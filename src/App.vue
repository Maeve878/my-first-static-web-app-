<template>
  <div>Hello {{ value }}</div>
  <h2>出席チェック</h2>
  <input type="checkbox" id="jack" value="Jack" v-model="checkedNames">
  <label for="jack">Miyazawa</label>
  <input type="checkbox" id="john" value="John" v-model="checkedNames">
  <label for="john">Ziyuan</label>
  <input type="checkbox" id="mike" value="Mike" v-model="checkedNames">
  <label for="mike">SatoT</label>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "School Service Test!!!!!!!"
    };
  }
};
</script>
