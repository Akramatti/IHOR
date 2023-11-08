<script lang="js">

</script>

<template>
  <div class="box">
    <ul class="nav nav-tabs">
      <li class="nav-item">
        <a class="nav-link active" aria-current="page" href="#">Flights</a>
      </li>
    </ul>
    <div class="box2">
      <div class="input-group">
        <span class="input-group-text">Where from? and Where to?</span>
        <input type="text" aria-label="Where from" class="form-control">
        <input type="text" aria-label="Where to" class="form-control">
      </div>
      <div class="input-group" style="margin-top: 10px;">
        <span class="input-group-text">Departure and Return</span>
        <input type="date" aria-label="Departure" class="form-control">
        <input type="date" aria-label="Return" class="form-control">
      </div>
    </div>
  </div>
</template>

<style scoped>
body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
}

.box {
  border-radius: 19px;
  width: 80%;
  margin-top: 100px;
  margin-bottom: 100px;
  border: 1px solid #ccc;
  padding: 50px;
  text-align: center;
  background: linear-gradient(to bottom right, #213E60, #dddbda);
}

.box2 {
  margin-bottom: 30px;
  border: 1px solid #ccc;
  padding: 20px;
  background-color: #ffffff;
  text-align: center;
}
</style>