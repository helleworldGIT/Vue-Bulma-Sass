<template>
  <div>
    <!-- BULMA TEST -->
    <div class="columns">
      <div class="column is-12">
        <h1 class="has-text-info title is-1">
          This is a Bulma test!
        </h1>
        <h4 class="has-text-info subtitle has-text-success">
          Hello, this is Bulma: I'm easier than Bootstrap!
        </h4>
          <button class="button is-primary">
            A primary button.
          </button>
          <button class="button is-link">
            A link button.
          </button>
          <button class="button is-danger">
            A danger button.
          </button>
      </div>
    </div>
    <!-- /BULMA TEST -->
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
/** Importing our Bulma css file **/
@import url("../css/main.css");
</style>
