<p align="center"> 
<img src="/img/Back.png" width="350" title=""><br>
  <!-- 355 X 110 px o logo --!>
<h2 align="center">Sistema para documentação de redes de internet FTTH</h2>
</p>

<!--ts-->
   * [Funcionalidades](#Funcionalidades)
   * [Caracteristicas](#Caracteristicas)
<!--te-->


<p>Me chamo Raphael Maia sou aluno do 4° periodo do curso de Analise e Desenvolvimento de Sistemas na universidade Candido Mendes - Campos dos Goytacazes - RJ. Para meu trabalho de conclusão de curso escolhi desenvolver o Software Fibermap.</p>
<p>Com intuito de sanar a dificuldade em obter sistemas voltado para a area de mapeamento e documentação de redes FTTH (Ópticas), senti a vontade de criar esse sistema para atender algumas areas na empresa em que hoje trabalho, trata-se de uma empresa do ramo de Telecomunicações, mais especificamente um provedor de internetl, temos hoje redes ópticas e UTP em 4 municipios no estado do Rio de Janeiro</p>

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

<h3 align="center">Principais caracteristicas e funcionalidades</h3>

<h4>Funcionalidades</h4>

* Cadastro de Usuários.
    <p>Consiste no cadastro de usuários do sistemas podendo esses serem técnicos, projetistas, engenheiros, vendedores e equipe de marketing.</p>
* Cadastramento de Ativos.
    <p>Consiste em um cadastro centralizado onde todos os equipamentos utilizado na rede estarão registrados de forma organizada, contento suas principais caractristicas.</p>
* Cadastro de Clientes.
    <p>Consiste no cadastros de todos os clientes ativos e inativos da empresa, e suas respectivas coordenadas geograficas, tornando assim mais facil a manutenção futura assim como controle de portas livres por caixas de atendimento. Esse cadastro podera ser feito de forma manual, ou automatizada atravéz de integração via API do Fibermap com o sistema ERP da empresa contratando do Fibermap.<p/>
* Cadastro de Fusões.
    <p>Essa é uma area primordial do sistema pois através dela que temos o controle e documentação da rede de fato, nessa área estará registradas todas as caixas de emendas da rede (CEO), contendo suas coordenadas geograficas, tipos de cabo, destino dos cabos e fusões em si, com isso conseguiremos mostrar em tela para o cliente uma visão explodida da caixa de emenda (CEO), e tornar cada vez mais fácil a manutenção em campo da rede.</p>
* Emissão de relatórios em diversos formatos.
    <p>Nessa área o cliente poderá emitir diversos relatórios que o ajudara nas tomadas de decisões na empresa. Como exemplo de alguns relatórios dou maior destaque a esses quatro que são eles:</p>
    
    * Numero de clientes inativos e ativos.
    * Numero de portas livres em toda a rede e por áreas especificas.
    * Valor total de todo o iventário ou seja toda a rede do provedor.
    * Area com maior potencial de venda. 

<h4>Caracteristicas</h4>

* Multiplataforma.
    <p>O sistema deverá ser acessado atravez de multiplas plataformas, dentre elas o mobile. Deverá ser disponibilizado uma versão mobile (App) onde o técnico em campo fara interações ao sistema, dentre elas consultar Fusoes existentes, e cadastrar novas caso seja necessário, também devera conseguir atribuir em qual porta cada cliente esta conectado na sua respectiva CTO, tambem irá conseguir atravez do GPS do smartphone atualizar coordenadas de todos os objetos cadastrados no sistema</p>
* Segurança.
    <p>Por conter toda a rede da empresa o sistema deverá ser seguro quanto aos dados, impedindo que pessoas não autorizadas visualize os mesmos, assim como deverar gerar log de toda alteração feita por cada usuario.</p>
* Responsividade.
    <p>Deverá ser responsivo, adaptando assim em qualquer formato de tela, e com isso facilitando a usabilidade ao sistema.</p>
* Simples e eficaz.
    <p>Devera ser simples e ao mesmo tempo eficáz, tornando fácil a usabilidade, contendo informações claras e precisas de toda a rede.</p>

<h3 align="center">Funcionalidades em novas releases</h3>

* Integração com OLT.
    <p>Fara integração aos principais fabricantes de OLT.</p>
* Provisionamento de ONU.
    <p>O técnico atravez do seu Smartphone conseguira na residencia do cliente fazer a autorização da ONU assim como a atribuição de vlan e com isso aumentar a agilidade no momento da instalação, sem a necessidade de depender de terceiros</p>
* Gerenciamento de equipamentos.
    <p>Atrávez do protocolo TR-069 nativo na maioria dos equipamentos atuais, os técnicos atravéz do seu Smartphone, vai conseguir gerenciar e fazer toda a configuração no roteador do cliente</p>
* Roteadores Inteligentes.
    <p>Ainda atravez do protocolo TR-069 o sistema devera fazer integração ao servidor ACS (Auto Configuration Server), permitindo assim atravéz de uma interface gráfica de simples entendimento, conter todos os dados do roteador do cliente junto ao seu cadastro no sistema, com isso facilitara a reconfiguração de forma automática caso o equipamento na casa do cliente seja resetado.</p>
* Controle de comodato.
    <p>Como todos os equipamentos que estão na residencia do cliente vão estar registrados no Fibermap, será facil ter controle de equipamentos em comodato</p>
