<script lang="ts">
	type Props = {
		category: string;
	};

	let { category }: Props = $props();
</script>

<span
	class="w-fit rounded-full border border-lime-500 bg-neutral-800 px-6 font-fira text-xs font-bold text-white"
>
	{category}
</span>
