<template>

    <!-- crecion de nuestro component prestamos -->

    <div class="prestamos">
        <div class="row">
         <div class="col-12 col-md-3">
            <label for="">titulo</label>
            <select class="custom-select custom-select-sm">
                <option selected>Open this select menu</option>
                <option value="1">One</option>
                <option value="2">Two</option>
                <option value="3">Three</option>
            </select>
        </div>  

        <div class="col-12 col-md-3">
            <label for="">titulo</label>
            
            <select class="custom-select">
                <option selected>Open this select menu</option>
                <option value="1">One</option>
                <option value="2">Two</option>
                <option value="3">Three</option>
            </select>
        </div>

        <div class="col-12 col-md-3">
            <label for="">titulo</label>
            
            <select class="custom-select">
                <option selected>Open this select menu</option>
                <option value="1">One</option>
                <option value="2">Two</option>
                <option value="3">Three</option>
            </select>
        </div>

        <div class="col-12 col-md-3">
            <label for="">titulo</label>
            
          <button>Solicitar</button>
        </div>
        </div>
      
    </div>
   
</template>

<script>


export default {
 
}

</script>

<style lang="scss">
@import 'node_modules/bootstrap/scss/bootstrap.scss';
.prestamos{
    width: 85%;
    margin: 0 auto;
    background: #fff;
    border-radius: 7px;
    position: relative;
    top: -88px;
    padding: 26px;
    box-shadow: 0 0 20px 3px #ccc;

}

   
</style>
