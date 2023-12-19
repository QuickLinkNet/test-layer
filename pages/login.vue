<script setup lang="ts">
const props = defineProps({
  image: {
    type: String,
    required: false,
  },
});

const default_image = "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ0qCreqkTZL0F0bF9kZctFE1XVFocO__70kw&usqp=CAU";
</script>

<template>
  <div class="login-container">
    <div class="logo-container">
      <img :src="props.image ? props.image : default_image" alt="Logo"> <!-- Ersetzen Sie logo.png mit Ihrem Projekt-Logo -->
    </div>
    <form class="login-form">
      <input type="text" placeholder="Benutzername" required>
      <input type="password" placeholder="Passwort" required>
      <button type="submit">Einloggen</button>
    </form>
  </div>
</template>