<template>
  <div class="w-fit">
    <VuePDF :pdf="pdf" :page="1" />
    <VuePDF :pdf="pdf" :page="2" />
  </div>
</template>

<script setup>
import { VuePDF, usePDF } from '@tato30/vue-pdf'
import '@tato30/vue-pdf/style.css'

const { pdf } = usePDF({
  url: 'CV_Ivan.pdf',
  enableXfa: true
})
</script>
