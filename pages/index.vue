<template>
  <div class="main">
    <div class="left">
        <VerticalNav></VerticalNav>
    </div>
  
    <div class="right">
      <SlideOver class="toleft"></SlideOver>
      <Card></Card>
      <Carroussel></Carroussel>
    </div>
  </div>
</template>

<script lang="ts" setup>


</script>

<style>

.toleft {
  position: absolute;
  right: 10px;
}

.main {
  display:flex;
  flex-direction: row;
}

.left {
  width:2.5rem;
}

</style>