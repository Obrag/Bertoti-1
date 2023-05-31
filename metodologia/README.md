# Alan Araujo Rodrigues

## Introdução
Seja bem vindo ao meu portifólio acadêmico. Aqui estarão listados todos os meus projetos durante minha formação em Banco de dados. 

# Projeto 3: Terceiro semestre

### Empresa parceira  

<p align="center">
    <b>IACIT soluções tecnológicas S.A.</b> 
    <img src="https://github.com/alantrs/Bertoti/blob/ce55d69f624ba22495bcf76f626bb86899750763/metodologia/Imagens/Iacit.png" alt="Logo da IACIT soluções tecnológicas">
</p>


## Descrição do projeto

Foi proposto um desafio para desenvolver um sistema capaz de importar dados meteorológicos de arquivos CSV disponibilizados pela empresa, armazená-los em uma base de dados e gerar relatórios solicitados pelos clientes da empresa IACIT. A aplicação web é capaz filtrar os registros por regiões, estados, estações, tipo de dado e ranges de datas, além de exibir as informações em formato de gráficos e cards. Por fim, é possível obter relatórios com base na pesquisa realizada.

 - `Requisitos funcionais exigidos:` Cadastro de estações, cadastro de estados e regiões, importação de dados e geração de relatórios.
 - `Requisitos não funcionais exigidos:` Sistema Web, linguagem java, banco de dados relacional e documentações.
 
 ## Tecnologias utilizadas
 
### Java
 
A linguagem Java foi utilizada para desenvolver todo o back-end da aplicação, utilizando o framework Spring Boot. O Spring Boot é uma estrutura que permite aos desenvolvedores criar rapidamente aplicativos web em Java, fornecendo um conjunto de ferramentas e bibliotecas que tornam a construção de aplicativos mais rápida e fácil.

### PostgreSQL

O banco de dados PostgreSQL foi utilizado para armazenar os dados meteorológicos que foram importados a partir dos arquivos CSVs, que foram disponibilizados pela empresa. PostgreSQL é um sistema de gerenciamento de banco de dados relacional de código aberto que é amplamente utilizado em aplicações empresariais e científicas, devido à sua confiabilidade, escalabilidade e recursos avançados. Além disso, o PostgreSQL é compatível com muitas linguagens de programação, incluindo Java, que foi usada neste projeto. Isso significa que os dados podem ser facilmente acessados e manipulados por meio do back-end da aplicação, permitindo que a equipe de desenvolvimento crie consultas complexas para gerar os relatórios solicitados pelos clientes da empresa IACIT.


###HTML, CSS e Javascript

As linguagens de marcação HTML e CSS foram utilizadas em conjunto com a linguagem de programação JavaScript para criar a interface gráfica da aplicação. O HTML é a base da estrutura da página web, enquanto o CSS é responsável por definir o estilo visual e a aparência da página. O JavaScript é utilizado para adicionar interatividade à página, permitindo que o usuário realize ações e que os dados sejam exibidos e atualizados dinamicamente.
Com o uso do HTML, CSS e JavaScript, foi possível criar uma interface amigável e intuitiva para os usuários da aplicação, permitindo que eles possam visualizar os dados meteorológicos e gerar relatórios de forma fácil e eficiente. Além disso, utilizamos uma biblioteca do javascript chamada Charts, perfeita para disponibilizar os dados em forma de gráficos.

## Contribuições pessoais

Fui o administrador do banco de dados da equipe em conjunto com a função de Scrum master. Como DBA desenvolvi desde a modelagem de dados até a criação da base de dados completa. Como scrum master fui responsável por garantir que o processo Scrum estivesse sendo seguido corretamente e que a equipe estivesse funcionando de maneira eficaz e produtiva.

<br>
<details>
  <summary>Algumas das minhas contribuições como Administrador de banco de dados:</summary>
  <br>
  <ul>
    <details>
      <summary>Modelagem do banco de dados.</summary>
      <br>
      <img src="https://github.com/alantrs/Bertoti/blob/e19d9567debe132ef4387b306ba9451d048716cf/metodologia/Imagens/modelagem_img1.jpeg" alt="Modelagem do banco de dados">
    </details>
   <details>
      <summary>Implementação física do banco de dados (criar as tabelas, definir as colunas, os tipos de dados, as chaves primárias, as chaves estrangeiras e as restrições necessárias para cada tabela).</summary>
      <br>
      <img src="https://github.com/alantrs/Bertoti/blob/9ea504d93f38be6eb8a90e052fb204119d34ae62/metodologia/Imagens/Cadastro.png" alt="script cadastro">
    <img src="https://github.com/alantrs/Bertoti/blob/9ea504d93f38be6eb8a90e052fb204119d34ae62/metodologia/Imagens/Dados.png" alt="Script dados">
   </details>
   <details>
  <summary style="background-color: lightgray; padding: 5px;">Gerar backup.</summary>
    <br>
  <p style="margin-left: 20px;">
    <code>pg_dump -U postgres -d iacit -F p -f "C:backup_iacit.sql"</code>
  </p>
</details>

 </ul>
</details>

<details>
  <summary>Algumas das minhas contribuições como Master:</summary>
 <br>
 <ul>
    <li>Garantir que a equipe esteja seguindo os princípios do Scrum e entendendo seus papéis e responsabilidades.</li>
    <li>Organizar e facilitar as reuniões do Scrum</li>
    <li>Ajudar a equipe a criar e manter o Backlog do Produto, garantindo que esteja atualizado e priorizado corretamente.</li>
    <li>Remover impedimentos que possam impedir a equipe de concluir as tarefas necessárias para atingir os objetivos do Sprint.</li>
    <li>Monitorar o progresso da equipe e garantir que ela esteja cumprindo os prazos e entregando os itens do Backlog do Produto dentro do prazo.</li>
    <li>Fornecer feedback regular aos membros da equipe e ajudá-los a melhorar continuamente o seu processo de trabalho.</li>
    <li>Garantir uma comunicação eficaz entre todos os membros da equipe, incluindo o Product Owner, os desenvolvedores e outras partes interessadas.</li>
    <li>Promover um ambiente de trabalho positivo e colaborativo para a equipe.</li>
  </ul>
</details>


## Aprendizados efetivos

Como DBA, adquiri conhecimentos em modelagem de dados, arquitetura do SGBD PostgreSQL, e aprofundei meus conhecimentos em SQL incluindo comandos DDL, DML e DCL. Como Scrum Master, desenvolvi habilidades valiosas em liderança, facilitação do processo Scrum, remoção de impedimentos, comunicação, feedback e melhoria contínua.

<details>
  <summary>Modelagem de dados</summary>
  <ul>
    <li>Estrutura do banco, distribuição das tabelas</li>
    <li>Evitar redundâncias</li>
  </ul>
 </details>
<details>
  <summary>SQL</summary>
  <ul>
    <li>DDL (Data Definition Language)</li>
    <li>DML (Data Manipulation Language)</li>
    <li>DCL (Data Control Language)</li>
  </ul>
 </details>
 <details>
  <summary>Administração do PostgreSQL</summary>
  <ul>
    <li>Política de backup</li>
    <li>Criação de usuário</li>
  </ul>
 </details>

<details>
  <summary>Domínio do processo Scrum</summary>
  <ul>
    <li>Compreensão dos princípios e papéis do Scrum.</li>
   <li>Remoção de impedimentos</li>
   <li>Comunicação e colaboração</li>
   <li>Feedback e melhoria contínua</li>
   <li>Habilidades de liderança e organização</li>
  </ul>
 </details>




 
 
 
 
 
 



