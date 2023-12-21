<template>
  <div class="about">
    <h1>This is an about page</h1>
    <div>
      <v-row>
        <v-col cols="12" md="6"> <v-text-field label="Last Name"></v-text-field></v-col>
        <v-col cols="12" md="6">
          <v-text-field label="First Name"></v-text-field>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" md="6"> <v-text-field label="Address"></v-text-field></v-col>
        <v-col cols="12" md="6">
          <v-text-field label="Address 2"></v-text-field>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" md="4"> <v-text-field label="City"></v-text-field></v-col>
        <v-col cols="12" md="4">
          <v-select label="State" :items="['TN', 'GA', 'KY']"></v-select>
        </v-col>
        <v-col cols="12" md="4">
          <v-text-field label="Zip"></v-text-field>
        </v-col>
      </v-row>
      <div class="button-row">
        <v-btn color="primary" flat>Primary</v-btn>
        <v-btn color="accent" flat>Accent</v-btn>
        <v-btn color="error" flat>Error</v-btn>
        <v-btn color="success" flat>Success</v-btn>
        <v-btn color="warning" flat>Warning</v-btn>
      </div>
    </div>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    max-width: 1000px;
    margin: auto;
  }
  .button-row {
    width: max-content;
    margin: auto;
  }
}
</style>
