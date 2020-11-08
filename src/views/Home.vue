<template>
  <div class="home">
    <h1>Home Page</h1>
    <v-btn class="green white--text">CLICK ME</v-btn>
    <v-btn depressed dark color="green">CLICK ME AGAIN</v-btn>
    <v-btn flat color="green">CLICK</v-btn>
    <button
      type="button"
      class="v-btn v-btn--flat v-btn--icon v-btn--round theme--light v-size--default pink--text"
      id="no-background"
    >
      <span class="v-btn__content"
        ><i
          aria-hidden="true"
          class="v-icon notranslate mdi mdi-heart theme--light"
        ></i
      ></span>
    </button>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
};
</script>
