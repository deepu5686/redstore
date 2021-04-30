<template>
   <header>

<div class="header">
    <div class="container">
        <div class="navbar">
            <div class="logo">
                <img src= "@/assets/images/logo.png" :style="{width: '125px'}" alt="">
            </div>
            <nav>
                <ul id="MenuItems">
                    <li><a href="">Home</a></li>
                    <li><a href="">Products</a></li>
                    <li><a href="">About</a></li>
                    <li><a href="">Contact</a></li>
                    <li><a href="">Account</a></li>
                </ul>
            </nav>
            <img src="@/assets/images/cart.png" :style="{width:'30px', height:'30px'}" alt="">
            <img src="@/assets/images/menu.png" class="menu-icon" onclick="menuToggle()">
        </div>
    
      </div>
 </div>
   </header>
</template>

<script>
export default {
    name: 'Header'
}
</script>