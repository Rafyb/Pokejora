<template>
  <div id="PokNav">
    <ul>
      <li><b>Pokejora</b></li>
      <li><router-link to="/">Accueil</router-link></li>
      <li><router-link to="/Pokedex">Pokédex</router-link></li>
      <li><router-link to="/Equipe">Mon Equipe</router-link></li>
      <li style="float:right;background-color: #c62828"><router-link to="/Projet">Projet</router-link></li>
    </ul>
  </div>
</template>

<script>

export default {
  name: 'PokNav',
}
</script>

<style>
#PokNav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

#PokNav li {
  float: left;
}

#PokNav li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

#PokNav li a:hover {
  background-color: #111;
}

b{
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  background-color: #c62828;
}
</style>