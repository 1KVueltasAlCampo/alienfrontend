<template>
  <div id="wrapper">
    <section id="inputSection">
      <section id="titleSection">
        <label>Variables'</label>
        <label>values</label>
      </section>
      <section class="inputSection">
        <label>X</label>
        <input type="text" class="textInput" id="" />
      </section>

      <section class="inputSection">
        <label>Y</label>
        <input type="text" class="textInput" id="" />
      </section>
    </section>
    <section id="outputSection">
      <label>Charts</label>
    </section>
  </div>
</template>

<script>

</script>

<style scoped>
#titleSection label {
  margin-right: 23%;
}

.inputSection label {
  margin-right: 23%;
}

#wrapper{
  display: grid;
  grid-template-columns: 1fr 1fr;
}


</style>
