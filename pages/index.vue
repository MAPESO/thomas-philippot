<template>
  <v-app>
    <body>
      <div id="app">
        <v-app light>
          <v-toolbar class="white">
            <v-toolbar-title v-text="title"/>
          </v-toolbar>
          <v-content>
            <section>
              <v-parallax
                src="https://raw.githubusercontent.com/vuetifyjs/parallax-starter/master/template/assets/hero.jpeg"
                height="600">
                <v-layout
                  column
                  align-center
                  justify-center
                  class="white--text"
                >
                  <v-avatar size="200">
                    <img
                      src="/profil.jpg"
                      alt="Profil picture">
                  </v-avatar>
                  <h1 class="white--text mb-2 display-1 text-xs-center">{{ title }}</h1>
                  <div class="subheading mb-3 text-xs-center">Student Developper</div>
                </v-layout>
              </v-parallax>
            </section>

            <section>
              <v-layout
                column
                wrap
                class="my-5"
                align-center
              >
                <v-flex
                  xs12
                  sm4
                  class="my-3">
                  <div class="text-xs-center">
                    <h2 class="headline">I'm a french student learning new Javascript Frameworks</h2>
                    <span class="subheading">
                      I'm currently learning vue.js frameworks (mostly),
                      to build multi-platform web app.
                    </span>
                    <v-img
                      src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/53/Vue.js_Logo.svg/2000px-Vue.js_Logo.svg.png"
                      style="display: block; margin: auto;"
                      width="200"/>
                  </div>
                </v-flex>
                <v-flex xs12>
                  <v-container grid-list-xl>
                    <v-layout
                      row
                      wrap
                      align-center>
                      <v-flex
                        xs12
                        md4>
                        <v-card class="elevation-0 transparent">
                          <v-card-text class="text-xs-center">
                            <v-icon
                              x-large
                              class="blue--text text--lighten-2">color_lens</v-icon>
                          </v-card-text>
                          <v-card-title
                            primary-title
                            class="layout justify-center">
                            <div class="headline text-xs-center">Web Applications</div>
                          </v-card-title>
                          <v-card-text>
                            <v-layout
                              row
                              wrap>
                              <v-img
                                src="https://i.imgur.com/PzEm5j2.png"
                                alt="nuxt.js"
                                containt
                                aspect-ratio="1"/>
                            </v-layout>
                          </v-card-text>
                        </v-card>
                      </v-flex>
                      <v-flex
                        xs12
                        md4>
                        <v-card class="elevation-0 transparent">
                          <v-card-text class="text-xs-center">
                            <v-icon
                              x-large
                              class="blue--text text--lighten-2">flash_on</v-icon>
                          </v-card-text>
                          <v-card-title
                            primary-title
                            class="layout justify-center">
                            <div class="headline text-xs-center">Mobile Applications</div>
                          </v-card-title>
                          <v-card-text>
                            <v-layout
                              row
                              wrap>
                              <v-img
                                src="https://madewithvuejs.com/uploads/00/12/nativescript-vue.jpg"
                                alt="native-script vue"
                                contain
                                aspect-ratio="1"/>
                            </v-layout>
                          </v-card-text>
                        </v-card>
                      </v-flex>
                      <v-flex
                        xs12
                        md4>
                        <v-card class="elevation-0 transparent">
                          <v-card-text class="text-xs-center">
                            <v-icon
                              x-large
                              class="blue--text text--lighten-2">build</v-icon>
                          </v-card-text>
                          <v-card-title
                            primary-title
                            class="layout justify-center">
                            <div class="headline text-xs-center">Desktop Applications</div>
                          </v-card-title>
                          <v-card-text>
                            <v-layout
                              row
                              wrap>
                              <v-img
                                src="https://raw.githubusercontent.com/Thomas-Philippot/Desktop-meteo/master/src/renderer/assets/logo.png"
                                alt="electron vue"
                                containt
                                aspect-ratio="1"/>
                            </v-layout>
                          </v-card-text>
                        </v-card>
                      </v-flex>
                    </v-layout>
                  </v-container>
                </v-flex>
              </v-layout>
            </section>

            <section>
              <v-parallax
                src="./plane.jpg"
                height="380">
                <v-layout
                  column
                  align-center
                  justify-center>
                  <div class="headline white--text mb-3 text-xs-center">Web development has never been easier</div>
                  <em>Kick-start your application today</em>
                </v-layout>
              </v-parallax>
            </section>

            <section>
              <v-container grid-list-xl>
                <v-layout
                  row
                  wrap
                  justify-center
                  class="my-5">
                  <v-flex
                    xs12
                    sm4>
                    <v-card class="elevation-0 transparent">
                      <v-card-title
                        primary-title
                        class="layout justify-center">
                        <div class="headline">Company info</div>
                      </v-card-title>
                      <v-card-text>
                        Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
                        Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
                        Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.
                      </v-card-text>
                      <img
                        src="/stage1.png"
                        alt="stage picture">
                    </v-card>
                  </v-flex>
                  <v-flex
                    xs12
                    sm4
                    offset-sm1>
                    <v-card class="elevation-0 transparent">
                      <v-card-title
                        primary-title
                        class="layout justify-center">
                        <div class="headline">Contact us</div>
                      </v-card-title>
                      <v-card-text>
                        Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
                      </v-card-text>
                      <v-list class="transparent">
                        <v-list-tile>
                          <v-list-tile-action>
                            <v-icon class="blue--text text--lighten-2">phone</v-icon>
                          </v-list-tile-action>
                          <v-list-tile-content>
                            <v-list-tile-title>777-867-5309</v-list-tile-title>
                          </v-list-tile-content>
                        </v-list-tile>
                        <v-list-tile>
                          <v-list-tile-action>
                            <v-icon class="blue--text text--lighten-2">place</v-icon>
                          </v-list-tile-action>
                          <v-list-tile-content>
                            <v-list-tile-title>Chicago, US</v-list-tile-title>
                          </v-list-tile-content>
                        </v-list-tile>
                        <v-list-tile>
                          <v-list-tile-action>
                            <v-icon class="blue--text text--lighten-2">email</v-icon>
                          </v-list-tile-action>
                          <v-list-tile-content>
                            <v-list-tile-title>john@vuetifyjs.com</v-list-tile-title>
                          </v-list-tile-content>
                        </v-list-tile>
                      </v-list>
                    </v-card>
                  </v-flex>
                </v-layout>
              </v-container>
            </section>
          </v-content>
        </v-app>
      </div>
    </body>
  </v-app>
</template>

<script>
  export default {
    data: () => ({
      title: 'Thomas Philippot'
    })
  }
</script>
