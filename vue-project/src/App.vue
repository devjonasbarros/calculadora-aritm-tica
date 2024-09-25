// npm create vue@latest

<script setup>

var valor1, valor2;

</script>

<template>

  <h2>CALCULADORA ARITMETICA</h2>
  <br>
<input class="seuNome" v-model="nome" placeholder="Digite aqui por favor !" />
<p>Me fale o seu nome: {{ nome }}</p>


<input :type="Number" v-model="valor1" placeholder="Primeiro numero" > 
<input :type="Number" v-model="valor2" placeholder="Segundo numero" >

<p>ADIÇÃO</p>
<h1>{{ valor1 }} + {{ valor2 }}</h1>

<br>
<hr>

<p>SUBTRAÇÃO</p>
<h1>{{ valor1 }} - {{ valor2 }}</h1>

<br>
<hr>

<p>MULTIPLICAÇAO</p>
<h1>{{ valor1 }} * {{ valor2 }}</h1>

<br>
<hr>

<p>DIVISÃO</p>
<h1>{{ valor1 }} / {{ valor2 }}</h1>

<br>
<hr>



</template>

<style scoped>

input{

  width: 120px;
  height: 30px;


}

.seuNome{
  width: 300px;
  height: 30px;

  left: 30px;
}

</style>
