<template>
  <header class="hello">
    <div class="container">
      <h1>La mia prima app con Vue CLI!</h1>
    </div>
  </header>
</template>

<script>
export default {
  name: 'HelloWorld',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.container{
  margin: 0 auto;
  width: 1000px;
}
/*Display none  messo solo per non cancellare 1.esercizio */

.hello{
  background-color: #183446;
  height: 10vh;
  display: none; /*HERE*/
}

.hello h1{
  color: #fff;
  text-align: center;
  padding: 15px 0;
}
</style>
