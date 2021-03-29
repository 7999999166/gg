<script>
  import './nedb.min.js';
  var db = new Nedb({
    filename: 'AppData.db',
    autoload: true
  });
  import './halfmoon.min.css';
  import halfmoon from 'halfmoon';
  import { RouterView, Link } from '@bjornlu/svelte-router';

  
  
</script>
<nav>
    <Link to="/">Home</Link>
    <Link to="/products">Products</Link>
    <Link to="/about-us">About Us</Link>
    <Link to="/login">Login</Link>
    <Link to="/cart">Cart</Link>
  </nav>
  <RouterView />


