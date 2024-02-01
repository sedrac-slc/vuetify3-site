<template>
  <v-app>
    <v-app-bar class="border-b" flat>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <v-app-bar-title>My app</v-app-bar-title>
      <template #append>
        <v-btn icon class="mr-3">
          <v-badge color="warning" :content="37">
            <v-icon icon="mdi-bell-outline"></v-icon>
          </v-badge>
        </v-btn>
        <v-avatar>
          <v-img
            src="https://images.pexels.com/photos/774909/pexels-photo-774909.jpeg"
            cover
          ></v-img>
        </v-avatar>
      </template>
    </v-app-bar>
    <v-main>
      <v-container class="w-100">
        <h1>Dashboard</h1>
        <v-row>
          <v-col cols="12" sm="6" md="4" lg="3">
            <v-card>
              <v-img
                class="align-end text-white"
                src="https://images.pexels.com/photos/3049339/pexels-photo-3049339.jpeg"
              >
                <v-card-title>Casa no mar</v-card-title>
              </v-img>
              <v-card-title>Casa no mar</v-card-title>
              <v-card-subtitle class="pt-2"> Number 10 </v-card-subtitle>
              <v-card-text>
                <div>Whitehaven Beach</div>
                <div>Whitsunday Island, Whitsunday Islands</div>
              </v-card-text>
              <v-card-actions>
                <v-btn variant="tonal" prepend-icon="mdi-chevron-down" color="primary">
                  ver mais
                </v-btn>
                <v-btn variant="tonal" prepend-icon="mdi-cart" color="success">
                  comprar
                </v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
          <v-col cols="12" sm="6" md="4" lg="3">
            <v-card>
              <v-img
                class="align-end text-white"
                src="https://images.pexels.com/photos/3049339/pexels-photo-3049339.jpeg"
              >
                <v-card-title>Casa no mar</v-card-title>
              </v-img>
              <v-card-title>Casa no mar</v-card-title>
              <v-card-subtitle class="pt-2"> Number 10 </v-card-subtitle>
              <v-card-text>
                <div>Whitehaven Beach</div>
                <div>Whitsunday Island, Whitsunday Islands</div>
              </v-card-text>
              <v-card-actions>
                <v-btn variant="tonal" prepend-icon="mdi-chevron-down" color="primary">
                  ver mais
                </v-btn>
                <v-btn variant="tonal" prepend-icon="mdi-cart" color="success">
                  comprar
                </v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
          <v-col cols="12" sm="6" md="4" lg="3">
            <v-card>
              <v-img
                class="align-end text-white"
                src="https://images.pexels.com/photos/3049339/pexels-photo-3049339.jpeg"
              >
                <v-card-title>Casa no mar</v-card-title>
              </v-img>
              <v-card-title>Casa no mar</v-card-title>
              <v-card-subtitle class="pt-2"> Number 10 </v-card-subtitle>
              <v-card-text>
                <div>Whitehaven Beach</div>
                <div>Whitsunday Island, Whitsunday Islands</div>
              </v-card-text>
              <v-card-actions>
                <v-btn variant="tonal" prepend-icon="mdi-chevron-down" color="primary">
                  ver mais
                </v-btn>
                <v-btn variant="tonal" prepend-icon="mdi-cart" color="success">
                  comprar
                </v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
          <v-col cols="12" sm="6" md="4" lg="3">
            <v-card>
              <v-img
                class="align-end text-white"
                src="https://images.pexels.com/photos/3049339/pexels-photo-3049339.jpeg"
              >
                <v-card-title>Casa no mar</v-card-title>
              </v-img>
              <v-card-title>Casa no mar</v-card-title>
              <v-card-subtitle class="pt-2"> Number 10 </v-card-subtitle>
              <v-card-text>
                <div>Whitehaven Beach</div>
                <div>Whitsunday Island, Whitsunday Islands</div>
              </v-card-text>
              <v-card-actions>
                <v-btn variant="tonal" prepend-icon="mdi-chevron-down" color="primary">
                  ver mais
                </v-btn>
                <v-btn variant="tonal" prepend-icon="mdi-cart" color="success">
                  comprar
                </v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script setup>
//
</script>
