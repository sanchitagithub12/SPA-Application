<template>
  <v-row class="align-center">
    <v-col cols="12" sm="8">
      <v-sheet class="mx-auto pa-4" elevation="8" max-width="800">
        <v-row>
          <v-col cols="12" sm="12">
            <v-row>
              <v-col cols="12" sm="6">
                <v-text-field
                  v-model="message4"
                  label="Name"
                  outlined
                  clearable
                  color="pink"
                ></v-text-field>
              </v-col>
              <v-col cols="12" sm="6">
                <v-text-field
                  v-model="message4"
                  label="Email"
                  outlined
                  clearable
                  color="pink"
                ></v-text-field>
              </v-col>
            </v-row>
            <v-row>
              <v-col cols="12" sm="6">
                <v-text-field
                  v-model="message4"
                  label="Subject"
                  outlined
                  clearable
                  color="pink"
                ></v-text-field>
              </v-col>
              <v-col cols="12" sm="6">
                <v-text-field
                  v-model="message4"
                  label="Phone Number"
                  outlined
                  clearable
                  color="pink"
                ></v-text-field>
              </v-col>
            </v-row>
            <v-row>
              <v-col cols="12" sm="12">
                <v-textarea
                  outlined
                  name="input-7-4"
                  label="Solo textarea"
                  color="pink"
                ></v-textarea>
              </v-col>
            </v-row>
            <v-row>
              <v-col cols="12" sm="12">
                <v-btn depressed color="pink" rounded class="white--text" large>
                  Primary
                </v-btn>
              </v-col>
            </v-row>
          </v-col>
        </v-row>
      </v-sheet>
    </v-col>
    <v-col cols="12" sm="4">
      <v-sheet class="mx-auto" elevation="8" max-width="500" max-height="300">
        <v-list two-line>
          <v-list-item>
            <v-list-item-icon>
              <v-icon color="pink"> mdi-map-marker </v-icon>
            </v-list-item-icon>

            <v-list-item-content>
              <v-list-item-title class="grey--text text--darken-3"
                ><b>Address: </b></v-list-item-title
              >
              <v-list-item-subtitle
                >1828 Johns Drive Glenview, IL 60025</v-list-item-subtitle
              >
            </v-list-item-content>
          </v-list-item>
          <v-list-item>
            <v-list-item-icon>
              <v-icon color="pink"> mdi-email </v-icon>
            </v-list-item-icon>

            <v-list-item-content>
              <v-list-item-title class="grey--text text--darken-3"
                ><b>Email: </b></v-list-item-title
              >
              <v-list-item-subtitle>support@ganial.com</v-list-item-subtitle>
            </v-list-item-content>
          </v-list-item>
          <v-list-item>
            <v-list-item-icon>
              <v-icon color="pink"> mdi-phone </v-icon>
            </v-list-item-icon>

            <v-list-item-content>
              <v-list-item-title class="grey--text text--darken-3"
                ><b>Phone: </b></v-list-item-title
              >
              <v-list-item-subtitle>(224) 228-8475</v-list-item-subtitle>
            </v-list-item-content>
          </v-list-item>
          <v-list-item>
            <v-list-item-icon>
              <v-icon color="pink"> mdi-web </v-icon>
            </v-list-item-icon>

            <v-list-item-content>
              <v-list-item-title class="grey--text text--darken-3"
                ><b>Website: </b></v-list-item-title
              >
              <v-list-item-subtitle>www.ganial.com</v-list-item-subtitle>
            </v-list-item-content>
          </v-list-item>
        </v-list>
      </v-sheet>
    </v-col>
  </v-row>
</template>