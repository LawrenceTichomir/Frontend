<script lang="ts">
import {defineComponent } from 'vue';
import TestComponent from '@/components/TestComponent.vue';
import TheWelcome from '@/components/TheWelcome.vue';


export default defineComponent({
  name: "TihiView",
  components: {
    TheWelcome,
  },
  data() {
    return {
      username: "Pes"
    }
  }
})

</script>

<template>
    <div>
        <RouterLink :to="'/about'">klick me maybe</RouterLink>
        <TheWelcome/>
    </div>
</template>