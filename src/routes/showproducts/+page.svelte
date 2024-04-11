<!-- <script>
	/** @type {import('./$types').PageData} */
	export let data;
	import LucideIcon from '../../common/components/LucideIcon.svelte';
	let isGridview = false;
	const toggleGridview = () => (isGridview = !isGridview);
</script>
<div
				class="grid grid-cols-1 mt-5 md:grid-cols-2 [&.gridView]:grid-cols-1 xl:grid-cols-4 group [&.gridView]:xl:grid-cols-1 gap-x-5 {isGridview
					? 'gridView'
					: ''}"
				id="cardGridView"
			>
				{#each data.PRODUCTSLIST as product, index}
					{#if index < 8}
						<div class="card md:group-[.gridView]:flex relative">
							<div class="relative group-[.gridView]:static p-8 group-[.gridView]:p-5">
								<a
									href="#!"
									class="absolute group/item toggle-button top-6 ltr:right-6 rtl:left-6 {product.isFavorite
										? 'active'
										: ''}"
									><LucideIcon
										name="Heart"
										class="size-5 text-slate-400 fill-slate-200 transition-all duration-150 ease-linear dark:text-zink-200 dark:fill-zink-600 group-[.active]/item:text-red-500 dark:group-[.active]/item:text-red-500 group-[.active]/item:fill-red-200 dark:group-[.active]/item:fill-red-500/20 group-hover/item:text-red-500 dark:group-hover/item:text-red-500 group-hover/item:fill-red-200 dark:group-hover/item:fill-red-500/20"
									/></a
								>
								<div
									class="group-[.gridView]:p-3 group-[.gridView]:bg-slate-100 dark:group-[.gridView]:bg-zink-600 group-[.gridView]:inline-block rounded-md"
								>
									<img src={product.img} alt="" class="group-[.gridView]:h-16" />
								</div>
							</div>
							<div
								class="card-body !pt-0 md:group-[.gridView]:flex group-[.gridView]:!p-5 group-[.gridView]:gap-3 group-[.gridView]:grow"
							>
								<div class="group-[.gridView]:grow">
									<h6
										class="mb-1 truncate transition-all duration-200 ease-linear text-15 hover:text-custom-500"
									>
										<a href="/apps/ecommerce/products-overview">{product.product_name}</a>
									</h6>

									<div class="flex items-center text-slate-500 dark:text-zink-200">
										<div class="mr-1 text-yellow-500 shrink-0 text-15">
											<i class="ri-star-fill" />
											<i class="ri-star-fill" />
											<i class="ri-star-fill" />
											<i class="ri-star-fill" />
											<i class="ri-star-half-line" />
										</div>
										({(Math.random() * 1000).toFixed(0)})
									</div>
									<h5 class="mt-4 text-16">
										{product.price}<small
											class="font-normal line-through text-slate-500 dark:text-zink-200"
											>{product.original_price}</small
										>
									</h5>
								</div>

								<div
									class="flex items-center gap-2 mt-4 group-[.gridView]:mt-0 group-[.gridView]:self-end"
								>
									<button
										type="button"
										class="w-full bg-white border-dashed text-slate-500 btn border-slate-500 hover:text-slate-500 hover:bg-slate-50 hover:border-slate-600 focus:text-slate-600 focus:bg-slate-50 focus:border-slate-600 active:text-slate-600 active:bg-slate-50 active:border-slate-600 dark:bg-zink-700 dark:text-zink-200 dark:border-zink-400 dark:ring-zink-400/20 dark:hover:bg-zink-600 dark:hover:text-zink-100 dark:focus:bg-zink-600 dark:focus:text-zink-100 dark:active:bg-zink-600 dark:active:text-zink-100"
										><LucideIcon name="ShoppingCart" class="inline-block size-3 leading-none" />
										<span class="align-middle">Add to Cart</span></button
									>
									
								</div>
							</div>
						</div>
						end col & card-->
					<!-- {/if}
				{/each}
			</div> -->

		