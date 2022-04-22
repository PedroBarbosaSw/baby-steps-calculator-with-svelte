<script>
   export let valor;
</script>

<div class="tela">
   <span>{valor}</span>
</div>

<style>
   .tela {
      display: flex;
      flex: 1;
      justify-content: flex-end;
      align-items: center;
      padding: 0px 5px;
      font-size: 1.7rem;
      overflow: hidden;
      background-color: aliceblue;
      margin: 2px 1px;
      border-top-right-radius: 5px;
      border-top-left-radius: 5px;
   }
</style>