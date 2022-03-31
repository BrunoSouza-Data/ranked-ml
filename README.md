# Ranked ML

Repositório destinado à criação de um modelo de Machine Learning com os dados da GC. A finalidade deste projeto é levar o conhecimento de Data Science e Analytics para o maior número de pessoas possível.

As lives são realizadas na Twitch no canal [Téo Me Why](https://www.twitch.tv/teomewhy) às Terças e Quintas - 9:00AM.

## Sumário
- [Sobre o Curso](#sobre-o-curso)
- [Sobre o Professor](#sobre-o-professor)
- [Sobre os Dados](#sobre-os-dados)
- [Setup e requisitos](#setup-e-requisitos)
- [Etapas](#etapas)
- [FAQ](#faq)

## Sobre o curso

Algumas oportunidades que teremos de soluções para a GC:

1. Predição de jogadores que jogarão na próxima/mês
2. Predição de churn
3. Predição de assinatura
4. Predição churn de assinatura

Mas antes de debruçar no algoritmo, precisamos preparar os dados. Assim, passaremos pela criação de um book de variáveis (feature store) e posteriormente criar a nossa variável resposta (target).

Pretendemos realizar este curso para apresentar como um algoritmo por ajudar a resolver problemas reais de negócio. Bem como, passar pelas dificuldades e preparação de dados para desenvolver uma solução end-to-end.

## Sobre o professor

Téo é Bacharel em Estatística e tem Pós Graduação em Data Science & Big Data.É bastante curioso em aprender novas tecnologias e aprimorar seus projetos voltados à Análise de Dados e Modelagem Preditiva.

Tem atuado desde 2014 em grandes empresas, sempre utilizando técnicas Estatísticas e Computacionais para empregar Aprendizado de Máquina em diferentes cenários. Com isso, entende que a principal etapa no ciclo analítico consiste em consultas de dados em bancos relacionais. Além de realizar suas lives na Twitch desde 08.2019.

Hoje, como Head of Data na Gamers Club, gostaria de contribuir ainda mais para a comunidade trazendo dados reais e aplicações com SQL.

Você pode conhecer mais sobre o professor no [LinkedIn](https://www.linkedin.com/in/teocalvo/).

## Sobre os dados

Para este curso utilizaremos dados de partidas que ocorreram nos servidores da Gamres Club. São aprtidas referentes à 2.500 jogadores, havendo mais de 30 estatísticas de seus partidas. Tais como Abates, Assistências, Mortes, Flash Assist, Head Shot, etc.

Alem disso, temos informações de medalhas destes players, como:
- Assinatura Premium, Plus
- Medalhas da Comunidade

Para ter uma melhor descrição destes dados, confira na [página oficial do Kaggle](https://www.kaggle.com/gamersclub/brazilian-csgo-plataform-dataset-by-gamers-club) onde os dados foram disponibilizados.

Abaixo temos o schema (relacionamentos) dos nossos dados.

<img src="https://user-images.githubusercontent.com/4283625/157664295-45b60786-92a4-478d-a044-478cdc6261d7.jpg" alt="" width="500">

## Setup e requisitos

### 1. Visual Studio Code

Para acompanhar este curso você precisará instalar o [Visual Studio Code](https://code.visualstudio.com/). Basta realizar o download na [página oficial](https://code.visualstudio.com/) da ferramenta e seguir os passos de instalação.

### 2. Dados

Como vamos utilizar os dados da GC, você precisa baixar estes dados de nossa pasta no [google drive](https://drive.google.com/file/d/1TfGfhwm7tnfaQnAKDNSEezggYemDxdUR/view?usp=sharing).

### 3. Conhecimentos técnicos

Temos como objetivo  ajudar pessoas que estão descobrindo o mundo de dados agora. Como é um curso de Data Science end-to-end, é recomendado que se saiba os conceitos de SQL e familiaridade com Python. Para facilitar o acompanhamento, preparamos um curso de [SQL aqui](https://github.com/TeoCalvo/sql_gc).

## Etapas

|Descrição|VOD|
|---|:---:|
| 1. Introdução **Machine Learning** | |
| 2. Criação do book de Variáveis | |
| 3. Criação da ABT (*Analytical Base Table*) | |
| 4. SEMMA e primeiros Algoritmos | |
| 5. Tunning do melhor modelo | |
| 6. Deploy | |

## FAQ

1. É grátis?

Sim, as lives serão abertas e sem a necessidade de pagamento.

2. Precisa se cadastrar?

Não, é só abrir a live no horário da transmissão.

3. Vai ficar gravado?

Sim! Os inscritos no canal da Twitch terão acesso à todos os VODs gerados a parti das lives. Para ser inscrito, basta ter Amazon Prime e assinar nosso canal de forma gratuita ou realizando o pagamento na própria plataforma.

4. Vai para o YouTube?

Não! Queremos prestigiar nossos apoiadores do projeto. Assim, apenas os assinantes da Twitch terão acesso ao conteúdo gravado.

5. Como posso apoiar?

Sua inscrição no canal da Twitch já apoia muito o nosso trabalho. Esta seria uma ótima forma de contribuir.
Alem da ajuda financeira, sinta-se a vontade para abrir `issues` no nosso repositório para melhorias no projeto.

6. Posso usar este material em um curso?

Este material é aberto e pode ser utilizado por outras iniciativas gratuitas na comunidade. É importante que se faça as devidas referências ao utilizar este projeto. **Não se deve utilizar este conteúdo para fins comerciais.**
