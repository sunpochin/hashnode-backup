## Vuejs <router-link> same route but different parameter

I want to filter product-list by [ men / women / all ] category, using the same **ProductList.vue**, but it doesn't refresh.
```
// headerPart.vue
						<nav class="main-nav">
							<router-link class="route" to="/cate/men">Men</router-link>
							<router-link class="route" to="/cate/women">Women</router-link>
							<router-link class="route" to="/cate/all">All</router-link>
						</nav>

```
Solutions: 
```
// App.vue
		<router-view :key="$route.path"></router-view>

```

https://stackoverflow.com/questions/56131100/vuejs-router-link-same-route-but-different-parameter


https://stackoverflow.com/questions/42603583/vue-js-same-component-with-different-routes

https://dev.to/erefor/vue-tip-same-component-different-route-4fme

snapshot by branch: https://github.com/sunpochin/vue2-ecommerce/tree/gender_filter

