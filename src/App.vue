<template>
  <Nav/>
  <div class="owerlay">
    <router-view/>
  </div>
</template>


<script>
import Nav from '@/components/Nav.vue'
export default {
components:{
  Nav
},
data(){
return{

}
},
methods:{

},
}
</script>


<style >
:root{
  --bg-dark:#004d40;
  --text-dark:#004d40;
  --text-light:gold;
}
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 100%;
  height: 100vh;
  color: var(--text-dark);
}
.owerlay {
  width: 100%;
  height: calc(100vh - 75px);
  background-color: rgb(0,0,0,.3);
  position: relative;
}


</style>
