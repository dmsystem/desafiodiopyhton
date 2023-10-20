<a name="readme-top"></a>
<div align="center">
  
  [![Contributors][contributors-shield]][contributors-url]
  [![Forks][forks-shield]][forks-url]
  [![Stargazers][stars-shield]][stars-url]
  [![Issues][issues-shield]][issues-url]
  [![MIT License][license-shield]][license-url]
  [![LinkedIn][linkedin-shield]][linkedin-url]

</div>
<br />
<div align="center">
  <a href="https://github.com/dmsystem/desafiodiopyhton">
    <img src="img/etl-sdw2023-logo.png" alt="Logo" width="200" height="182">
  </a>
  <h3 align="center">etl-sdw2023</h3>
  <p align="center">
    An ETL pipeline for the Santander Dev Week 2023 database.
    <br />
    <a href="https://github.com/dmsystem/desafiodiopyhton"><strong>Explore the documentation »</strong></a>
    <br />
    <br />
      ·
    <a href="https://github.com/dmsystem/desafiodiopyhton/issues">Report a Bug</a>
    ·
    <a href="https://github.com/dmsystem/desafiodiopyhton/issues">Request a Feature</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About the Project</a>
      <ul>
        <li><a href="#technologies-used">Technologies Used</a></li>
      </ul>
    </li>
    <li><a href="#features">Features</a></li>
    <li><a href="#getting-started">Getting started</a></li>
    <li><a href="#to-do">To Do</a></li>
    <li><a href="#reporting-bugs">Reporting Bugs</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

## About the project

Este projeto foi desenvolvido como parte das iniciativas da Santander Dev Week 2023 e visa a implementação de um pipeline ETL eficaz para personalizar mensagens de marketing para clientes do Santander usando IA generativa. Utilizando dados dos clientes e a API do Google Bard, nosso objetivo é gerar mensagens que não apenas capturam a essência das necessidades e comportamentos financeiros individuais, mas também enfatizam a importância de tomar decisões de investimento informadas.

Abaixo é um exemplo de output:

> **Resposta baseada em regras:**                                                     
>                                                                                 
> Olá Devweekerson,                                                               
> Iniciar o investimento com um orçamento apertado é um desafio, mas não          
> impossível.                                                                     
> Com seu limite de cartão mais elevado, você tem a liberdade de explorar uma     
> variedade de investimentos.Investir é a chave para multiplicar seu dinheiro.    
> Não deixe sua grana parada! Vamos investir?                                     
>                                                                                
> **Mensagem do Bard:**                                                               
>                                                                                                                             
> Olá Devweekerson,                                                           
>                                                                                 
> Vi que você tem um saldo de R$ 624,12 e um limite de crédito de R$ 2.000,00.  
> Isso é um bom começo, mas você pode fazer mais para melhorar sua situação       
> financeira.                                                                     
>                                                                                 
> Os investimentos são uma ótima forma de fazer seu dinheiro crescer. Eles      
> podem ajudá-lo a alcançar seus objetivos financeiros, como comprar uma casa,    
> viajar ou se aposentar.                                                         
>                                                                                 
> Existem muitos tipos de investimentos diferentes, por isso é importante fazer 
> sua pesquisa e encontrar o que é certo para você. Eu posso ajudá-lo com isso.   
>                                                                                 
> Entre em contato comigo para agendar uma consulta.                            
>                                                                                 
> Atenciosamente,                                                               
> Banqueiro expert 

O fluxo de trabalho é composto por várias etapas de ETL (Extração, Transformação e Carregamento), incluindo:

1. Extração de dados dos clientes a partir de uma API
2. Geração de mensagens personalizadas usando IA Generativa
3. Exibição dessas mensagens de uma forma que seja tanto atraente quanto informativa

A implementação é feita em Python, utilizando várias bibliotecas e APIs para realizar as tarefas necessárias.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Technologies Used

The project uses the following technologies:

- Python
- Pandas
- Requests
- Google Bard API
- Santander Dev Week 2023 API (Swagger UI)

It's one of the projects of the **Santander Bootcamp 2023 - Data Science with Python**.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Features

This project includes the following features:

- Extração de IDs de usuários de uma planilha CSV
- Geração de mensagens de marketing personalizadas usando IA Generativa (Google Bard)
- Exibição dessas mensagens de forma atraente e informativa
- Possibilidade de integração com outros APIs através do requests

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting started

1. Clone this repository to your machine:

   ```bash
   git clone https://github.com/dmsystem/desafiodiopyhton.git

   ```

2. You can open [this link](https://github.com/dmsystem/desafiodiopyhton/blob/main/Personaliza%C3%A7%C3%A3o_de_Engajamento_de_Clientes_no_Santander_usando_IA_Generativa.ipynb) to see results too.
   
2. Or [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dmsystem/desafiodiopyhton/blob/main/Personaliza%C3%A7%C3%A3o_de_Engajamento_de_Clientes_no_Santander_usando_IA_Generativa.ipynb) and add the `SDW2023.csv` file ([in here](https://github.com/dmsystem/desafiodiopyhton/blob/main/SDW2023.csv))

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## To do

- [ ] Integração com outras APIs de IA
- [ ] Melhorias na interface do usuário

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Reporting bugs

Found a bug or issue in the project? Follow the steps below:

1. Check if the bug has already been reported in our "Issues" section on GitHub: link to Issues.

2. If you don't find an existing report about the bug, click on "New Issue" to open a new bug report.

3. Provide a clear and descriptive title for the bug, along with a detailed description of the steps needed to reproduce it.

4. If possible, include screenshots, relevant code snippets, or any other information that may help identify and resolve the bug.

5. Click on "Submit Issue" to create the bug report.

Thank you for reporting bugs! If you would like to contribute with code, you can open a PR, and your participation is more than welcome.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

This project is licensed under the [MIT License](/LICENSE).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[contributors-shield]: https://img.shields.io/github/contributors/dmsystem/desafiodiopyhton.svg?style=for-the-badge
[contributors-url]: https://github.com/dmsystem/desafiodiopyhton/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/dmsystem/desafiodiopyhton.svg?style=for-the-badge
[forks-url]: https://github.com/dmsystem/desafiodiopyhton/network/members
[stars-shield]: https://img.shields.io/github/stars/dmsystem/desafiodiopyhton.svg?style=for-the-badge

[issues-shield]: https://img.shields.io/github/issues/dmsystem/desafiodiopyhton.svg?style=for-the-badge
[issues-url]: https://github.com/dmsystem/desafiodiopyhton/issues
[license-shield]: https://img.shields.io/github/license/dmsystem/desafiodiopyhton.svg?style=for-the-badge
[license-url]: https://github.com/dmsystem/desafiodiopyhton/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/decio-morais
