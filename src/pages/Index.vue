<template>
  <q-page class="flex flex-center">
    <q-select
      v-model="selected"
      :options="['luke', 'matt', 'jake']"
    />
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'PageIndex'
})
</script>
