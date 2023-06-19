<h1 align="center"> Terceiro Semestre - API </h1>
<p align="center">
  <a href ="#sobre-o-projeto"> Sobre o projeto  </a>  • 
  <a href ="#telas"> Telas </a>  • 
  <a href ="#requisitos"> Requisitos </a>  • 
  <a href ="#tecnologias-utilizadas"> Tecnologias Utilizadas </a>  •
  <a href ="#contribuições-pessoais"> Contribuições Pessoais </a>  
</p>

<br>



## Sobre o projeto 

<div align="justify">
No terceiro semestre tivemos uma empresa parceira especializada no controle de contas (água, energia e gás) para terceiros.
<br><br>
Nosso objetivo era criar um sistema que ajudasse essa empresa a realizar a coletada e digitação de todos campos para, posteriormente, salvar em seu banco de dados para eventuais consultas e análises técnicas/financeiras desejassem.
<br><br>
As cores foram escolhidas para remeter a logo da empresa e gerar confiabilidade aos usuários. Um designer bem pensado para combinar com o foco do projeto. O Website que foi desenvolvido também é intuitivo para os colaboradores que o utilizarão.
<br><br>
O cliente gostou bastante da entrega. Entregamos com excelência tudo que nos foi proposto e usamos bem as tecnologias solicitadas. Uma entrega realizada com êxito!

<br><br>

## Telas


<!-- Inicial -->
 <details>
  <summary>
  <h4 align="left">Tela Inicial com Login</h4>  
  </summary>
    Optamos pela escolha do layout da <b> Tela Inicial </b> com 2 colunas para proporcionar uma melhor experiência ao usuário. A coluna principal contém uma imagem de destaque que representa o propósito da plataforma e a segunda coluna possui o campo de login para que apenas usuários autentificados tenham acesso aos recursos disponíveis. 
    <br> <br>
    Essa medida de segurança é necessária para garantir a privacidade dos dados dos usuários e oferecer uma navegação mais confiável e eficiente. Além disso, desenvolvemos um website intuitivo para facilitar a utilização da plataforma desde a primeira interação.
    
  </details>
  
<!-- Tabela de Contas -->
  <details>
  <summary>
   <h4 align="left">Tabela de Contas</h4>  
  </summary>
  
A <b>Tabela de Contas</b> lista todas as contas coletadas pela empresa (água, energia e fás) e permite filtragem, busca e exportação dos dados. Uma vez que o usuário encontra a conta desejada, é possível acessar todas as informações digitadas no momento da coleta, como nome do cliente, endereço, consumo de energia, água ou gás, entre outras informações. <br> <br>
Para tornar a página de Tabela de Contas mais interativa e atraente, optamos por utilizar uma interface visual intuitiva e de fácil navegação. Utilizamos elementos gráficos como cores, ícones e botões para destacar as funcionalidades da página e facilitar a compreensão dos usuários.
  
  </details>

<!-- Dashboard -->  
 <details>
  <summary>
   <h4 align="left">Dashboard</h4>  
  </summary>
  
A página <b> Dashboard </b>  é uma das páginas mais importantes da plataforma e apresenta informações de maneira visual e interativa. Utilizamos cores vibrantes e recursos gráficos para destacar as informações relevantes e proporcionar uma experiência mais agradável e intuitiva para os usuários.

Ao clicar em uma unidade específica, a plataforma apresenta informações detalhadas sobre o consumo e despesas do contrato com a concessionária, além de alertas automáticos em caso de consumo elevado. Além disso, é possível gerar relatórios em PDF com os dados exibidos na página, tornando a análise mais ágil e prática.
  
  </details> 

<!-- Cadastro -->

 <details> 
  <summary>
   <h4 align="left">Cadastro </h4>  
  </summary>
 
A tela de <b> Cadastro </b> temos alguns formulários que foram desenvolvidos com uma interface clara e objetiva, afim de facilitar o preenchimento dos dados e garantindo a integridade das informações. Temos nessa página diferentes opções de formulários para cadastrar contas, concessionárias, unidades e contratos, que são organizados de forma intuitiva e prática para facilitar a navegação.
<br><br>
É a partir desse cadastro que definimos as rotas de cada perfil. Nosso login explicado acima possui autentificação e cada usuário só terá acesso as telas necessárias para seu trabalho, seja ele Digitador - quem escreverá as contas - Gestor - quem as aprovará - ou Administrador - quem tem controle de tudo na plataforma.

 </details>

   
<!-- Histórico  -->
 <details>
  <summary>
   <h4 align="left">Histórico</h4>  
  </summary>
  
Na tela <b> Histórico </b> é possível encontrar informações detalhadas sobre quais dados de cadastro foram adicionados, alterados ou excluídos, juntamente com o nome do usuário responsável e a data em que a ação foi realizada. Essa funcionalidade garante maior transparência e controle sobre as operações realizadas no sistema, permitindo uma melhor análise e rastreamento de qualquer alteração ou atualização feita no banco de dados.
  
  </details>

<!-- Perfis  -->
<details>
  <summary>
   <h4 align="left">Perfis</h4>  
  </summary>
  
A página de <b> Perfis </b> é onde os administradores da plataforma podem gerenciar os usuários e suas permissões de acesso. É possível visualizar, cadastrar, editar e excluir usuários. Através dessa página, é possível definir qual usuário será um digitador, responsável por inserir as contas, um gestor, que irá aprovar as contas ou um administrador, com acesso total à plataforma. A página também possui uma opção para redefinir as senhas dos usuários, caso necessário. Tudo isso é feito de forma intuitiva e fácil de usar, para garantir um bom gerenciamento dos usuários e permissões.
  
  </details>



  </details>

  <div width="100%">
    <div width="50%" align="left" margin-left="1px"><img src="../gifs/terceiroSemestre_1.gif" width="49%" align="left"></div>
    <div width="50%" align="right" margin-left="1px" ><img src="../gifs/terceiroSemestre_2.gif"  width="49%" align="right"></div>
  </div>


<br> <br> <br> <br> <br> <br> <br> <br>  <br> <br> <br> <br>
> Gif da execução completa.

<br>

## Requisitos 

**Funcionais:**<br>
✔️ Cadastros de Unidades, Concessionárias, Contratos; <br>
✔️ Cadastro do usuário e seus perfis (administrador, gestor e digitador); <br>
✔️ Cadastro (digitação) da conta de água, energia e gás; <br>
✔️ Registro de log de operações (cadastro e deleção); <br>
✔️ Relatório de consumo total de água mensal, anual e média; <br>
✔️ Geração de alertas de consumo acima da média (a média pode ser definida no cadastro do contrato).

<br>

**Não Funcionais**<br>
✔️ Prezar pelo UX da tela de digitação das contas; <br>
✔️ Incluir atalhos no teclado; <br>
✔️ Permitir navegação entre campos por TAB ou seta.
<br>
> O repositório oficial do projeto pode ser acessado [aqui](https://github.com/NewInoDevs/NewInoDevs).

<br>

## Tecnologias Utilizadas
Ao longo do projeto, trabalhamos com as seguintes ferramentas:
<br>
   <h4 align="left">Reuniões e Apresentações</h4> 
   
  - **Discord:** Utilizamos para armazenar informações importantes e trabalhar em reuniões; <br> 
  - **WhatsApp:** Para troca de mensagens rápidas e avisos; <br> 
  - **Microsoft Teams:** Para as reuniões com o cliente e visualização da documentação dos requisitos.
 
   <h4 align="left">Data-base</h4>  
 
   - **MySQL:** Utilizamos em nosso Banco de Dados para armazenar e alterar os dados. 

   <h4 align="left">Back-end </h4>  
  
  - **Java:** Utilizamos para manipular o Banco de Dados;
  - **Spring:** Utilizamos para facilitar o desenvolvimento da aplicação
  
   <h4 align="left">Front-end </h4>  
 
  - **HTML5:** Para marcar nosso layout e importar os componentes do website; 
  - **CSS3:** Para estilizar nosso site;
  - **JavaScript:** Utilizamos para criar animações em nosso Website;
  - **Bootstrap:** Utilizamos para facilitar a criação do frontend.
  
   <h4 align="left">Outros</h4>  
 
  - **Github:** Nosso repositório, onde trabalhamos com o controle de versão;
  - **Visual Studio Code:** Nossa IDE para o desenvolvimento;
  - **Figma:** Para criação do protótipo navegável;
  - **Photoshop:** Para edição das imagens.
<br>

## Contribuições Pessoais
<div align="justify">
Neste projeto fui <b>Product Owner</b>. Compreendi a necessidade do cliente e repassei ao time. Além disso, minha função envolveu a definição e gerenciamento das user stories e do backlog, bem como a compreensão clara do MVP (Minimum Viable Product) de cada entrega. Trabalhei próxima ao time de desenvolvimento para garantir que o trabalho estivesse sempre alinhado com as necessidades do cliente e as prioridades do projeto. Cuidei também para que o cliente estivesse ciente de quaisquer mudanças ou ajustes necessários, a fim de garantir a transparência e a confiança em nosso trabalho
<div>

## Hard Skills
- **Conceitos aplicados de UX Designer:** Sei fazer com autonomia;<br>
- **Habilidade em gerenciamento de backlog:** Sei fazer com autonomia;<br>
- **Criação de Wireframe com Figma:** Sei fazer com autonomia; <br>
- **Habilidade de gerenciar o escopo do projeto:** Sei fazer com autonomia; <br>
- **Utilização do MySQL como Banco de Dados:** Sei fazer com auxílio de consultas; <br>
- **Manipulação de entradas com Java:** Sei fazer com auxílio de consultas;<br>
- **Dominio de HTML5:** Sei fazer com autonomia; <br>
- **Dominio de CSS3:** Sei fazer com autonomia; <br>
- **Edição de imagens com Canva:** Sei fazer com autonomia. 

## Soft Skills
 - **Comunicação eficaz:** Comuniquei-me de forma clara e assertiva com o time e o cliente - exerci bem meu papel de PO; <br>
 - **Planejamento:** Gerenciei bem o backlog do produto e a expectativa em nosso produto; <br>
 - **Organização:** Entreguei todas as minhas tarefas de maneira bem organizada e clara; <br>
 - **Produtividade:** Tive a iniciativa em nossas tarefas - como a criação da modelagem do banco de dados e estruturação do protótipo no Figma. <br>
