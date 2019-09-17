<template>
  <div class="col-sm-6 col-md-4 col-lg-3">
    <div class="div panel panel-default">
      <div class="panel-body quote">
        <slot></slot>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.panel-body {
  font-family: 'Azizona', cursive;
  font-size: 24px;
  color: #6e6e6e;
}
.quote {
  cursor: pointer;
}
.quote:hover {
  background-color: #ffe2e2;
}
</style>
