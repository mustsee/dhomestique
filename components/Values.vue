<template>
  <div class="values">
    <div class="header text-xs-center">À propos</div>
    <div class="card-wrapper">
      <div class="image"></div>
      <div class="text">
        <div class="content">
          <div>
            <span>
              Gardien d'immeuble à Neuilly-sur-Seine depuis 20 ans, je souhaite mettre aujourd'hui
              mes compétences au service du plus grand nombre.
            </span>
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
    font-family: "Lobster", cursive !important;
  }
  .card-wrapper {
    display: flex;
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
      padding: 20px;
      @media (max-width: 801px) {
        margin-left: 0;
        padding-top: 30px;
      }
      .content {
        font-family: sans-serif;
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



