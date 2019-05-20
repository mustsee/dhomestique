<template>
  <div class="services">
    <div class="header text-xs-center">
      Votre maison a besoin de <span class="name">D<span class="home">HOME</span>STIQUE</span> ?
    </div>
    <div class="card-wrapper">
      <div class="image">
        <img src="/expert.png" alt="icon of an expert" width="auto" height="150px">
        <div class="pricing">
          Tarif 30€ TTC
        </div>
      </div>
      <div class="text">
        <div class="title">Diagnostic et conseil</div>
        <div class="content">
          <div>
            <v-icon color="#FF8C00">check</v-icon>
            <span>Déplacement à votre domicile</span>
          </div>
        </div>
                <div class="content">
          <div>
            <v-icon color="#FF8C00">check</v-icon>
            <span>Recherche et détermine la panne</span>
          </div>
        </div>
        <div class="content">
          <div>
            <v-icon color="#FF8C00">check</v-icon>
            <span>Pose un diagnostic de réparation ou de remplacement de vos équipements</span>
          </div>
        </div>
        <div class="content">
          <div>
            <v-icon color="#FF8C00">check</v-icon>
            <span>Apporte une solution</span>
          </div>
        </div>
      </div>
    </div>
    <div class="card-wrapper">
      <div class="image">
        <img src="/tools.png" alt="icon of tools" width="auto" height="90px">
        <div class="devis">
          Devis<br/>Gratuit
        </div>
      </div>
      <div class="text">
        <div class="title">Pour tous dépannages et bricolages, mise en relation avec nos artisans</div>
        <div class="content">
          <div>
            <v-icon color="#FF8C00">check</v-icon>
            <span>Trouve l'artisan ou l'entreprise qui vous accompagne</span>
          </div>
        </div>
        <div class="content">
          <div>
            <v-icon color="#FF8C00">check</v-icon>
            <span>Estimation des travaux et réalisation d'un devis gratuit</span>
          </div>
        </div>
        <div class="content">
          <div>
            <v-icon color="#FF8C00">check</v-icon>
            <span>Supervise l'exécution des travaux et garantie le résultat escompté</span>
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
  font-family: 'Roboto', sans-serif;
  .header {
    font-size: 40px;
    font-weight: 400;
    margin: 40px 0 40px 0;
    font-family: "Lobster", cursive;
    letter-spacing: 1px;
    @media (max-width: 801px) {
      font-size: 35px;
    }
    .name {
      font-family: 'Roboto', sans-serif;
      font-weight: 500;
      letter-spacing: 0;
        .home {
        color: #ff8c00;
      }
    }
  }
  .card-wrapper {
    display: flex;
    align-items: center;
    margin-bottom: 80px;
    padding-top: 40px;
    max-width: 750px;
    margin-left: auto;
    margin-right: auto;
    @media (max-width: 801px) {
      flex-direction: column;
      align-items: center;
    }
    .image {
      position: relative;
      min-width: 200px;
      height: 200px;
      background-color: #ff8c00;
      border-radius: 5px;
      border: 2px solid rgba(0,0,0,0.87);
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .pricing, .devis {
      position: absolute;
      border: 1px solid rgba(0,0,0,0.87);
      border-radius: 25px;
      background: #c40b0b;
      color: #fff;
      padding: 10px 20px;
      font-size: 20px;
      text-align: center;
      font-weight: bold;
    }
    .pricing {
      top: -35px;
      left: -50px;
    }
    .devis {
      top: 135px;
      left: -50px;
      border-radius: 50%;
      width: 110px;
      height: 110px;
      display: flex;
      justify-content: center;
      align-items: center;
      @media (max-width: 801px) {
        top: -65px;
        left: 135px;
      }      
    }
    .text {
      margin-left: 50px;
      @media (max-width: 801px) {
        margin-left: 0;
      }
      .title {
        padding: 0 20px 20px 20px;
        font-family: "Lobster", cursive !important;
        font-size: 25px !important;
        @media (max-width: 801px) {
          text-align: center;
          padding-top: 30px;
        }
      }
      .content {
        margin-bottom: 5px;
        @media (min-width: 501px) and (max-width: 801px) {
          margin: 0 50px 0 50px;
        }
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



