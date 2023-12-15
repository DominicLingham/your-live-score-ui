<script setup>
import Step from "./Step.vue";
const name = "test";
</script>

<template>
  <Step heading="1. Team Details🏆">
    <template #step-form>
      <label for="team-name">Your team name</label>
      <input
        type="text"
        name="team-name"
        id="team-name"
        placeholder="Your team name"
      />
      <label for="team-color-one">Team colour 1</label>
      <input type="color" id="team-color-one" />
      <label for="team-color-two">Team colour 2</label>
      <input type="color" id="team-color-two" />
    </template>
  </Step>
  <Step heading="2. Match Details🏟️">
    <template #step-form>
      <label for="opposition-team-name">Opposition Team Name</label>
      <input type="text" id="opposition-team-name" />
      <label for="">Match Date</label>
      <input type="date" />
      <label for="kick-off-time">K.O Time</label>
      <input type="time" id="kick-off-time" />
      <label for="match-location">Location</label>
      <input type="type" name="address" id="match-location" />
    </template>
  </Step>
  <Step heading="3. Your Lineup👕">
    <template #step-form>
      <label for="player-number">Number</label>
      <input type="number" id="player-number" />
      <label for="player-initial">Initial</label>
      <input type="text" id="player-initial" />
      <label for="player-surname">Surname</label>
      <input type="text" id="player-surname" />
    </template>
  </Step>
  <button>Back</button>
  <button>Next</button>
</template>

<style scoped></style>
