<template>
  <div id="app">
    <div class="container">
      <app-quote-grid :quotes="quotes"></app-quote-grid>
    </div>
  </div>
</template>

<script>

import QuoteGrid from './components/QuoteGrid.vue';

export default {
  data: function() {
    return {
      quotes: [
        'Just a Quote to see something'
      ],
      maxQuotes: 10
    }
  }
}
</script>

<style>

</style>
