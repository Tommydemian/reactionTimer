<template>
  <header>
    <h1 class="header">I like to welcome ya'll to the TommyDemian Show</h1>
  </header>
  <div>
  <button 
    class="button"
    @click="onClick"
  >
      Play
    </button>
  </div>
</template>

<script>
export default {
  name: 'App',
  methods:{
    onClick() {
      
    }
  }
}

</script>

<style>
:root{
  --primary-clr:#ffffff;
  --alternate-text-clr: #000000;
  --secondary-clr:#14213d;
  --accent-clr: #fca311; 
  --accent-clr-pseudo: #efac3f;
}

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.header{
  margin-top: 3em;
  font-size: 2.5rem;
  color: #000000;
  text-align: center;
}

.button {

}
</style>
