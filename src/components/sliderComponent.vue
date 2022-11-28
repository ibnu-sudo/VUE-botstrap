<template>
<div>
    <div class="bg-light p-3">
        <div class="my-5">
            <h2>Complete Your Room</h2>
            <h2>with What We Designed</h2>
        </div>
        <div class="d-flex justify-content-around">
        <cardslide title="Cangkir Mauttie" price="89.300.000" index="chair-2"></cardslide>
        <cardslide title="Syail Ammeno" price="89.000.000" index="chair-1"></cardslide>
        <cardslide title="Saman Kaka" price="14.000.000" index="chair-3"></cardslide>
        <cardslide title="Lino Lino" price="22.000.000" index="chair-4"></cardslide>
        </div>
    </div>
</div>
</template>

<script>
import cardslide from "./cardComponent.vue"


export default {
  name: 'sliderComponent',
  components:{ cardslide }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
