<template>
<div class="block">
<p class="block-content" >Click Me</p>
</div>
</template>

<script>
export default {
  name: 'Block',
}
</script>

<style >

.block {
width: 30%;
height: 20em;
background-color: var(--secondary-clr);
border: none;
border-radius:6px;
margin: 2em auto;
display: flex;
justify-content: center;
align-items: center;
}
.block-content {
  font-size: 2rem;
  color: var(--primary-clr);

}


</style>
