<template>
  <div id="app">
    <div class="card mb-3 border-0 " style="width: 600px">
      <div class="row g-0 justify-content-center">
        <div class="col-md-5">
          <img src="https://pm1.narvii.com/6963/1d4ca65ea5f648a8cb790ac45e91b708ae1b4e0br1-1536-2048v2_hq.jpg" class="img-fluid rounded-start" alt="..." />
        </div>
        <div class="col-md-7">
          <div class="card-body">
            <h1 class="card-title text-center">Login</h1>
            <form action="">
                <label for="">E-mail</label>
                <input class="form-control mt-2" type="text">
                <label for="">Senha</label>
                <input class="form-control mt-2" type="text">
            </form>
            <div class="d-flex text-center flex-column">
              <button class="btn p-3 mt-4 button-style">Entrar</button>
            </div>
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

.button-style {
  background-color: tomato !important; 
  color: white !important;
}



</style>