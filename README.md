<!DOCTYPE html>
<html>
  <head>
    <title>Lista de Compras</title>
  </head>
  <body>
  <h1>Lista de Compras</h1>
  <button onclick="AdicionarProdutos()">
    Adicionar Produtos
  </button>
    <div id="lista"></div>/div>
    <script> 
    function AdicionarProdutos(){
    let produto=prompt("Digite o produto");
      let lista=
        document.getelementById("lista");
      lista.innerHTML +=produto+ "br";
          }
          </script>
  </body>
</html>
  
