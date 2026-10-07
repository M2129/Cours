<script setup>
const nom = "Momo";
const role = "Etudiant";
const montant = 1000000000;
const annee = new Date().getFullYear();
const prime = 0.5;
const personne = { fullName: "Momo", role: "Etudiant", montant: 1000000000, annee: 2023, prime: "Prime de fin d'année" };

</script>


<template>
  <section>
    <div class="momo1">Nom: {{ personne.fullName }}</div>
  <div class="momo2">Role: {{ personne.role }}</div>
  <div class="momo3">Montant: {{ montant.toLocaleString() }}</div>
  <div class="momo4">Annee: {{ annee }}</div>
  <div class="momo1">Salaire Net: {{ montant + montant * prime }}</div>
  </section>
</template>




<style scoped>
.momo1 {
  background-color: #f00;
  color: #fff;
  padding: 10px;
  border-radius: 5px;
}
.momo2 {
  background-color: #0f0;
  color: #fff;
  padding: 10px;
  border-radius: 5px;
}
.momo3 {
  background-color: #00f;
  color: #fff;
  padding: 10px;
  border-radius: 5px;
}
.momo4 {
  background-color: #ff0;
  color: #000;
  padding: 10px;
  border-radius: 5px;
}

</style>