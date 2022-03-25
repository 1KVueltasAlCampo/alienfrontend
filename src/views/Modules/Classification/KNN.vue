<template>
  <div class ="wrapper">
    <section class = "wrapper" id="inputSection">
      <section id="titleSection">
        <label>Variables</label>
        <label>values</label>
      </section>
      <section class="inputs">
        <label>X</label>
        <input type="text" class="textInput" />
      </section>

      <section class="inputs">
        <label>Y</label>
        <input type="text" class="textInput" />
      </section>
    </section>
    <section id="outputSection">
      <input type="button" class="ml-5 btn btn-primary expand" value="Create charts"/>
    </section>
  </div>
</template>

<script>

</script>

<style scoped>

#titleSection label {
  margin-right: 23%;
}

.inputs{
  display: flex;
  gap: 25%;
}

.inputSection label {
  margin-right: 23%;
}

#wrapper{
  display: grid;
  grid-template-columns: 1fr 1fr;
}

.inputSection{
  display: grid;
  grid-template-columns: 1fr 1fr;
}

#outputSection{
 grid-column: 1fr;
}

.textInput{
  display: grid;
  grid-template-columns: 1fr;
}

</style>
