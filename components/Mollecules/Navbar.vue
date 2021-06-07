<template>
  <nav class="menu">
      <p class="logo">News</p>
      <ul class="nav-menu">
        <NuxtLink to="/">Link 1</NuxtLink>
        <NuxtLink to="detail">Link 2</NuxtLink>
        <!-- <a class="link-one" href="/"><li>Link 1</li></a> -->
        <!-- <a class="link-two" href="detail"><li>Link 2</li></a> -->
      </ul>
      <div class="header"> 
        <button class="hamburger">&#9776;</button>
        <button class="cross">&#735;</button>
      </div>  
    </nav> 
</template>

<script>
export default {
}
</script>

<style>
.menu {
    display: flex;
    justify-content: space-between;
    padding-right: 80px;
    padding-left: 80px;
    align-items:center;
    margin-top : 10px;
    position: relative;
}
.nav-menu {
    display : flex;
    align-items:center;
    list-style: none;
    }
    .menu ul a {
    text-decoration: none!important;
    cursor: pointer;
    color: black;
    margin : 0 20px
}

.header {
    width: auto; 
    background:#ffffff; 
    height: 60px; 
    line-height: 60px;
    align-self: flex-end;
    position: absolute;
    right: 20px;
    top: 50%;
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    display : none
}
#myBtn {
    display: none;
    position: fixed;
    bottom: 70px;
    right: 30px;
    z-index: 99;
    border: none;
    outline: none;
    background-color: red;
    color: white;
    cursor: pointer;
    padding: 15px;
    border-radius: 10px;
    font-size: 18px;
}
    #myBtn:hover {
    background-color: #555;
}
@media (max-width: 768px) {
    .nav-menu {
      width: 100%;
      display: none;
      padding: 0;
      margin: 0;
      float: right;
    }
    .menu {
        width: 100%;
    }
    .menu ul {
      padding-top: 70px;
    }
    .menu ul a {
      width: 100%;
      font-size: small;
      padding: 5px;
      line-height: 20px;
    }
    .menu ul li {
      text-align: center;
      margin: auto;
      width: 50%;
      border-bottom: 1px solid #dddddd;

    }
    .hamburger {
      position: relative;
    }
}
@media (max-width: 480px) {
    .nav-menu {
        width: 100%;
        height: auto;
        position: absolute;
        padding: 0;
        margin: 0;
        text-align: center;

    }
    .header {
        display: block;  
    }
    .menu ul a {
        display: table-cell;
        font-size: small;
        margin: auto;
        padding: auto;
    }
    .link-one {
        padding-top: 100px;
        width: 100%;
        float: left;
    }
    .link-two {
        width: 100%;
        float: left;
    }
    .hamburger {
        width: 30px;
        height: 30px;
        position: relative;
    }
    .cross {
        width: 30px;
        height: 30px;
    }
}
</style>