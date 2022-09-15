<script>
export default {
  data() {
    return {
      text: 'Edit me',
      checked: true,
      checkedNames: ['Miyazawa'],
      picked: 'One',
      selected: 'A',
      multiSelected: ['A']
    }
  }
}
</script>

<template>
  <h2>School Service Test</h2>
  <input v-model="text"> {{ text }}


  <h2>check!check!</h2>
  <input type="checkbox" id="Miyazawa" value="Miyazawa" v-model="checkedNames">
  <label for="miyazawa">Miyazawa</label>
  <input type="checkbox" id="Ziyuan" value="Ziyuan" v-model="checkedNames">
  <label for="ziyuan">Ziyuan</label>
  <input type="checkbox" id="SatoT" value="SatoT" v-model="checkedNames">
  <label for="sato">SatoT</label>
  <p>Checked names: <pre>{{ checkedNames }}</pre></p>

</template>