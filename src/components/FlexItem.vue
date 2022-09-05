<template>
  <div>
    <div class="container">
      <div class="items item1">1</div>
      <div class="items item2">2</div>
      <div class="items item3">3</div>
      <div class="items item4">4</div>
    </div>
  </div>
</template>
  
  <script>
export default {
  name: "FlexItem",
};
</script>
  
  <style>
.container {
  display: flex;
  background: red;
}
.container > div {
  width: 100%;
  background: yellow;
  margin: 10px;
  text-align: center;
  line-height: 50px;
  border: 1px solid black;
  /* flex-direction: row-reverse; */
  /* justify-content:flex-end; */
  /* align-content: flex-end; */
}
</style>
  