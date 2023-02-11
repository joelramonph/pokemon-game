<template>
  <h1>¿Quien es este pokemon?</h1>
  <!-- TODO img -->
    <PokemonPicture />
  <!-- TODO Opciones -->
  <PokemonOption />
</template>

<script>
import PokemonPicture from "@/components/PokemonPicture";
import PokemonOption from '@/components/PokemonOption';

export default {
    components:{PokemonPicture, PokemonOption}  
    
}
</script>

<style>

</style>
