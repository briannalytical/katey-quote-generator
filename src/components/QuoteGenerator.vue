<template>
  <div class="page-container">
    <header class="header">
      <h1 class="title">Katey Quote Generator</h1>
      <h3>The Best Manager I Ever Had</h3>
    </header>
    <div class="quote-container">
      <div class="thought-bubble">
        <span class="quote-mark quote-mark-left">"</span>
        <span class="quote-mark quote-mark-right">"</span>
        <p class="quote-text">{{ currentQuote }}</p>
        <p class="quote-author">- Katey Piazza</p>
      </div>
      <button @click="fetchQuote" class="btn-generate" :disabled="loading">
        {{ loading ? 'Loading...' : 'Generate' }}
      </button>
    </div>
  </div>
  <h1>Katey Quote Generator</h1>
  <h3>The Best Manager I've Ever Had</h3>
</template>

<script>

</script>

<style scoped>

</style>