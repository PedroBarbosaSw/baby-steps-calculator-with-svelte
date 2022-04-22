<script>
   import Botao from './Botao.svelte';
   import Linha from './Linha.svelte';
   import Tela from './Tela.svelte';
</script>

<div class="calculadora">
   <Tela valor="123" />
   <Linha>
      <Botao texto="AC"  destaque />
      <Botao texto="/" operacao />
   </Linha>
   <Linha>
      <Botao texto="7" />
      <Botao texto="8" />
      <Botao texto="9" />
      <Botao texto="*" operacao />
   </Linha>
   <Linha>
      <Botao texto="4" />
      <Botao texto="5" />
      <Botao texto="6" />
      <Botao texto="+" operacao />
   </Linha>
   <Linha>
      <Botao texto="1" />
      <Botao texto="2" />
      <Botao texto="3" />
      <Botao texto="-" operacao />
   </Linha>
   <Linha>
      <Botao texto="0" />
      <Botao texto="," />
      <Botao texto="=" destaque duplo />
   </Linha>
</div>

<style>
   .calculadora {
      background-color: var(--cor-fundo);
      height: 220px;
      width: 150px;
      padding: 10px;
      border-radius: 10px; 

      display: flex;
      flex-direction: column;
   }
</style>