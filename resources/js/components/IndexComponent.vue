<template>
  <div class="row justify-content-center">
      <div class="col-md-8">
          <div class="card card-default">
              <div class="card-header">Index Component</div>

              <div class="card-body">
                  Eu sou o Componente Index
              </div>
          </div>
      </div>
  </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Index Component mounted.')
        }
    }
</script>