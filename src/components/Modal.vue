<template>
  <div class="backdrop">
      <div class="modal">
          <h1>Modal Title</h1>
          <p>Modal Content</p>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .backdrop{
        position : fixed;
        top : 0;
        background: rgba(0, 0, 0, 0.5);
        width : 100%;
        height: 100%;
    }
    .modal{
        width: 400px;
        padding: 20px;
        margin: 100px auto;
        background-color: white;
        border-radius: 10px;
    }
</style>