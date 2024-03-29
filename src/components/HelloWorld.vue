<template>
  <div class="hello">
   <input v-bind:placeholder="inputDeger" /> <br />
   <input v-bind:maxlength="maxDeger" /> <br />
   <a v-bind:href="link" > Facebook Git</a>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',

data(){
  return{
    inputDeger:'deneme input değer ',
    maxDeger :5,
    link : 'https://www.facebook.com'
  }
}
}
</script>

