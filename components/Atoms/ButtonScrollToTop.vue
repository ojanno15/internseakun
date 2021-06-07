<template>
  <div>
      <button @click="topFunction()" id="myBtn" title="Go to top">Top</button>
  </div>
</template>

<script>
window.onscroll = function() {scrollFunction()};

function scrollFunction() {

  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 1000) {
      
    document.getElementById("myBtn").style.display = "block";
  
  } else {
      
    document.getElementById("myBtn").style.display = "none";
  
  }
}
export default {
    methods: {
        topFunction() {
            document.body.scrollTop = 0;
            document.documentElement.scrollTop = 0;
        }
    }
}
</script>

<style>

</style>