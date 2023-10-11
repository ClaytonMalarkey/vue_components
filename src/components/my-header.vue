<template>
    <header>
        <img id="logo" src="../assets/logo.jpg"/>
        <h1>TITLE</h1>
        <nav id="main-nav">
            <a class="nav-item">home</a><a class="nav-item">products</a><a class="nav-item">contactus</a>
        </nav>
    </header>
  </template>
  
  <script>
  
  export default {
    name: 'App',
    }
  </script >
    <header></header>
  
  
  <!-- Styles of component -->
  <style scoped>
    header {
        background-color: red;
        color: white;
        display:grid;
        grid-template-columns: 1fr 1fr 4fr;
    }
    #logo {
        width: 50px;
        height: 50px;
        border-radius: 50%;
        display: grid;
        align-self: center;
        justify-self: center;
        padding: 10px;
    }
    #main-nav {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        justify-self: end;
        align-self: center;
        align-items: center;
        justify-items: center;
    }
    .nav-item {
        display:grid;
        padding: 20px;
    }


  </style>
  