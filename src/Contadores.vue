<template>
    <div class="contadores">
        <app-contador/>
    </div>
</template>

<script>
import Contador from './Contador.vue'
export default {
    name: 'contadores',
    components: { 'app-contadores': Contador }
}
</script>

<style>

</style>