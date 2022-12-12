<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Teriery</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Teriery</ion-title>
        </ion-toolbar>
      </ion-header>
      <div class="content">
        <div class="content-text">
         Hans Rāber powołując się na kilku autorów przypuszcza, że miejscem powstania psów terierowatych są Wyspy Brytyjskie, a większość odmian tych psów pochodzi od popularnego w dawnej Anglii pinczera wiejskiego szorstkowłosego i krótkowłosego (E.Hauck). Słowo terier figurowało już w języku staroangielskim i pojawia się w książce dotyczącej ras psów występujących w XV wieku. Autorem tej pozycji jest przeorysza z klasztoru Sopwell – Juliane Berners. Opisuje ona w niej grupę psów zaliczanych do norowców, określonych mianem teroures.
        <p> </p>
        W późniejszych źródłach – Turberville (1575), Buffon (XVIII wiek) – są przytaczane opisy psów zaliczanych do terierów zarówno wysokonożnych, jak i niskonożnych. Rozróżnienie to wiązało się z użytkowością tych psów. Krótkonożna odmiana z szorstką sierścią była ceniona za upór i odwagę w wypłaszaniu i dławieniu zwierzyny z nor. Psy gładkowłose z kończynami dłuższymi brały udział w nagankach na zwierzynę leśną.
        <p> </p>        
        </div>
        
      <img src="./teriery.jpg">
      </div>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';

export default defineComponent({
  name: 'Tab2Page',
  components: {IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});
</script>
