<template>
  <div>Child4</div>
</template>

<script>
import log from '../mixins/log.js'

export default {
  data() {
    return {
      name: 'child4'
    }
  },
  mixins: [log]
}
</script>