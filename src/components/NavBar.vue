<template>
  <nav>
    <ul>
      <li class="active">
        <router-link :to="{ name: 'home_page' }" exact-active-class="exact-active">INÍCIO</router-link>
      </li>
      <li>
        <router-link :to="{ name: 'my_favorites' }" exact-active-class="exact-active">FAVORITOS</router-link>
      </li>
    </ul>
    <span><strong>Github</strong> <i>Search</i></span>
  </nav>
</template>

<script></script>

<style scoped>
  nav {
    background-color: #D9D9D9;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    padding: 15px 80px 15px 30px;
  }

  span {
    width: 298px;
    height: 84px;
    font-family: 'Inter';
    font-size: 30px;
    color: #000000;
  }

  ul {
    float: right;
  }

  ul li {
    display: inline-flex;
    padding-left: 20px;
  }
  
  li a {
    text-decoration: none;
    color: #000000;
    font-weight: 700;
  }

  .exact-active {
    color: #FF0000;
  }

</style>
