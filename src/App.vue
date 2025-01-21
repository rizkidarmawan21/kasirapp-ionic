<template>
  <ion-app>
    <ion-router-outlet />
  </ion-app>
</template>

<script setup lang="ts">
import { IonApp, IonRouterOutlet } from '@ionic/vue';
import { StatusBar } from '@capacitor/status-bar';

StatusBar.setOverlaysWebView({ overlay: false });
</script>
