## Crop and center images with CSS, Not found solution when visiting https://[website].netlify.app/products



1. quote: 
"In your public folder (folder which contains index.html) create a file called _redirects with no extension. Then, type the following inside it:

/*    /index.html    200
"

https://stackoverflow.com/a/63738122/720276
https://medium.com/@ishoshot/page-not-found-on-reload-vuejs-netlify-c71716e97e6


=== 
2. product-covers
https://stackoverflow.com/questions/11552380/how-to-automatically-crop-and-center-an-image

branch:
https://github.com/sunpochin/vue2-ecommerce/tree/product-covers

在 ProductCard.vue 裡面，
```
.center-cropped {
	width: 100%;
	height: 250px;
	/* background-position: center center;
	background-repeat: no-repeat; */
	overflow: hidden;
}

.center-cropped img {
	object-fit: cover;
	height: 100%;
	width: 100%;

	border-radius: 9px;
}
```