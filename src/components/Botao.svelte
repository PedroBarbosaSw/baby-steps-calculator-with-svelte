<script>
   export let texto
   export let triplo = false
   export let duplo = false
   export let operacao = false
   export let destaque = false
</script>

<button class="botao" 
   class:triplo class:duplo class:operacao class:destaque>
   {texto}
</button>

<style>
   .botao {
      margin: 0;
      border: 1px solid var(--cor-fundo);
      flex-basis: 25%;
   }

   .triplo {
      flex-basis: 75%;
   }

   .duplo {
      flex-basis: 50%;
   }

   .operacao {
      background: orange;
      color: white;
   }

   .destaque {
      background: red;
      color: white;
   }

</style>
