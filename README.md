Tabela de produtos (
idprodutos int  not null auto_increment chave primária ,
nome varchar ( 12 ) não nulo ,
preco tinyint,
quantidade varchar ( 12 ) não nula
);

inserir em (nome, preco, quantidade de produtos)
valores ( ' feijao ' , 4 , ' 2,3Kg ' ),
	  ( ' melancia ' , 5 , ' 1 Unidade ' ),
      ( ' melao ' , 12 , ' 1,5 Litros ' ),
      ( ' Açaí ' , 5 , ' 1 Litros ' ),
      ( ' castanha ' , 6 , ' 1,5Kg ' ),
      ( ' laranja ' , 3 , ' 1Kg ' ),

excluir  dos produtos
onde idprodutos =  ' 3 ' ;

atualizar produtos
set idprodutos =  ' 12 '
onde idprodutos =  ' 5 ' ;

atualizar os produtos
set nome =  ' feijao '
onde idprodutos =  ' 4 ' ;

selecione  *  dos produtos;
