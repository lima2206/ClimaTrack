# API 5º Semestre ADS 
# Kersys - ClimaTrack

<p align="center">
      <img src="Documentação/Img/Logo/logo-BuzzTech.png" alt="logo da Buzz Tech" width="200">
      <h2 align="center"> Buzz Tech</h2>

<br>

<hr>
<br>
<p align="center">
  <a href ="#desafio"> Desafio </a>  |   
  <a href ="#metodologia"> Metodologia </a>  |
  <a href ="#mvp"> MVP </a>  |
  <a href ="#sprint"> Sprints </a>  |
  <a href ="#backlog"> Backlog do Produto </a>  | 
  <a href ="#equipe"> Equipe </a> |
  <a href ="#prot"> Prototipo </a> |
  <a href ="#demo"> Demonstração </a> |

</p>

<br>

<h4 align="center">
 <a href="https://www.figma.com/"><img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/></a>
 <a href="https://firebase.google.com/"><img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=Firebase&logoColor=white"/></a>
 <a href="https://github.com/"><img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/></a>
 <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/></a>
 <a href="https://reactnative.dev/"><img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/></a>
 <a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/></a>
 <a href="https://fastapi.tiangolo.com/"><img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/></a>
 <a href="https://www.atlassian.com/software/jira"><img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white"/></a>
</h4>




<br>
<br>

> Status do Projeto: Concluido

<br>

## :medal_sports: Desafio <a id="desafio"></a>

Desenvolver um aplicativo para auxiliar os produtores rurais a acompanhar o histórico das variações das informações climáticas de uma determinada lavoura. O aplicativo deve permitir aos usuários cadastrar seus pontos e acompanhar via gráficos a variação da pluviometria e da temperatura a partir de uma data informada, até a data atual. 

Além disso, deve exibir dados consolidados de temperatura e pluviometria por ano ou mês, e emitir notificações e alertas em caso de situações críticas.

<br>

## 🚀 MVP <a id="mvp"></a>


O nosso Produto Mínimo Viável (MVP) abrange os seguintes recursos:
      
- Pesquisa de Localidade: Permite ao usuário realizar a busca de informações climáticas de uma localidade específica.
- Histórico Climático: Fornece dados históricos sobre temperatura e pluviosidade da localidade pesquisada.
- Salvar Localidade: O usuário pode salvar localidades pesquisadas para acesso rápido.
- Alarmes Climáticos: Gera notificações caso os níveis de temperatura ou pluviosidade da localidade atinjam valores alarmantes.
- Série Histórica de Dados: Exibe informações detalhadas do histórico climático da localidade pesquisada.


<br>

## 	:art: Protótipo do Programa <a id="prot"></a>

<br>

<div align="center">
<table>
  <tr>
    <td>
      <img src="Documentação/Img/Prototipo/SearchScreen - alta fidelidade.png" width="250" height="">
    </td>
    <td>
      <img src="Documentação/Img/Prototipo/ResultScreen - alta fidelidade.png" width="250" height="">
    </td>
    <td>
      <img src="Documentação/Img/Prototipo/MyAreas - alta fidelidade.png" width="250" height="">
    </td>
  </tr>
  <tr>
    <td>
      <img src="Documentação/Img/Prototipo/SavedLocation - alta fidelidade.png" width="250" height="">
    </td>
    <td>
      <img src="Documentação/Img/Prototipo/modals - alta fidelidade.png" width="250" height="">
    </td>
  </tr>
</table>

  
</div>

## 📽 Demonstração <a id="demo"></a>

[Vídeo de Demonstração - Sprint 1](https://www.youtube.com/watch?v=TnMFILxzt3g)

<br>


<br>

## 📅 Sprints <a id="sprint"></a>

🔖 SPRINT 1: Concluído! ✅

🔖 SPRINT 2: Concluido! ✅

🔖 SPRINT 3: Concluido! ✅

🔖 SPRINT 4: Concluido! ✅

<br>

## :books: Metodologia <a id="metodologia"></a>

O framework de Metodologia Ágil utilizado foi o Scrum, que possui os seguintes princípios norteadores:

1. Controle empírico
2. Auto-organização
3. Colaboração
4. Priorização da criação de valor
5. Time-boxing
6. Desenvolvimento iterativo

O projeto foi dividido em Sprints, onde priorizamos tarefas que trouxessem maior valor ao cliente. Utilizamos a construção de Personas para guiar nossas Histórias de Usuários e o Planning Poker para definir o tempo necessário para cada tarefa.

<br>

## 📋 Backlog do Produto <a id="backlog"></a>

| **Prioridade** | **ID**   | **História de Usuário**                         | **Descrição**                                                                                                    |
|----------------|----------|-------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| 1              | US001    | Pesquisa do Local                               | Eu, como usuário, quero pesquisar uma área para ter informações daquela ponto.|
| 2              | US003    | Exibição dos dados da Pluviosidade e Temperatura| Eu, como usuário, quero ver os dados de Pluviosidade e Temperatura a partir de uma data e depois escolher uma granularidade(ano, mês, dia) e para que consiga visualizar o histórico da pluviosidade da área, para poder escolher o melhor plantio para a área.|
| 3              | US002    | Salvar Local                                    | Eu, como usuário, quero salvar os locais de minhas plantações para que consiga acompanhar o estado de minhas plantações, se terá algum fator que causará problemas em minhas plantações.|
| 4              | US004    | Notificação de Alteração Climática Extrema      | Eu, como usuário, quero definir um parâmetro para temperaturas muito altas e muito baixas e de alta pluviosidade e baixa para uma área salva anteriormente.|
| 5              | US005    | Notificação de Alteração Climática Prolongada   | Eu, como usuário, quero definir um parâmetro para temperaturas muito altas e muito baixas e de alta pluviosidade e baixa para períodos prolongados para uma área salva anteriormente.|
| 6              | US006    | Marcar os locais para ficar disponíveis sem acesso à internet | Eu, como usuário, quero escolher os locais que quero deixar disponíveis os dados para acesso sem internet.|
| 7              | US007    | Atualizar os dados disponíveis sem acesso à internet, toda vez que houver conexão com a internet                 | Eu, como usuário, quero que o sistema atualize os dados disponíveis sem acesso à internet, sejam atualizados automaticamente quando houver conexão com internet. |

<br>

## :mortar_board: Equipe <a id="equipe"></a>

<div align="center">
  <table>
    <tr>
      <th>Membro</th>
      <th>Função</th>
      <th>Github</th>
      <th>Linkedin</th>
    </tr>
    <tr>
      <td>Isaque da Silva</td>
      <td>Product Owner</td>
      <td><a href="https://github.com/KhovetS2"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/isaque-elis-da-silva-2a4087226/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Nilber Siqueira</td>
      <td>Scrum Master</td>
      <td><a href="https://github.com/NilberSiqueira"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/nilber-siqueira-b3404a176"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Cauan Almeida</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/cauancesar"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/cauancesar-almeida/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Ivan Duarte</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/Ivan-Duarte"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/ivan-duarte-982532217"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Natanael Machado</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/NatanaelSM"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/natanael-machado-796841270"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Pedro Davi</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/PedrohDavi"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/pedro-davi-jobs/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Vitor Lima</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/lima2206"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/vitor-spricigo-lima-84a377184"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Rafael Motta</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/Rafael-Motta"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/rafaelmotta97"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
  </table>
</div>

<br>
