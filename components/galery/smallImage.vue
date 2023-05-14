<template>
    <div class="sm-galery-img">
        <img :src="image" class="img" />
    </div>
</template>
<script>
export default {
  name: 'SmallImage',
  props: {
    image: {
        type: String,
        default: () => 'Pusty string'
    }
  }
}
</script>
<style scoped>
.img {
    width: 200px;
}
.sm-galery-img
{
    float: left;
    margin-top: 2%;
    margin-right: 1%;

}
</style>