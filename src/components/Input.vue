<template lang="html">
  <div class="container">
    <h2>Input</h2>

    <div class="placeholder-show">
      <input type="email" name="email" placeholder=" " />
      <label for="email">Email</label>
    </div>
    <div class="placeholder-show">
      <input type="password" name="password" placeholder=" " />
      <label for="password">Password</label>
    </div>
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
