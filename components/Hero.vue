<template>
  <v-parallax height="600" src="/man_with_tools.png" alt="Man with tools">
          <v-layout row wrap>
              <v-flex xs10 offset-xs1 sm6 offset-sm1 align-self-center class="presentation">
                  <div class="services mb-3">
                      diagnostic - conseil - dépannage - expertise
                  </div>
                  <div class="motto mb-4">
                    Un concierge à votre domicile, pour tous conseils et services
                  </div>
                  <v-btn outline round large color="#000" class="action-button">Allons-y !</v-btn>
              </v-flex>
          </v-layout>
      </v-parallax>
</template>


<style lang="scss" scoped>
    .presentation {
        color: rgba(34, 34, 34, 0.932);
        border-radius: 15px;
        .services {
            text-transform: uppercase;
            font-size: 18px;
        }
        .motto {
            font-size: 37px;
            font-weight: 700;
        }
        .action-button {
            margin: 0;
        }
    }

</style>



