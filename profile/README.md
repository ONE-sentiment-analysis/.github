![banner](https://raw.githubusercontent.com/ONE-sentiment-analysis/.github/refs/heads/main/profile/resources/img/banner.jpeg)

# ONE-sentiment-analysis

### Sobre
Projeto desenvolvido para o **[Hackaton da ORACLE ONE](https://www.oracle.com/br/education/oracle-next-education/)**. Esta aplicação, construída com Java Spring Boot, Python e Streamlit, tem como objetivo realizar analise de sentimento em textos fornecidos por um usuario.

### O que é este projeto
Imagine que uma empresa recebe milhares de comentários de clientes todos os dias. Ler um por um para saber se o cliente está feliz ou insatisfeito é impossível.

Este sistema é uma solução inteligente que automatiza esse trabalho. Ele atua como um "cérebro" que lê os textos, entende a emoção por trás deles e classifica instantaneamente se o comentário é Positivo, Negativo ou Neutro.

## O que ele faz por você?

### 1. Análise Instantânea

Você envia uma frase ou comentário (como "Adorei o produto!") e o sistema responde na hora qual é o sentimento e com qual nível de certeza (probabilidade).

### 2. Processamento em Massa (Lote)

Tem uma planilha com 10.000 avaliações de produtos? Sem problemas.

* Você envia o arquivo com todos os comentários.
* O sistema processa tudo automaticamente.
* Ele devolve um relatório organizado (em Excel ou CSV) com todas as análises prontas.

### 3. Segurança Total

Sabemos que dados de clientes são sensíveis. Por isso, o sistema conta com:

* **Cadastro seguro:** Apenas pessoas autorizadas podem entrar.
* **Proteção de dados:** As senhas e informações são criptografadas (codificadas) para garantir privacidade total.

## Por que é inovador?

Este projeto não é apenas um "leitor de texto". Ele conecta uma interface segura e robusta a um modelo avançado de Inteligência Artificial.

* **Resiliente:** Se a Inteligência Artificial demorar para responder, o sistema não trava; ele sabe lidar com instabilidades para que você nunca perca seu trabalho.
* **Organizado:** Mantém um histórico de tudo o que foi analisado.


### O nosso projeto

#####  O "Gerente do Restaurante"

Imagine este software como um restaurante de alta gastronomia:

1. **O Cliente (Você):** Faz o pedido (envia o texto).
2. **O Garçom (API Java):** Recebe o pedido, verifica se você tem cadastro e organiza a solicitação. Ele não cozinha, mas garante que tudo flua bem.
3. **O Chef Especialista (API Python):** É quem realmente coloca a mão na massa. Ele fica na cozinha (isolado) e é o único que sabe "provar" o prato e dizer se o sentimento é doce (positivo) ou amargo (negativo).

TL:DR -> Criar uma API simples que recebe textos (comentários, avaliações ou tweets), aplica um modelo de Data Science para classificar o sentimento (Atrasado / Pontual → neste caso: Positivo / Neutro / Negativo ou binário Positivo / Negativo) e retorna o resultado em formato JSON, permitindo que aplicações consumam essa predição automaticamente.

Para mais detalhes acesse a pagina do projeto:
* [Requerimentos do projeto](docs/projeto.md)

### Tecnologias utilizadas

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Debian](https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![Neovim](https://img.shields.io/badge/NeoVim-%2357A143.svg?&style=for-the-badge&logo=neovim&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)


### Como desenvolvemos este projeto

Primeiro criamos uma "organização" no github (esta conta), para poder organizar a nossa equipe e melhorar o workflow colaborativo além de centralizar todos os repositórios criados em um lugar.

A nossa equipe está divida entre dois grupos distintos de desenvolvimento, sendo elas a equipe focada ao Back-end e a equipe focada a Data Science.

A equipe de back-end se dedicou a desenvolver a API back-end ue vai servir a nossa solução ao cliente, desenvolvendo um projeto com Java Spring-Boot seguindo todos os padroes de projetos recomenddados.

A equipe de Data Science se dedicou a coleta, tratamento e limpeza dos dados iniciais, utilizando este dados para formar um dataset para ser utilizado em treinamendo de um modelo de predicao por aprendizado de maquina. Ao todo foram treinados 3 modelos diferentes utilizando algotitmos distintos, sendo eles o Logistc Regression, que é o nosso modelo recomendado, o Naive Bayes e Random Forest.

### Onde encontrar o projeto
Ao todo o projeto esta distruibuido em 3 repositorios:

Front-end: [https://github.com/ONE-sentiment-analysis/BIA_frontend_python](https://github.com/ONE-sentiment-analysis/BIA_frontend_python)

Back-end Java: [https://github.com/ONE-sentiment-analysis/Back-end-structure-sentiment-analisys](https://github.com/ONE-sentiment-analysis/Back-end-structure-sentiment-analisys)

Back-end Python: [https://github.com/ONE-sentiment-analysis/One_sentiment_analysis_model](https://github.com/ONE-sentiment-analysis/One_sentiment_analysis_model)


### A nossa equipe 404-feelings-not-found

Andrey Nagatani|Caian Matos Garibaldi Pires|Cauan Henrique Sanches Araujo
:---:|:---:|:---:
![andrey](https://raw.githubusercontent.com/ONE-sentiment-analysis/.github/refs/heads/main/profile/resources/avatar/01_120.jpeg)|![caian](https://raw.githubusercontent.com/ONE-sentiment-analysis/.github/refs/heads/main/profile/resources/avatar/02_120.jpeg)|![cauan](https://raw.githubusercontent.com/ONE-sentiment-analysis/.github/refs/heads/main/profile/resources/avatar/03_120.jpeg)
![Static Badge](https://img.shields.io/badge/Github-Github?style=for-the-badge&logo=github&logoColor=white&logoSize=auto&link=https%3A%2F%2Fgithub.com%2Finatagan)|![Static Badge](https://img.shields.io/badge/Github-Github?style=for-the-badge&logo=github&logoColor=white&logoSize=auto&link=https%3A%2F%2Fgithub.com%2Fcaianmatos)|![Static Badge](https://img.shields.io/badge/Github-Github?style=for-the-badge&logo=github&logoColor=white&logoSize=auto&link=https%3A%2F%2Fgithub.com%2FCauan77)
![Static Badge](https://img.shields.io/badge/LinkedIn-LinkedIn?style=for-the-badge&logo=linkedin&logoColor=white&logoSize=auto&color=blue&link=www.linkedin.com%2Fin%2Fandrey-nagatani)|![Static Badge](https://img.shields.io/badge/LinkedIn-LinkedIn?style=for-the-badge&logo=linkedin&logoColor=white&logoSize=auto&color=blue&link=https%3A%2F%2Fwww.linkedin.com%2Fin%2Fcaian-matos%2F)|![Static Badge](https://img.shields.io/badge/LinkedIn-LinkedIn?style=for-the-badge&logo=linkedin&logoColor=white&logoSize=auto&color=blue&link=https%3A%2F%2Fwww.linkedin.com%2Fin%2Fcauan-henrique%2F)|

Giovanna  Felicio|Pablo Lima|Sergio de Oliveira Burlamaqui Junior
:---:|:---:|:---:
![giovana](https://raw.githubusercontent.com/ONE-sentiment-analysis/.github/refs/heads/main/profile/resources/avatar/04_120.jpeg)|![pablo](https://raw.githubusercontent.com/ONE-sentiment-analysis/.github/refs/heads/main/profile/resources/avatar/05_120.jpeg)|![sergio](https://raw.githubusercontent.com/ONE-sentiment-analysis/.github/refs/heads/main/profile/resources/avatar/06_120.jpeg)
![Static Badge](https://img.shields.io/badge/Github-Github?style=for-the-badge&logo=github&logoColor=white&logoSize=auto&link=https%3A%2F%2Fgithub.com%2FImgih)|![Static Badge](https://img.shields.io/badge/Github-Github?style=for-the-badge&logo=github&logoColor=white&logoSize=auto&link=https%3A%2F%2Fgithub.com%2Fstevopablo)|![Static Badge](https://img.shields.io/badge/Github-Github?style=for-the-badge&logo=github&logoColor=white&logoSize=auto&link=https%3A%2F%2Fgithub.com%2FSergioBurlamaK)
![Static Badge](https://img.shields.io/badge/LinkedIn-LinkedIn?style=for-the-badge&logo=linkedin&logoColor=white&logoSize=auto&color=blue&link=https%3A%2F%2Fwww.linkedin.com%2Fin%2Fgiovanna-felicio-78152a278%2F)|![Static Badge](https://img.shields.io/badge/LinkedIn-LinkedIn?style=for-the-badge&logo=linkedin&logoColor=white&logoSize=auto&color=blue)|![Static Badge](https://img.shields.io/badge/LinkedIn-LinkedIn?style=for-the-badge&logo=linkedin&logoColor=white&logoSize=auto&color=blue&link=https%3A%2F%2Fwww.linkedin.com%2Fin%2Fsergioburlamaqui%2F)
