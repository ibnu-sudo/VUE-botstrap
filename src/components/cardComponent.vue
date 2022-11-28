<template>
<div>
    <div class="d-flex justify-content-around p-5">
        <div class="card" style="width: 18rem;">
            <img class="card-img-top" :src="require('@/assets/img/' + index + '.png')" alt="Card image cap">
            <div class="card-body">
                <h5 class="card-title">{{title}}</h5>
                <p class="card-text">IDR {{price}}</p>
            </div>
        </div>
    </div>
</div>
</template>

<script>


export default {
  name: 'cardComponent',
  props: [
      "title","price","index"
  ]
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
