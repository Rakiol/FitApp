<script setup>
  import { gymHealthFacts} from "../../utils/index.js";
  console.log(gymHealthFacts)
  const randomNumber = Math.round(Math.random() * 256);
</script>

<template>
  <section id="dashboard">
    <div class="card tip-container">
      <h2>Welcome Smoldier</h2>
      <div>
        <p class="tip"><strong>Daily Tip</strong><br/> INJECT THE TIP</p>
      </div>
    </div>
  </section>
</template>

<style scoped>

</style>
