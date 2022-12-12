<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Jamniki</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Jamniki</ion-title>
        </ion-toolbar>
      </ion-header>
           <div class="content">
        <div class="content-text">
         Jamnik – jedna z ras psów pochodząca z Niemiec. Niemiecka nazwa jamnika Dachshund oznacza w dosłownym tłumaczeniu "borsuczy pies", etymologia nazwy związana jest z jego zbliżoną do borsuków budową oraz wykorzystywaniem tej rasy do polowania na zwierzęta ryjące nory. Podlega próbom pracy. Jamnik to pies małego wzrostu, o krótkich nogach i wydłużonym tułowiu. Krótkość ich nóg jest spowodowana dziedziczną achondrodystrofią, którą ludzie wykorzystali do stworzenia tej rasy.
        <p></p>
        Jego pochodzenie budzi wątpliwości, miłośnicy jamników twierdzą, że pochodzi ze starożytnego Egiptu. Wizerunki psów o długich tułowiach i krótkich nogach pojawiły się na ścianach świątyń[4]. Już w starożytnym Egipcie istniały liczne rasy psów, z których część uwieczniono na płaskorzeźbach i posągach świątynnych. Archeolodzy znaleźli rysunki odpowiadające jamnikowi w świątyni w Bescheb. Naukowcy jednak nie są pewni, czy w tym przypadku chodzi o jamnika, czy o podobnego psa. Pierwsze europejskie wzmianki o jamnikach pochodzą ze średniowiecznych Niemiec. W XIV wieku można było przeczytać: "Psy o krótkich nogach wchodzą o wiele łatwiej pod ziemię niż inne i są bardziej przydatne do polowań na borsuki".
        </div>
        
      <img src="./Standard-Dachshund.jpg">
      </div>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';

export default defineComponent({
  name: 'Tab3Page',
  components: {IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});
</script>
