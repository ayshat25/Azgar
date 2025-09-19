<script setup lang="ts">
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <!-- <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main> -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap" rel="stylesheet">

  <header>
    <div class="header_top">
      <div class="container">
        <div class="header_top_inner">
          <div class="header_top_left">
            Бесплатная доставка
          </div>
          <div class="header_top_right">
            <div class="header_top_faqs">Faqs</div>
            <div class="header_top_help">Нужна помощь?</div>
          </div>
        </div>
      </div>
    </div>

    <div class="header_main">
      <div class="container">
        <div class="header_main_inner">
          <div class="header_main_logo">
            <img src="./components/icons/logo.png" alt="">
          </div>
          <div class="header_main_search">
            <input type="search" placeholder="Поиск">
          </div>
          <div class="header_main_right">
            иконки
          </div>
        </div>
      </div>
    </div>
  </header>

  <nav>
    <div class="container">
      <div class="nav_inner">
        <div class="nav_menu">
          <div class="full_menu">
            Полное меню
          </div>
          <div class="menu_link">
            <a href="http://">Главная</a>
            <a href="http://">Каталог</a>
            <a href="http://">Специальные предложения</a>
            <a href="http://">Наши партнеры</a>
            <a href="http://">О нас</a>
          </div>
        </div>
        <div class="nav_contacts">
          <div class="nav_contacts_text">Контакты:</div>
          <div class="nav_contacts_phone">+7(999) 777-7778</div>
        </div>
      </div>
    </div>
  </nav>

  <main>
    
  </main>



</template>

<style scoped>
/* header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
} */
</style>
