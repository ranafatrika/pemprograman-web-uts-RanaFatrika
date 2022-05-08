<script setup>
import Navbar from "../components/Navbar.vue";

</script>
<template>
  <navbar />
  <h1 class="namasurah text-start" v-if="chapter">{{chapter.name_arabic}}
    <br>{{chapter.verses_count}} Ayat</h1>
  <hr>
  <p class="info" v-if="chapter_info">{{chapter_info.text}}</p>
  <p v-if="audio_file" class="has-text-right">
  </p>
</template>


<style>

</style>
