<template>
  <div class="loadingBar">
    <div class="percentage" />
  </div>
</template>

<script>
export default {
    name : 'ProgressBar' ,

    
}
</script>

<style scoped>
.loadingBar{
    position: relative;
    width: 400px;
    height: 30px;
    border-radius: 15px;
    overflow: hidden;
    border-bottom: 1px solid #ddd;
    box-shadow: inset 1px 2px 4px rgb(99, 96, 96);
    border: 1px solid rgb(2, 9, 6);
}

.percentage{
    position: absolute;
    top: 1px;
    left: 1px;
    right: 1px;
    background-color: aqua;
    display: block;
    height: 100%;
    width: 50% ;
    border-radius: 15px;
    background-size: 30px 30px ;
}



</style>