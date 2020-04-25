<template>
  <Layout class="intro">
    <div class="intro__wrapper">
      <h1 class="intro__h1">Hi, you found me!</h1>
      <br>
      <h2 class="intro__h2">I am a Junior Web Developer currently building awesome things @ <a class="intro__link" href="https://argonauten.de/">Argonauten</a> .</h2>
    </div>
    <div class="about">
      <div class="about__wrapper">
        <g-image class="about__img" src="~/assets/water.jpg" width="500"/>
        <h2 class="about__h1">A fresh start!</h2>
        <p class="about__text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet adipisci, vero consectetur repellendus quidem aliquam placeat, explicabo similique nostrum, assumenda saepe suscipit perspiciatis non illum quasi voluptatem accusantium a pariatur.</p>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Intro'
  }
}
</script>

<style lang="scss">

.intro {

  height: 100vh;
  padding: 0;


  &__wrapper{
    //background-color: #fed7d7;
    height: 100%;
    padding: 20px;
    background-repeat: no-repeat;
    height: 100%;
   // padding: 5% 60px;
    background-size: 100%;
    background-image: linear-gradient(212deg, #FFA48D 3%, #6799FF 100%);
  }

  &__h1{
    margin-top: 10px;
    color:rgba(0, 0, 0, 0);
    font-size: 2.5em;
    -webkit-text-stroke: 1px #fff;
    font-weight: 900;
  }

  &__h2{
    color:rgba(0, 0, 0, 0);
    font-size: 2.5em;
    -webkit-text-stroke: 1px #fff;
    font-weight: 900;
  }

  &__link{
    color:rgba(0, 0, 0, 0);
    -webkit-text-stroke: 1px rgb(12, 0, 124);
    font-weight: 900;
  }
}

.about {

  height: 100vh;
  padding: 0;


  &__wrapper{
      display: grid;
    grid-template-columns: 50px 200px 1fr;
    grid-template-rows: 260px 50px 100px 1fr;
    height: 100%;
    padding: 20px;
    background-repeat: no-repeat;
    height: 100%;
    background-size: 100%;
    background-image: linear-gradient(-32deg, #FFA48D 3%, #6799FF 100%);
  }

  &__img{
    grid-column: 1/2;
    grid-row-start: 1;
    max-width: 250px;
  }

  &__h1{
    grid-column: 2/4;
    grid-row-start: 2;
    color:rgba(0, 0, 0, 0);
    font-size: 2.5em;
    -webkit-text-stroke: 1px #fff;
    font-weight: 900;
  }

  &__text{
    grid-column: 1/4;
    grid-row-start: 4;
    color: white;
    font-size: 1em;
    font-weight: 900;
  }


  &__link{
    color:rgba(0, 0, 0, 0);
    -webkit-text-stroke: 1px rgb(12, 0, 124);
    font-weight: 900;
  }
}



</style>