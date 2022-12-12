<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Wyżły</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Wyżły</ion-title>
        </ion-toolbar>
      </ion-header>
        <div class="content">
        <div class="content-text">
         Wyżeł – pies myśliwski charakteryzujący się stójką właściwą tylko tej grupy psów. Wyżły wywodzą się z półwyspu Iberyjskiego. Przeznaczone do polowań w polu suchym, wodzie i w lesie na ptactwo i zwierzynę drobną. Średniej wielkości: od 50 do 70 cm w kłębie. Dzielą się na wyżły brytyjskie (pointer, seter angielski, seter szkocki (gordon), seter irlandzki) i kontynentalne (wyżły francuskie, niemieckie, węgierskie, włoskie i inne). Umaszczenie dowolne, sierść od krótkiej przez szorstką do długiej – zależnie od wzorca uznanego przez FCI.
         <p></p>
         Wyżeł ten ma sylwetkę prostokątną i stosunkowo masywną. Ważną proporcją jest stosunek wysokości do długości tułowia, który wynosi 8:9. Głowa jest dość obszerna i krótka, stop nie jest wyraźnie zaznaczony. Linia grzbietu lekko jest lekkoopadająca ku tyłowi, najwyższa w kłębie.
        </div>
        
      <img src="./Wyżeł_duński_123.jpg">
      </div>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';

export default defineComponent({
  name: 'Tab4Page',
  components: {IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});
</script>
