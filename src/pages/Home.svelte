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
        width: 1566px;
        height: 500px;
        
    }
    .jj{
        text-align: center;
        font-family: fantasy;
        color: #03045e;
        margin-top: 2%;
    }
    .ff{
        display: flex;
        justify-content: space-between;
    }
    .uu{
        margin-right: 30px;
        margin-left: 30px;
    }
    .zz{
        margin-top: 4.9%;
    }
</style>

<div class="splide zz">
	<div class="splide__track">
		<ul class="splide__list">
			<li class="splide__slide"><img src="1.svg" alt="1" class="mm"></li>
			<li class="splide__slide"><img src="2.svg" alt="2" class="mm"></li>
			<li class="splide__slide"><img src="3.svg" alt="3" class="mm"></li>
		</ul>
	</div>	
</div>
<h1 class="jj">Featured Product</h1>
<div class="ff">
<img src="1.svg" class="uu" alt="" width="300px" height="300px">
<img src="1.svg" class="uu" alt="" width="300px" height="300px">
<img src="1.svg" class="uu" alt="" width="300px" height="300px">
</div>
<div class="ff">
<img src="2.svg" class="uu" alt="" width="300px" height="300px">
<img src="2.svg" class="uu" alt="" width="300px" height="300px">
<img src="2.svg" class="uu" alt="" width="300px" height="300px">
</div>