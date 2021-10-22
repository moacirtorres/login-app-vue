<template>
  <div id="app">
    <div class="card mb-3 " style="max-width: 540px">
      <div class="row g-0 justify-content-center">
        <div class="col-md-4">
          <img src="https://picsum.photos/200/300" class="img-fluid rounded-start" alt="..." />
        </div>
        <div class="col-md-8">
          <div class="card-body">
            <h1 class="card-title text-center">LOGIN</h1>
            <form action="">
                <label for="">E-mail</label>
                <input class="form-control" type="text">
                <label for="">Senha</label>
                <input class="form-control" type="text">
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>



<script>
import "bootstrap";

export default {};
</script>


<style>

#app {
    background-color: red;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background: rgb(240,3,3);
    background: linear-gradient(90deg, rgba(240,3,3,1) 14%, rgba(247,129,9,1) 96%);
}



</style>