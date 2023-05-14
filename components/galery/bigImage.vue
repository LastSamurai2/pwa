<template>
    <div>
        <img :src="image" class="img" />
    </div>
</template>
<script>
export default {
  name: 'BigImage',
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
    width: 50%;
    /* display: block; */
    margin-left: auto;
    margin-top: auto;
}
</style>