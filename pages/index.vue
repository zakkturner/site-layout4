<template>
  <section class="home">
    <div class="home__container">
      <h1 class="home__container__title">Arlo <span>Studios</span></h1>
      <p class="home__container__subtitle">Digital Agency</p>
    </div>
  </section>
</template>

<script>
export default {
  head() {
    return {
      title: 'Arlo Studios | Home',
    }
  },
}
</script>

<style lang="scss">
.home {
  background: url('../assets/img/background.jpeg') no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  -webkit-box-shadow: inset 40px 0px 300px 200px rgba(0, 0, 0, 0.92);
  -moz-box-shadow: inset 40px 0px 300px 200px rgba(0, 0, 0, 0.92);
  box-shadow: inset 40px 0px 300px 200px rgba(0, 0, 0, 0.92);
  &__container {
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    &__title {
      color: #fff;
      font-size: 45px;
      text-transform: uppercase;
      font-weight: 700;
      margin-bottom: 20px;
      span {
        color: #ff214f;
      }
    }

    &__subtitle {
      color: #fff;
    }
  }
}
</style>
