<template>
  <div class="hello">
    <br>
    <h1>{{ msg }}</h1>
  <div class="flex">
    <img src="https://i.postimg.cc/QdV96Mx2/IMG-9863-1.jpg" class="img-02" alt="">
    <div>
      <h2 class="h-02">Who Am I?</h2>
      <p class="txt-01">  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus pariatur, tenetur quae nulla doloribus unde adipisci iusto, id aliquam quia, enim reprehenderit praesentium voluptate placeat maxime ipsa rerum voluptates esse?</p>  
      <button class="btn">Click For Resume</button>
    </div>
  </div>
  </div>
    <div>
    <h3>Social Links</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul>
    </div>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.img-02 {
  width: 14rem;
  border-radius: 2rem;
}
.flex {
  display: flex;
}
.txt-01 {
  font-size: 24px;
  font-weight: 700;
  text-align: center;
}
.h-02 {
  text-decoration: underline;
}
.btn {
  border-radius: 1rem;
  width: 8rem;
  height: 2rem;
  font-weight: 600;
}
.btn:hover {
  transform: scale(1.3);
  transition: ease-out 4s;
}
</style>
