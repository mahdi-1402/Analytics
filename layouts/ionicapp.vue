<template>
  <IonApp dir="rtl">
    Header
    <!-- page content will appear here -->
    <slot />
    Footer
  </IonApp>
</template>

<script setup>
import { IonApp } from "@ionic/vue"
// useHead({
//   viewport: 'width=device-width, initial-scale=1, maximum-scale=1, viewport-fit=cover',
// })
</script>