<template>
  <v-parallax
    height="600"
    src="/rico-bleu.png"
    alt="Portrait of a craftsman smilling wearing blue work"
  >
    <v-layout row wrap>
      <v-flex xs10 offset-xs1 sm6 offset-sm1 align-self-center class="presentation">
        <div class="services mb-4">
          <span class="chip-custom">diagnostic</span>
          <span class="chip-custom">conseil</span>
          <span class="chip-custom">dépannage</span>
          <span class="chip-custom">expertise</span>
          </div>
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
  @media (max-width: 801px) {
    line-height: 1.4;
  }  
  .services {
    display: flex;
    @media (max-width: 530px) {
      flex-wrap: wrap;
    } 
    .chip-custom {
      display: flex;
      justify-content: center;
      align-items: center;
      text-transform: uppercase;
      font-weight: 500;
      font-size: 13px;
      height: 32px;
      margin: 4px;
      padding: 0 12px;
      background: #fff;
      border-radius: 28px;
      border: 1px solid rgba(0,0,0,0.87);
      color: rgba(0,0,0,0.87);
    }
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
      background: #fff;
      font-weight: 700;
      padding: 5px 30px;
      border: solid 1px rgba(0,0,0,0.87);
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



