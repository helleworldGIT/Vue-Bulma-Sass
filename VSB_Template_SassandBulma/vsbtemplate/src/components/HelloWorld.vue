<template>
  <div>
    <!-- HTML TEST -->
    <p>
      SASS PART:
    </p>
      <h1>This is my new project</h1>
      <h3>I'm implementing SASS!</h3>
      <br><br>
    <!-- /HTML TEST -->
    <!-- BULMA TEST -->
    <p>
      BULMA PART:
    </p>
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
<style lang="scss" scoped>
// IMPORTING CUSTOM PARTIAL FROM CSS FOLDER
@import '../css/fonts.scss';
/** Importing our Bulma css file **/
@import url("../css/main.css");

// DECLARING CUSTOM SCSS VARIABLES
$font-custom-size: 25px;
$color-customred: #ff563c;
$color-customgreen: #3cffa1;

@mixin separator{
  font-size: $font-custom-size;
  color: orangered;
  font-weight: bold;
  text-align: center;
  margin: 20px;
}

// STYLES
h1{
  color: $color-customred;
  font-family: $merriweather-font;
  font-size: $font-custom-size;
}
h3{
  color: $color-customgreen;
  font-family: $catamaran-font;
  font-size: $font-custom-size;
}
p{
  @include separator();
}
</style>
