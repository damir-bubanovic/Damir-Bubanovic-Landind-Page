<template>
  <div class="w-100 pb-2">
    <p >&copy; Copyright 2023 <a @click.stop.prevent="snackbar" class="text-blue-lighten-2 font-weight-black text-decoration-none" href="">Damir Bubanovic</a></p>
  </div>
</template>

<script>
  export default {
    name: 'FooterComponent',
    methods: {
      snackbar() {
        this.$emit('snackbarEmail', true);
      }
    }
  }
</script>