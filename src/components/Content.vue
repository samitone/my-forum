<template>
    <div class="content-main">
        <h1>Example Content</h1>
        <img :src="require('../assets/' + img + '')" class="content-image">
    </div>
</template>

<script>
export default {
  name: 'Content',
  props: {
    img: String
  },
}
</script>

<style scoped>

.content-main {
    max-width: 500px;
    margin: auto;
}

.content-image {
    max-width: 100%;
}

</style>
