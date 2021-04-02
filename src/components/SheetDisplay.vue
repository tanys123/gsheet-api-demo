<template>
  <div>
    Hello world
  </div>
</template>

<script>
const GSheetReader = require('g-sheets-api');

export default {
  mounted() {
    this.load()
  },
  methods: {
    load: function () {
      const options = {
        sheetId: '1eabQ7flBgElDFilBO4ErkLPIb7LtokDATLF8EAUR6J8',
        sheetNumber: 1,
        returnAllResults: true
      }

      GSheetReader(
        options,
        results => {
          console.log(results)
        },
        error => {
          console.log(error)
        }
      );
    }
  }
}
</script>
