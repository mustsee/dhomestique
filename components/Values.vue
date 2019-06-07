<template>
  <div class="values">
    <div class="header text-xs-center">À propos</div>
    <div class="card-wrapper">
      <div class="image"></div>
      <div class="text">
        <div class="content">
          <div>
            L’entreprise est née de mon
            expérience de plus de 20 ans en tant que gardien de résidences de
            standing à Neuilly.
          </div>
          <div>
            J’ai pu constater que les besoins des résidents
            sont d’avoir une personne de confiance et disponible pour
            les dépanner dans des situations quotidiennes.
          </div>
          <div>
            Les services que rend
            un gardien sont nombreux, ils vont du simple fait de changer une
            ampoule ou resserrer un robinet à la mise en relation pour des
            réparations ou travaux plus importants.
          </div>
          <div>
            J’effectue un premier
            constat et diagnostic de la situation avant toute intervention, et
            m’occupe de la mise en relation avec des artisans de confiance et à
            moindre coût.
          </div>
          <div>
            Dhomestique propose à Neuilly et ses environs, les services et la disponibilité
            d’un gardien à domicile pour gérer en toute confiance vos pannes ou
            problèmes du quotidien.
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<style lang="scss" scoped>
.values {
  position: relative;
  margin: 40px;
  .header {
    font-size: 40px;
    font-weight: 400;
    margin: 40px;
    font-family: "Oswald", sans-serif;
  }
  .card-wrapper {
    display: flex;
    align-items: center;
    margin-bottom: 50px;
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
      border-radius: 50%;
    }
    .text {
      margin-left: 50px;
      padding: 10px 0 20px 0px;
      @media (max-width: 801px) {
        margin-left: 0;
        padding-top: 30px;
      }
      .content {
        font-family: 'Roboto', sans-serif;
        font-size: 18px;
        margin-bottom: 5px;
        div {
          margin-left: 10px;
          margin-bottom: 15px;
        }
      }
    }
  }
}
</style>



