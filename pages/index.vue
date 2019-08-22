<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6>
      <h1 class="headline">Welcome to Fun Quiz</h1>
      <div>
        <h1>real-time quizes</h1>
      </div>
      <v-form>
        <v-text-field>
          <p slot="label">Please enter your name</p>
        </v-text-field>
        <v-spacer />
        <v-btn color="primary" nuxt to="/waitingRoom">Continue to Quiz</v-btn>
      </v-form>
    </v-flex>
  </v-layout>
</template>

<script>
export default {};
</script>
