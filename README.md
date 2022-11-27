#Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE
 
Projeto-DIO

![image](../img/CienciaDadosUnimed.png)

<h3 align="center">Geração Tech Unimed-BH - Ciência de Dados - Bootcamp DIO</h3>

## Sobre 

O DIO Database Experience é um Bootcamp de banco de dados para profissionais que procuram uma experiência rápida em Ciência de Dados para se aprimorar nos principais conceitos de banco de dados SQL (MySQL) e NoSQL (MongoDB).

## Projeto - E-Commerce

A criação de um projeto conceitual, a partir de um modelo ERR, contemplando todas as entidades em seu processo.

As seguintes características devem ser utilizadas:
  
<b><i>Atributo Fornecedores</i></b> 
* Razão Social
* CNPJ
* Vendedores Tercerizados
  
<b><i>Atributo clientes</i></b> 
* o cliente pode se cadastrar no site com CPF ou CNPJ 
* O endereço irá determinar o valor do frete
* Um cliente pode comprar mais de um pedido. Este tem um período de arência para devolução do produto
* Cliente PJ e PF
* Pagamento

<b><i>Atributo Estoque e entrega</i></b> 
* Status
* Código de rastreio 
* Data máxima de entrega;
* Local
  
<b><i>Atributo pedidos</i></b> 
* Os Pedidos são Criados por clientes e possuem informações de compra, endereço e status da entrega
* Um produto ou mais compoem o pedido
* O pedido pode ser cancelado
  
<b><i>Atributo produtos</i></b> 
* São vendidos por uma unica plataforma online, contudo, estes podem ter vendedores distintos
* Cada produto possui apenas um fornecedor 
* Um pedido pode ser composto por um ou mais produtos.


### Projeto

![image](../img/e-commerce.png)
