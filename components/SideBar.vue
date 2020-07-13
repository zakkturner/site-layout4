<template>
  <header class="header">
    <div class="header__container">
      <div class="header__container__img">
        <img
          src="https://frenify.com/envato/marketify/html/arlo_1/img/logo/light.png"
          alt="logo"
          srcset=""
        />
      </div>
      <nav class="header__container__nav">
        <nuxt-link to="/" class="header__container__nav--link">Home</nuxt-link>
        <nuxt-link to="/about" class="header__container__nav--link"
          >About</nuxt-link
        >
        <nuxt-link to="/services" class="header__container__nav--link"
          >Services</nuxt-link
        >
        <nuxt-link to="/portfolio" class="header__container__nav--link"
          >Portfolio</nuxt-link
        >
        <nuxt-link to="/contact" class="header__container__nav--link"
          >Contact</nuxt-link
        >
      </nav>
      <div class="header__container__social-links">
        <a href="#">
          <font-awesome-icon
            :icon="['fab', 'linkedin']"
            class="header__container__social-links--icon"
          />
        </a>
        <a href="#">
          <font-awesome-icon
            :icon="['fab', 'github']"
            class="header__container__social-links--icon"
          />
        </a>

        <a href="#">
          <font-awesome-icon
            :icon="['fab', 'facebook']"
            class="header__container__social-links--icon"
          />
        </a>

        <a href="#">
          <font-awesome-icon
            :icon="['fab', 'instagram']"
            class="header__container__social-links--icon"
          />
        </a>

        <a href="#">
          <font-awesome-icon
            :icon="['fab', 'behance']"
            class="header__container__social-links--icon"
          />
        </a>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'SideBar',
}
</script>

<style lang="scss">
.header {
  width: 100%;
  height: 100vh;
  background-color: #191919;
  box-shadow: 0 0 30px rgba(255, 255, 255, 0.03);
  overflow: hidden;

  &__container {
    height: 100%;
    padding: 60px;
    &__img {
    }
    &__nav {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      &--link {
        font-size: 16px;
        color: #fff;
        text-decoration: none;
        padding: 10px 0;
        border-bottom: 1px solid #303030;
        width: 100%;
        padding: 15px;
      }
    }
    &__social-links {
      color: #fff;
      justify-self: center;
      align-self: center;
      padding-top: 15px;
      &--icon {
        margin-right: 10px;
        color: #fff;
      }
    }
  }
}
</style>
