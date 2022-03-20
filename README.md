<p align="center"> 
<img src="/img/Back5.png" width="355" title=""><br>
  <!-- 355 X 110 px o logo --!>
<h2 align="center">Sistema de gerenciamento de ordens de serviço</h2>
</p>

<!--ts-->
   * [Funcionalidades](#Funcionalidades)
   * [Caracteristicas](#Caracteristicas)
<!--te-->


<p>Sou Pedro Emmanuel Riscado Machado Barreto e neste projeto irei desenvolver uma aplicaçao com o intuito de gerenciar e facilitar o cadastro de usuarios e ordens de serviços de uma empresa.</p>
<p>Focado em facilitar e agilizar a abertura e fechamento de uma Ordem de Serviço o aplicativo tera telas para cadastro de clientes, abertura e fechamnto de OS, cadastro de produtos. </p>

Esse sistema esta sendo desenvolvido em python, utilizando o framwork Django em sua versão 3.2.6 junto com outras bibliotecas listadas abaixo:

* Python 3.9
* Django 3.2.6
* Pillow 8.3.1
* asgiref 3.4.1
* certifi 2021.5.30         
* charset-normalizer 2.0.4
* Geocoding 1.4.3
* idna 3.2
* KdQuery 0.2.2
* mysqlclient 2.0.3
* numpy 1.21.2
* pytz 2021.1
* requests 2.26.0
* sortedcontainers 2.4.0                                           
* sqlparse 0.4.1
* Unidecode 1.2.0
* urllib3 1.26.6
* bootstrap 5.1

<p>Para banco de dados estou utilizando o Mysql-Server em sua versão 8.0.26.</p>

<h3 align="center">Analise Geral</h3>

<h4>Funcionalidades</h4>

* Cadastro de Clientes.
    <p>Consiste no cadastro dos dados essenciais dos clientes, tais como (CPF, RG, Endereço, Contato).</p>
* Cadastro de Produtos e Serviços.
    <p>Cadastro de produtos e serviços ofertados, com o intuito de facilitar o preenchimento e padronização da ordem de serviço.</p>
* Abertura de Ordem de Serviço.
    <p>Tela onde serao preenchido os dados do produto para reparo, problema relatado, previsao de entrega, diagnostico a ser executado, cliente, produto para reeparo, materias nescessarios, entre outros. Apos o preenchimento sera disponibilizada a opçao de impressao, que criara um documento referente aquela ordem de serviço para ser impresso e assinado pelo cliente, declarando ciencia do serviço e valores de orçamento. <p/>
* Fechamnto de Ordem de Serviço.
    <p>Essa etapa sera executada apos a finalizaçao do serviço executado, cadastrando na OS os problemas encrotados os reparos realizados, produtos ultilizados entre outros tanto quanto a data de termino e fechamento da ordem de serviço e criaçao de um documento de saida para ser assinado pelo cliente com os valores cobrados..</p>

    
    * Numero de clientes e quantidade de OS geradas .
    * Valores de Serviços E produtos com a possibilidade de ediçao e desconto sobre o valor total.
    * Gerenciamento de estoque e quantidade de produtos disponiveis ou em reserva.
    * Gerenciamento de OS abertas e sem conclusao. 

