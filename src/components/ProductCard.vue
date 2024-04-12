<script>
    export default {
        name : 'ProductCard',
        props : {
            thumb: String,
            series: String,
        }
    }
</script>

<template>
    
    <div class="product-card">
        <div>
            <img :src="thumb">
        </div>

        <h3>{{ series }}</h3>
    </div>

</template>

<style scoped lang="scss">
// @use '..style/partials/_variables' as*;

.product-card {
    width: calc((100% / 6) - 6px);
    padding: 10px;
    margin: 5px 0;
}

h3 {
    color: white;
    font-size: 13px;
    text-align: center;
}
</style>