<template>
  <div>
    <Header./>
    <main class="container">
      <Sobre />
      <Formacao />
      <Experiencia />
      <Hobbies />
      <Contato />
    </main>
    <footer>&copy; 2025 - Isabelle de Oliveira Padilha. Todos os direitos reservados.</footer>
  </div>
</template>

<script setup>
import Header from './components/Header.vue'
import Sobre from './components/Sobre.vue'
import Formacao from './components/Formacao.vue'
import Experiencia from './components/Experiencia.vue'
import Hobbies from './components/Hobbies.vue'
import Contato from './components/Contato.vue'
</script>
