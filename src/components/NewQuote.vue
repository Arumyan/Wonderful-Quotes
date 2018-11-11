<template>
  <div class="row">
    <div class="col-sm-8 col-sm-offset-2 col-xs-12 col-md-6 col-md-offset-3">
      <label for="">Quote</label>
      <textarea class="form-control" rows="3" v-model="quote"></textarea>
    </div>

    <div class="col-sm-8 col-sm-offset-2 col-xs-12 col-md-6 col-md-offset-3">
      <button class="btn btn-success" @click.prevent="createNew">Add Quote</button>
    </div>
  </div>
</template>

<script>
import Quote from './Quote.vue';
export default {
  data() {
    return {
      quote: ''
    }
  },
  methods: {
    createNew() {
      
    }
  }
}
</script>

<style>

</style>


