<script>
import Splide from '@splidejs/splide';
import '../splide.min.css';
import { onMount } from 'svelte';
 onMount(() => {
     var splide = new Splide( '.splide' , {
	type    : 'loop',
	perPage : 1,
	autoplay: true } );
    splide.mount();
});



</script>
<style>
    .mm{
        width: 100vw;
        height: 500px;
    }
</style>

<h1>I m Cart Page</h1>
<div class="splide">
	<div class="splide__track">
		<ul class="splide__list">
			<li class="splide__slide"><img src="1.jpg" alt="1" class="mm"></li>
			<li class="splide__slide"><img src="2.jpg" alt="2" class="mm"></li>
			<li class="splide__slide"><img src="3.jpg" alt="3" class="mm"></li>
		</ul>
	</div>	
</div>
