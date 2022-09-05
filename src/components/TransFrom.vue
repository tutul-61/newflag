<template>
    
<div class="box2">

</div>
     
     
  </template>
  
  <script>
 
  
  export default {
    name: 'TransFrom',
   
  }
  </script>
  
  <style scoped>
    .box2{
    position:relative ;
    width: 200px;
    height: 200px;
    background: orange;
    margin: 200px auto;
    top:0;
    right: 0;
    bottom: 0;
    left: 0;
    transition: 3s;
    transition-delay: 2s;
    

  }
  .box2:hover{
    background:red;
    transform: scale(2);
    
  }

  
  </style>
  