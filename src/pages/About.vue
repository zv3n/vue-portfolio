<template>
  <Layout class="intro">
    <div class="intro__wrapper">
      <h1 class="intro__h1">Hi, you found me!</h1>
      <br>
      <h2 class="intro__h2">I am a Junior Web Developer currently building awesome things @ <a class="intro__link" href="https://argonauten.de/">Argonauten</a> .</h2>
    </div>
    <div class="about">
      <div class="about__wrapper">
        <h1 class="about__h1">Hi, you found me!</h1>
        <br>
        <h2 class="about__h2">I am a Junior Web Developer currently building awesome things @ <a class="intro__link" href="https://argonauten.de/">Argonauten</a> .</h2>
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
    margin-top: 20px;
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
    margin-top: 20px;
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



</style>