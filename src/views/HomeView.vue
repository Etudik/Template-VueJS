<template>
  <div class="installation-success">
    <div class="success-icon">
      <i class="fas fa-check-circle"></i>
    </div>
    <h1 class="success-heading">Installation réussie !</h1>
    <p class="success-message">Félicitations, l'installation de votre projet Vue.js s'est déroulée sans problème.</p>

    <div class="next-steps">
      <h2 class="next-steps-heading">Module installé :</h2>
      <ul class="next-steps-list">
        <li><span class="emoji">🚀</span> GSAP <span class="emoji-validated"> ✅</span></li>
      <li><span class="emoji">📡</span> AXIOS <span class="emoji-validated"> ✅</span></li>
      <li><span class="emoji">🔐</span> MD5 <span class="emoji-validated"> ✅</span></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'InstallationSuccess',
  components: {},
}
</script>

<style scoped>
.installation-success {
  text-align: center;
  margin-top: 20px;
  background-color: #87CEEB; /* Light Blue background color */
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
  font-family: Arial, sans-serif; /* Change font family */
}

.success-icon {
  color: #34d058;
  font-size: 64px; /* Increase font size */
}

.success-heading {
  font-size: 32px; /* Increase font size */
  margin-top: 10px;
  color: #333;
}

.success-message {
  font-size: 24px; /* Increase font size */
  margin-top: 20px;
  color: #333;
}

.next-steps-heading {
  font-size: 28px; /* Increase font size */
  margin-top: 20px;
  color: #333;
}
.next-steps-list {
  list-style-type: none; /* Supprimez les puces de la liste */
  padding: 0; /* Réinitialisez la marge et le rembourrage */
  text-align: center; /* Centrez horizontalement les éléments de la liste */
}

/* Style pour les éléments <li> *//* Utilisez flex pour centrer les éléments horizontalement */
.next-steps-list li {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 10px 0; /* Ajoutez de l'espace entre chaque élément de la liste */
}


/* Style pour les éléments <span> contenant les emojis */
  .emoji {
  font-size: 20px; /* Taille de la police pour les emojis */
  margin-right: 5px;
}
</style>
