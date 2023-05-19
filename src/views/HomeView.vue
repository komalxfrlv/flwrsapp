<template>
  <div class="home">
    <h1>Моя студия</h1>
    <div class="menu">
      <div>
        <div class="button slide">Забронировать</div>
      </div>
      <div>
        <div class="button slide">Расписание</div>
      </div>
      <div>
        <div class="button slide">Клиенты</div>
      </div>
      <div>
        <div class="button slide">Сотрудники</div>
      </div>
    </div>
    <div class="booking">
      <div>
        Состояние студии: <b>Свободна</b>
      </div>
      <div>
        Ближайшая бронь: <b>Kendrick Lamar</b>
      </div>
      <div>
        <i>(17:00 16.05.2023)</i>
      </div>
    </div>
  </div>
</template>
<style lang="scss">
.booking {
  margin-top: 70px;
  text-align: center;
}

.slide:hover,
.slide:focus {
  background-color: #329468;
}

.button {
  color: white;
  transition: 0.25s;
  background-color: #42b983;

  &:hover,
  &:focus {
    border-color: #329468;
    color: #fff;
  }
}

.button {
  border-radius: 10px;
  background: #42b983;
  border: 2px solid #42b983;
  font: inherit;
  line-height: 1;
  margin: 0.5em;
  padding: 1em 2em;
  font-size: 14pt;
}
</style>
