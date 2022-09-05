<template>
  <div>
  
    <div class="box">
        <div class="box1">
        </div>     
    </div>
  
   
  </div>
  </template>
  
  <script>
  
  
  export default {
    name: 'TableItem'
    
  }
  </script>
  
  <style scoped>
  .box{
    width: 400px;
    height: 200px;
    background: green;
    position:relative;
    margin:200px auto;
  }
  .box1{
    position: absolute;
    width: 100px;
    height: 100px;
    background: red;
    top:0; 
    left:0;
    bottom:0;
    right:0;
    margin:auto;
    border-radius: 50%;
    
   
  }
  
  
  </style>
  