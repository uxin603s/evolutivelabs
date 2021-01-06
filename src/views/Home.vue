<template>
  <Purchase></Purchase>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import Purchase from '@/components/Purchase.vue' // @ is an alias to /src

@Component({
  components: {
    Purchase
  }
})
export default class Home extends Vue {}
</script>
