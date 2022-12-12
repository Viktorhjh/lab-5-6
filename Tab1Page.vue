<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Owczarki</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">            
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Owczarki</ion-title>
        </ion-toolbar>
        <title>Ionic 1vv</title>
      </ion-header>
      <div class="content">
        <div class="content-text">
          Kiedy w Europie Środkowej rozwinął się ruch kynologiczny, a jednocześnie rozwój miast pociągnął za sobą wzrost przestępczości, zrodziło się zainteresowanie psem służbowym. W Niemczech utworzono związek, którego celem było popieranie hodowli psów owczarskich, w których widziano dobry materiał na psa służbowego dla wojska i policji. Związek ten nazywał się Phylax.
          <p></p>
          Po ośmiu latach działalności Phylaksu powstał nowy związek, utworzony przez rotmistrza Maxa von Stephanitza 3 kwietnia 1899 roku. Kiedy von Stephanitz wraz ze swoim przyjacielem Arturem Mayerem był w Karlsruhe na wielkiej ogólnokrajowej wystawie hodowlanej, ich uwagę zwrócił jeden z prezentowanych na tej wystawie psów. Był to pracujący owczarek w typie pierwotnym, silny, wytrzymały i sprężysty. Pies wabił się Hektor Linksrhein i stał się nowym nabytkiem von Stephanitza do jego psiarni w Grafrath. Hodowca zaczął wabić go Horand von Grafrath i zarejestrował go pod numerem 1 w księdze hodowlanej owczarków niemieckich.
          <p></p>
          Od chwili odkrycia Horanda von Stephanitz i jego współpracownicy rozpoczęli poszukiwanie suk, u których występowały cechy zbliżone do Horanda, aby rozpowszechnić jego typ. Wstępnie selekcjonowano szczenięta tuż po urodzeniu, a końcowa selekcja następowała w wieku, kiedy ich charakter, temperament i budowa mogły być ostatecznie ustalone.          

        </div>

        <div class="content-img">             
          <img src="./owczarki-niemiecki-wyszkow-533233917.jpg">
          <img src="./Black_German_Shephard.jpg">
        </div>
        
  
      
      </div>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';

export default  defineComponent({
  name: 'Tab1Page',
  components: {IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});
</script>
<style>
 
</style>