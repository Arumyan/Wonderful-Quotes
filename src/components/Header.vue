<template>
  <div class="row">
    <div class="col-sm-12">
      <h3>Quotes added</h3>
      <div class="progress progress-striped">
        <div class="progress-bar progress-bar-success"
             role="progressbar"
             aria-valuenow="20"
             aria-valuemin="0"
             aria-valuemax="100"
             :style="{width: (quoteCount / maxQuotes) * 100 + '%'}"
        >
            {{quoteCount}} / {{maxQuotes}}
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    props: ['quoteCount', 'maxQuotes']
  }
</script>
