<template>
   <span>
<header class="toolbar toolbar-header">
  <h1 class="title">Header the tabs</h1>
</header>

<div class="tab-group">
  <div class="tab-item">
    <span class="icon icon-cancel icon-close-tab"></span>
    Tab
  </div>
  <div class="tab-item active">
    <span class="icon icon-cancel icon-close-tab"></span>
    Tab active
  </div>
  <div class="tab-item">
    <span class="icon icon-cancel icon-close-tab"></span>
    Tab
  </div>
  <div class="tab-item tab-item-fixed">
    <span class="icon icon-plus"></span>
  </div>
</div>
   </span>
</template>

<script>
   export default {
      name:"tabBar"
   }
</script>

<style>

</style>