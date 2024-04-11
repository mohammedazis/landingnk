<script>import Landingpage from "/src/routes/(noauthlayout)/landing/product/+page.svelte"</script>
<style lang="scss">
	@import '/assets/scss/tailwind.scss';
	@import '/assets/scss/icons.scss';
	
</style>
<svelte:head>
	<script src="https://cdn.jsdelivr.net/npm/apexcharts"></script>
</svelte:head>


<div class="fixed inset-0 bg-slate-900/40 dark:bg-zink-800/70 z-[1049] backdrop-overlay hidden" id="backDropDiv"></div>
<Landingpage/>