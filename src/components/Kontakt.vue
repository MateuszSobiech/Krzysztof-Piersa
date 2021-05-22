<template>
  <div class="kontaktWrapper">
    <div class="tytul">Kontakt</div>
    <p>
      Możesz się ze mną skontaktować przez numer telefonu
      <a href="tel:+48608442847">608-442-847</a> lub poniższy formularz:
    </p>
    <Form />
  </div>
</template>

<script>
import Form from './Form.vue'

export default {
  name: 'Kontakt',
  components: { Form }
}
</script>

<style>
.kontaktWrapper {
  padding: 15px;
  background-color: white;
  text-align: center;
}
</style>