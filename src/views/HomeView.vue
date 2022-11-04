<script setup lang="ts">
import HelloWorld from '@/components/HelloWorld.vue'
import { IonButton, IonToggle, IonInput, IonItem, IonLabel } from '@ionic/vue';
</script>
   
<template>
   <div>
      <HelloWorld msg="You did it!" />
      <br>
      <br>
      <h5>Some Ionic Components:</h5>
      <ion-button>Default</ion-button>
      <br/>
      <ion-toggle color="medium"></ion-toggle>
      <br/>
      <ion-item fill="solid">
         <ion-label position="floating">Input Label</ion-label>
         <ion-input mode="ios" placeholder="Enter text"></ion-input>
      </ion-item>
   </div>
</template>
