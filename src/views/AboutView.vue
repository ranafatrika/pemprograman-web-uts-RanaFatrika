<script setup>
import Navbar from "../components/Navbar.vue";

</script>

<template>
 <navbar />
  <section class="tentang">
    <div class="about">
      <h1>About Me</h1>
    </div>
  </section>
  <div class="accordion accordion-flush bg-light" id="accordionFlushExample">
    <div class="accordion-item bg-light">
      <h2 class="accordion-header" id="flush-headingOne">
        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
          Contact
        </button>
      </h2>
      <div id="flush-collapseOne" class="accordion-collapse collapse" aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">
        <div class="accordion-body">ig: ranaaa_ftka | fb: Rana Fatrika | twitter: Rana Fatrika | Call me: 081268223669</div>
      </div>
    </div>
    </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
.tentang{
  background: #87cefa;
}
.tentang h1{
  padding: 20px;
  flex-grow: 1;
  flex-shrink: 0;
  margin-top: 2rem;
  text-align: center;
  font-family: monospace;
}
.accordion-button{
  text-align: center;
}
.accordion-body{
  margin-top: 20px;
  text-align: center;
  color: blue;
}
</style>
