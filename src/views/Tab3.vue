<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Cartella</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';

export default  {
  name: 'Tab3',
  components: { ExploreContainer, IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
}
</script>