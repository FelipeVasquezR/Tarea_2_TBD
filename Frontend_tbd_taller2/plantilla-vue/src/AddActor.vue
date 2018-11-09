<template>
  <div class="center">
    <h2>{{title}}</h2>

      <p>
        <label for="firstName">Nombre</label>
        <input type="text" id="firstName" name="firstName" required v-model="actor.firstName" onClick="this.select();" >
      </p>
      <p>
        <label for="lastName">Apellido</label>
        <input type="text" id="lastName" name="lastName" required v-model="actor.lastName" onClick="this.select();" >
      </p>
      <p><button v-on:click="addActor()">Agregar Actor</button></p>



  </div>
</template>

<script>
  export default {
    data(){
      return{
        title:'Añadir un actor',
        actor:{firstName:'',lastName:''}
      }
    },
    methods:{
      addActor:function(){
        if (firstName.value == 0 && lastName.value == 0){
          alert("Debe rellenar los campos");
        }
        else if (firstName.value == 0){
          alert("El campo nombre no puede quedar vacío");
        }
        else if (lastName.value == 0){
          alert("El campo apellido no puede quedar vacío");
        }
        else{
              this.$http.post('http://localhost:3305/actors', this.actor);
              alert("Añadido exitosamente");
          }
        }
      }
    }
</script>