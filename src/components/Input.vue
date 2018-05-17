<template lang="html">
  <div class="container">
    <h2>Input</h2>
    <div class="placeholder-show">
      <input type="text" name="text" placeholder=" " />
      <label for="text">text label</label>
    </div>

    <button class="btn">Button</button>
    <button class="btn-primary btn">Button</button>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="scss">
  @import './my_input_scss.scss';

  h2 {
    padding-bottom:2rem;
  }
</style>
