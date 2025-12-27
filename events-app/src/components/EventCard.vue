<template>
  <div class="event-card">
    <h4>{{ event.title }}</h4>
    <span>{{ event.date }} à {{ event.time }}</span>
  </div>
</template>

<script setup>
// Exercice 2.b: Données statiques initiales
const event = {
  time: '18:00',
  date: '2025-12-10',
  title: 'Soirée jeux de société',
}
</script>

<style scoped>
.event-card {
  padding: 20px;
  width: 250px;
  cursor: pointer;
  border: 1px solid #39495c;
  margin-bottom: 18px;
}
.event-card:hover {
  transform: scale(1.01);
  box-shadow: 0 3px 12px 0 rgba(0, 0, 0, 0.2);
}
</style>