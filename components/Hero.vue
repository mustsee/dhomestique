<template>
  <v-parallax
    height="600"
    src="/rico-bleu.png"
    alt="Portrait of a craftsman smilling wearing blue work"
  >
    <v-layout row wrap>
      <v-flex xs10 offset-xs1 sm6 offset-sm1 align-self-center class="presentation">
        <div class="services mb-4">diagnostic - conseil - dépannage - expertise</div>
        <div
          class="motto mb-5"
        >Un concierge à votre domicile pour tous dépannages, conseils et services</div>
        <div class="phone_number mb-3">
          <div class="wrapper">
            <v-icon color="#FF8C00" medium>local_phone</v-icon>
            <span>06 58 86 95 90</span>
          </div>
        </div>
        <div
          class="proximity"
        >Service de proximité : Neuilly-sur-Seine, Levallois-Perret, Courbevoie</div>
      </v-flex>
    </v-layout>
  </v-parallax>
</template>


<style lang="scss" scoped>
.presentation {
  //color: rgba(34, 34, 34, 0.932);
  color: rgba(0,0,0,0.87);
  .services {
    text-transform: uppercase;
    font-size: 21px;
    font-weight: 500;
    color: #c40b0b;
  }
  .motto {
    font-size: 37px;
    font-weight: 700;
  }
  .action-button {
    margin: 0;
  }
  .phone_number {
    display: flex;
    font-size: 26px;
    .wrapper {
      font-weight: 700;
      padding: 5px 30px;
      border: solid 1px black;
      border-radius: 45px;
      text-overflow: ellipsis;
      white-space: nowrap;
      overflow: hidden;
      width: auto;
    }
  }
  .proximity {
    font-size: 16px;
  }
}
</style>



