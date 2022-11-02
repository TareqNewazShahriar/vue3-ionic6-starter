<script lang="ts">
import HelloWorld from '@/components/HelloWorld.vue'
import { IonButton, IonToggle } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
   components: { HelloWorld, IonButton, IonToggle }
});
</script>

<template>
   <main>
      <ion-button>Default</ion-button>
      <ion-toggle color="medium"></ion-toggle>
      <hr>
      <HelloWorld msg="You did it!" />
   </main>
</template>
