<template>
  <div>
    <h1 class="title">
      Главная страница
    </h1>
    <p>Приложение работает в режиме SSR</p>
    <p>Страница about доступна только в случае наличия у пользователя токена.  Чтобы получить токен - залогиньтесь на странице login с любым username</p>
    <p>Страница users генерируется на основе json c сервера jsonplaceholder и рендерится на сервере. Список юзеров сохраняется в store</p>
    <p>Страница user содержит данные пользователя. Данные пользователей берутся из store. Рендерится на сервере. На странице подключен валидатор, который ограничивает параметр роутера id цифрой не более 10</p>
    <p>Страница login доступна только если вы не залогинены, и использует пустой layout</p>
    <p>На страницe Elements-UI песочница с элементами интерфейса из Elements-UI </p>
  </div>
</template>

<script>

export default {

};
</script>
