<template>
  <div class="services">
    <div class="header text-xs-center">Nos services</div>
    <div class="card-wrapper">
      <div class="image"></div>
      <div class="text">
        <div class="title">1. Conseil et diagnostic</div>
        <div class="content">
          <div>
            <v-icon color="#FF8C00">check</v-icon>
            <span>Déplacement au domicile</span>
          </div>
        </div>
        <div class="content">
          <div>
            <v-icon color="#FF8C00">check</v-icon>
            <span>Etablissement du diagnostic</span>
          </div>
        </div>
        <div class="content">
          <div>
            <v-icon color="#FF8C00">check</v-icon>
            <span>Réparation immédiate sur devis si bricolage/petits travaux ou mise en relation avec un artisan</span>
          </div>
        </div>
      </div>
    </div>
    <div class="card-wrapper">
      <div class="image"></div>
      <div class="text">
        <div class="title">2. Mise en relation avec nos artisans</div>
        <div class="content">
          <div>
            <v-icon color="#FF8C00">check</v-icon>
            <span>Trouve l'artisan ou l'entreprise qui vous accompagne</span>
          </div>
        </div>
        <div class="content">
          <div>
            <v-icon color="#FF8C00">check</v-icon>
            <span>Estimation des travaux à réaliser et devis</span>
          </div>
        </div>
        <div class="content">
          <div>
            <v-icon color="#FF8C00">check</v-icon>
            <span>Supervise la réalisation des travaux et garantie le résultat</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<style lang="scss" scoped>
.services {
  position: relative;
  margin: 40px;
  .header {
    font-size: 40px;
    font-weight: 400;
    margin: 40px;
  }
  .card-wrapper {
    display: flex;
    margin-bottom: 60px;
    max-width: 750px;
    margin-left: auto;
    margin-right: auto;
    @media (max-width: 801px) {
      flex-direction: column;
      align-items: center;
    }
    .image {
      min-width: 200px;
      height: 200px;
      background-color: grey;
      border-radius: 5px;
    }
    .text {
      margin-left: 50px;
      @media (max-width: 801px) {
        margin-left: 0;
      }
      .title {
        padding: 20px;
        @media (max-width: 801px) {
          text-align: center;
          padding-top: 30px;
        }
      }
      .content {
        font-family: 'Open Sans', sans-serif;
        margin-bottom: 5px;
        div {
          display: flex;
          align-items: flex-start;
        }
        span {
          font-size: 18px;
          margin-left: 10px;
        }
      }
    }
  }
}
</style>



