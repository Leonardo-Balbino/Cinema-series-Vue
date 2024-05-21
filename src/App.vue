<template>
  <header>
    <router-link to="/">
      <h1>
        <span>VUE</span>
        Movies
      </h1>
    </router-link>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Lato:wght@400;700&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:wght@100&family=Rubik:wght@300&family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap" rel="stylesheet">
  </header>
  
  <router-view/>
</template>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'poppins';

  &::selection {
    background: transparent(#42B883, 0.5);
  }

  body {
    background-color: #35495E;
  }

  a {
    text-decoration: none;
  }

  header {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 10px 16px;
    background-color: #2C3D4E;
    box-shadow: 0px 0px 6px rgba(0,0,0,0.1);

    h1{
      color: #fff;
      font-size: 60px;
      
      
      

      span {
        color: #42B883;
        -webkit-text-stroke: 2px #fff;
      }
    }
  }

}
</style>
