<h1 align="center"> Sexto Semestre - API </h1>
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
No sexto semestre, nossa parceria foi com uma empresa que atua no desenvolvimento de produtos e sistemas aplicados à tecnologia.
<br><br>
Nosso objetivo foi desenvolver uma aplicação para otimizar o processo de recrutamento e seleção de candidatos em empresas. Através de login e autenticação de múltiplos fatores, juntamente com a inserção da descrição do cargo, a aplicação coletava dados de nossa própria base. Com base nas CHA (Competências, Habilidades e Atitudes) de cada posição, os candidatos eram classificados de acordo com sua adequação ao perfil do cargo. Além disso, as empresas eram notificadas no momento do envio da solicitação e no recebimento dos resultados.
<br><br>
A abordagem adotada permitiu uma identificação mais precisa das correspondências entre as Competências, Habilidades e Atitudes (CHA) necessárias para cada posição e os candidatos disponíveis. Isso resultou em uma significativa redução de custos e em uma experiência mais eficaz para todos os envolvidos. 
<br><br>

## Telas

Todas as telas abaixo foram desenvolvidas para o website.

<!-- Autenticação -->
<details>
  <summary>
    <h4 align="left">Tela de Login com autentificaçãoo</h4>  
  </summary>
A tela de <b>Login com autentificação</b> é o ponto de entrada para os usuários, onde a empresa fornece suas credenciais, incluindo endereço de e-mail e senha. A autenticação de dois fatores fez-se necessária para garantir um acesso seguro às funcionalidades da aplicação. Esta camada adicional de segurança é realizada por meio de um e-mail previamente cadastrado pela empresa, reforçando a proteção das informações.

</details>
<!-- Cadastro de Empresa -->
<details>
  <summary>
    <h4 align="left">Cadastro de Empresa</h4>  
  </summary>
A opção de <b>Cadastro de Empresa</b> na tela inicial permite que novas empresas se registrem no sistema. Ao selecionar esta opção, os usuários são redirecionados para um formulário detalhado, onde podem preencher as informações necessárias para criar uma conta. Isso simplifica o processo de entrada no sistema e oferece às empresas acesso rápido às funcionalidades oferecidas.

</details>
<!-- Listagem das Vagas -->
<details>
  <summary>
    <h4 align="left">Listagem das Vagas</h4>  
  </summary>
Após o login, a <b>Listagem das Vagas</b> é acessível, fornecendo à empresa uma visão geral das oportunidades cadastradas. Nesta página, as empresas podem editar detalhes das vagas e visualizar o ranqueamento atualizado dos candidatos. A interface intuitiva facilita a gestão eficiente das informações relacionadas às oportunidades de emprego.

</details>
<!-- Ranqueamento de Candidatos -->
<details>
  <summary>
    <h4 align="left">Tela de Ranqueamento dos Candidatos</h4>  
  </summary>
Ao clicar no ícone de visualização, os usuários podem acessar a tela de <b>Ranqueamento dos Candidatos</b>. Esta funcionalidade apresenta os oito melhores candidatos para uma vaga específica, junto com a porcentagem de correspondência. Essa abordagem fornece insights rápidos sobre a adequação dos candidatos para a vaga em questão.

</details>
<!-- Cadastro da Vaga (CHA) -->
<details>
  <summary>
    <h4 align="left">Tela de Cadastro da nova Vaga</h4>  
  </summary>
Na tela de <b>Tela de Cadastro da nova Vaga</b>, os usuários podem criar novas oportunidades, inserindo um nome e um nível. A inteligência artificial gera automaticamente uma descrição da vaga com base nos Conhecimentos, Habilidades e Atitudes (CHA). Essa descrição pode ser ajustada posteriormente, proporcionando flexibilidade. Após salvar os dados, os usuários podem solicitar correspondência de candidatos, onde um Web Scrapping seleciona os perfis mais adequados.

</details>
<!-- Perfil -->
<details>
  <summary>
    <h4 align="left">Tela de Perfil</h4>  
  </summary>
A página de <b>Perfil</b> permite que as empresas visualizem e editem suas informações cadastradas. Além disso, oferece a opção de redefinir a senha, proporcionando flexibilidade na gestão da conta.

</details>
<!-- Redefinição de Senha -->
<details>
  <summary>
    <h4 align="left">Redefinição de Senha</h4>  
  </summary>
Além da opção de redefinir a senha na página de <b>Perfil</b>, é possível realizar esse procedimento diretamente na tela de login. Isso proporciona uma solução conveniente para os usuários que esqueceram suas senhas.

</details>
<!-- Notificações -->
<details>
  <summary>
    <h4 align="left">Notificações</h4>  
  </summary>
Quando a empresa gera uma descrição CHA ou realiza um match, <b>Notificações</b> são enviadas por e-mail. Além disso, existe uma página de notificações dentro do site que permite às empresas acompanharem informações relevantes de maneira centralizada.

</details>

  </details>

  <div width="100%">
    <img src="../gifs/sextoSemestre.gif" width="720" height="420" align="left">
  </div>


<br> <br> <br> <br> <br> <br> <br> <br>  <br> <br> <br> <br>  <br> <br> <br> <br>  <br>
> Gif da execução completa.

<br>

## Requisitos 

**Funcionais:**<br>
✔️ Registro e Autenticação;<br>
✔️ Registro de Empresa;<br>
✔️ Inserção de Descrição de Cargo;<br>
✔️ Notificação de Compreensão;<br>
✔️ Web Scraping;<br>
✔️ Notificação de Resultados;<br>
✔️ Apresentação de Resultados;<br>
✔️ Base de CHA.<br>
<br>

**Não Funcionais:**<br>
✔️ Desempenho;<br>
✔️ Segurança;<br>
✔️ Escalabilidade;<br>
✔️ Compatibilidade;<br>
✔️ Resiliência;<br>
✔️ Privacidade.<br>
<br>
> O repositório oficial do projeto pode ser acessado [aqui](https://github.com/inodevs-5/Reportify_Doc).

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
   
   - **Java: ** Nossa linguagem de programação para contrução do Back-End; <br>
   - **Spring:** Utilizamos esse framework de Java para manipulação do banco; <br>
   - **Python:** Utlizamos como nossa Linguagem de programação para contrução da inteligência artificial; <br>
   - **Django:** Utlizamos em nosso projeto esse framework de Python para ser nosso servidor de acesso à inteligência artificial. <br>
  
   <h4 align="left">Front-end </h4>  
   
  - **TypeScript:** Nossa linguagem de programação para desenvolvimento de interações da aplicação web;
  - **Vue.js:** Nosso framework de JavaScript para desenvolvimento de interfaces gráficas.
  
   <h4 align="left">Outros</h4>  
 
  - **Github:** Nosso repositório, onde trabalhamos com o controle de versão;
  - **Visual Studio Code:** Nossa IDE para o desenvolvimento;
  - **Figma:** Para criação do protótipo navegável;
  - **Photoshop:** Para edição das imagens.
<br>

## Contribuições Pessoais
<div align="justify">
Neste projeto, desempenhei o papel de <b>Desenvolvedora</b>, contribuindo com a integração da inteligência artificial em nossa aplicação. Minhas responsabilidades incluíram a edição e manipulação do banco de dados, assim como as notificações do site para a aplicação e para o e-mail. Além disso, busquei compreender as necessidades e desafios dos nossos clientes para desenvolver uma solução que atendesse de maneira eficaz às suas expectativas.
<div>


## Hard Skills
- **Conceitos aplicados de UX Designer:** Sei fazer com autonomia;<br>
- **Habilidade em gerenciamento de backlog:** Sei fazer com autonomia;<br>
- **TypeScript:** Sei fazer com auxílio de consultas;<br>
- **React Native:** Sei fazer com auxílio de consultas;<br>
- **CSS3:** Sei fazer com autonomia;<br>
- **React:** Sei fazer com auxílio de consultas;<br>
- **NodeJS:** Sei fazer com auxílio de consultas; <br>
- **MongoDB:** Sei fazer com auxílio de consultas; <br>
- **Criação de Wireframe com Figma:** Sei fazer com autonomia; <br>
- **Habilidade de gerenciar o escopo do projeto:** Sei fazer com autonomia. <br>

## Soft Skills
 - **Comunicação eficaz:** Comuniquei-me de forma clara e assertiva com o time dev, o PO e o cliente; - exerci bem meu papel de PO; <br>
 - **Planejamento:** Como Master organizei bem o backlog e as tasks do time por sprint; <br>
 - **Criatividade:** Desenvolvimento o pensamento criativo nas telas que criei e também na forma como solucionei os desafios que apareceram.<br>
