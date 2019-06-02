<template>
  <div>
    <!-- HTML TEST -->
      <h1>This is my new project</h1>
      <h3>I'm implementing SASS!</h3>
    <!-- /HTML TEST -->
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

// DECLARING CUSTOM SCSS VARIABLES
$color-customred: #ff563c;
$color-customgreen: #3cffa1;

// STYLES
h1{
  color: $color-customred;
  font-family: $merriweather-font;
}
h3{
  color: $color-customgreen;
  font-family: $catamaran-font;
}
</style>
