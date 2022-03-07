<template>
  <div>
    <AppHeader />
    <section>
      <h2>Page Content</h2>
      <p>This section is directly on the index.vue file</p>
      <p>Maha</p>
      <P>I think i'm the last one to finish it, happy to finish it little earlier.</P>
    </section>
  </div>
</template>

<script>
import { defineComponent } from '@nuxtjs/composition-api'

export default defineComponent({
  name: 'IndexPage'
})
</script>
