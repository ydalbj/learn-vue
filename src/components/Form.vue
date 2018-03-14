<template>
  <form method="post" action="/projects" @submit.prevent="onSubmit">
    <div class="control">
      <label for='first' class="label">Fist Name</label>
      <input type="text" name="first" id="first" class="input" v-model="first" />
      <span class="help is-danger"></span>
    </div>
    <div class="control">
      <label for="last" class="label">Last Name</label>
      <input type="text" name="last" id="last" class="input" v-model="last" />
      <span class="help is-danger"></span>
    </div>
    <div class="control">
      <button class="button is-primary">submit</button>
    </div>
  </form>
</template>


<script>
export default {
  name: 'MyForm'
}
</script>

<style>
  @import "https://cdnjs.cloudflare.com/ajax/libs/bulma/0.2.3/css/bulma.css";
</style>

