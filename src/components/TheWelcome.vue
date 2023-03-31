<template>
  <div class="center">
    <img alt="Juan Escutia" src="../assets/juan-escutia2.jpeg">
    <div class="row">
      <div class="column">
          <h1>Nombre Completo</h1>
          <p>Juan Escutia</p>
      </div>
      <div class="column">
          <h1>Matrícula</h1>
          <p>A01361234</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
          <h1>Correo Institucional</h1>
          <p>A01361234@tec.mx</p>
      </div>
      <div class="column">
          <h1>Carrera</h1>
          <p>ISC</p>
      </div>
      <div class="row">
        <div class="column">
          <h1>Correo Institucional</h1>
          <p>muriporlapatria@gmail.com</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
h1 {
  color: #384ffe;
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
img {
  border-radius: 50%;
}
.float-container {
    padding: 20px;
}
.column {
  float: left;
  width: 50%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
p {
  font-size: 24px;
}
.center {
  margin: auto;
  width: 80%;
  padding: 10px;
  text-align: center;
}
</style>
