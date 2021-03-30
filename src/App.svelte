<script>
  import './nedb.min.js';
  var db = new Nedb({
    filename: 'AppData.db',
    autoload: true
  });
  import './halfmoon.min.css';
  import halfmoon from 'halfmoon';
  import { RouterView, Link } from '@bjornlu/svelte-router';
  import './w3.css';

  
  
</script>
<style>
.bb{
display: flex;
justify-content: space-around;
height: 10vh;
align-items: center;
background-color: rgb(69, 163, 251);
width: 98.9%;
z-index:2 ;
}
.aa{
  font-size: larger; 
  margin-left: 5px;
}
.cc{
  color:#03045e;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
}
.cc:hover{
  color: aliceblue; 
}
.ff{
  margin-left: 20%;
  font-family: fantasy;
  font-size: xx-large;
}
.mm{
 color:#03045e; 
}
.yy{
  width: 40px;
  height: 40px;
}


</style>

  
 <div class="bb w3-top">
    <div class="aa" style="flex-grow: 1"><Link to="/"><span class="cc">Home</span></Link></div>
    <div class="aa" style="flex-grow: 1"><Link to="/products"><span class="cc">Products</span></Link></div>
    <div class="aa" style="flex-grow: 1"><Link to="/about-us"><span class="cc">About-Us</span></Link></div>
    <div class="aa ff" style="flex-grow: 8"><Link to="/"><span class="mm">G&G Steel</span></Link></div>
    <div class="aa" style="flex-grow: 1"><Link to="/login"><span class="cc">Login</span></Link></div>
    <div class="aa" style="flex-grow: 1"><Link to="/cart"><img src="cart.svg" alt="cart" class="yy"></Link></div>
 </div>
 <RouterView />