<template>
  <header>
    <h1 class="header">I like to welcome ya'll to the TommyDemian Show</h1>
  </header>
  <div class="button-container" >
  <button 
    class="button"
    @click="startGame">
      Play
    </button>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      isPlaying: false,
      delay: null
    }  
  },
  methods:{
    startGame() {
      this.delay = 2000 + Math.random() * 3000;
      this.isPlaying = true;
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
.button-container {
  display: flex;
  justify-content: center;
  align-items: center;
}
.button {
  margin: 2em auto;
  padding: 1em 1.5em;
  border: none; 
  border-radius: 6px;
  background-color: var(--accent-clr);
  transition:0.5s;
}
.button:hover {
  background-color: var(--accent-clr-pseudo);
}
</style>
