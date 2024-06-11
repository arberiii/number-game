<script context="module" lang="ts">
	const cache = new Map<string, Promise<DictionaryEntry>>();
</script>

<script lang="ts">
	export let word: string;
</script>

<div class="def">
	<div>Your number was <strong>{word}</strong>.</div>
</div>
