//!Creare un secondo componente Hero, che visualizza un jumbotron.
<template>
  <div id="hero" class="container-sm">
    <div class="hero-inner">
      <h1>Il mio sito Web</h1>
      <h2>Sottotitolo sito Web</h2>
      <a href="" class="btn">Scopri...</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>


<style scoped>
.container-sm {
  height: 100vh;
  margin: 0 auto;
  background-color: #046e8f;
}

#hero{
    display: flex;
    justify-content: center;
    align-items: center;

       background-image: linear-gradient(rgba(0, 0, 0, 0),rgba(0, 0, 0, 0.1)), url('https://picsum.photos/id/1051/3914/2935');
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
    background-attachment: fixed;
}

#hero .hero-inner{
 text-align:center;
}
#hero .btn {
    width: 200px;
    border: .5px thick #fff;
    padding: 5px 20px;
    border-radius: 20px;
    box-shadow: 2px 5px 10px #000;
}

#hero  a{
    display: inline-block;
    color: #fff;
    background-color: #183446;
    text-decoration: none;
    font-size: 1.5em;  

    margin: 30px 0;
}

#hero a:hover{
    color:#183446;
    border-color:#183446;
    background-color: #fff;
}

#hero a:active{
    scale: 1.05;
}
h1{
    font-size: 4em;
}
h2{
    font-size: 2em;
}
</style>

