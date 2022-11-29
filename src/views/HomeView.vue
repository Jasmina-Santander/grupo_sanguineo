<template>
  <div>
    <Portada/>
    <PrimeraVista />
    <Grupo />
    <factor />
    <filtroLista />
    <donaciones1 />
    <donaciones2 />
    <laboratorio />
    <Pie/>
    </div>
</template>

<script>
import Portada from "../components/Portada.vue"
import PrimeraVista from '@/components/PrimeraVista.vue';
import Grupo from '@/components/Grupo.vue';
import FiltroLista from '../components/FiltroLista.vue';
import Factor from '../components/Factor.vue';
import Donaciones1 from '../components/Donaciones1.vue';
import Donaciones2 from '../components/Donaciones2.vue';
import Laboratorio from '../components/Laboratorio.vue';
import Pie from '../components/Pie.vue';
export default {
  name:"HomeView",
    components: { Portada, PrimeraVista , Grupo, FiltroLista, Factor, Donaciones1, Donaciones2, Laboratorio, Pie}
}
</script>

<style>

</style>