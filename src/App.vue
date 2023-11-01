<template>
<div class="badass-todo">

  <div class="title has-text-centered">
 tareas 
  </div>


  <div class="field is-grouped">
  <p class="control is-expanded">
    <input class="input" type="text" placeholder="add a todo">
  </p>
  <p class="control">
    <a class="button is-info">
      Add
    </a>
  </p>
</div>
</div>


</template>

<style>
@import 'bulma/css/bulma.min.css';

.badass-todo{
  position: relative;
  top: 20px;
  max-width: 500px;
  padding-left: 20px;
  margin: 0 auto;
}
</style>