<template>
  <q-layout view="lHh Lpr lFf">
    <q-page-container style="background-color: #cfd8dd; overflow-x: auto">
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'BlankLayout'
})
</script>
