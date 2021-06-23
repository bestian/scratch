<template>
  <q-page class="flex flex-center">
    <vedio
      width="520"
      height="300"
      controls=""
      :src="'./Scratch.mp4'" />
  </q-page>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'PageIndex'
})
</script>
