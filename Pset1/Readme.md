# **PSET 1 - Design e Desenvolvimento de Banco de Dados I**

## **Professor: Abrantes Araujo Silva Filho**

## **Aluno: Caio Victor Cassimiro Ribeiro**

Este arquivo servirá como forma de documentação de cada etapa do desenvolvimento do projeto.

### Pré-requisitos e conceitos à serem aprendidos e objetivos do trabalho da disciplina:

* Adquirir primeiramente conhecimento e compreensão da importância dos **Sistemas de Controles de Versões** e o por quê de utilizá-los.

* Aprender sobre as ferramentas **Git** e **Github**, como funcionam, como criar um repositório para hospedar arquivos e disponibilizá-los publicamente, exercitar as técnicas de versionamento para treiná-las.

* **GitHub Flavored Markdown**. Aprender sobre o uso da linguagem de formatação de texto utilizados em aplicações como o próprio **Github**.

* Desenvolver as habilidades de detecção de erros a partir de um modelo de Banco de Dados já projetado.

* Criação de Modelos de Bancos de Dados através da ferramenta **SQL Power Architect**.

* Produzir *Scripts* que são responsáveis por efetuar a criação de tabelas, relacionamentos, inserção de dados nos SGBDs **PostgreSQL** e o **MariaDB/MySQL**.


>A área abaixo do documento será destinada ao detalhamento de minha compreensão de cada aplicação ou conhecimento utilizado no desenvolvimento do trabalho.


## GIT

Esta aplicação se trata de um Sistema de Versionamento. É indispensável para que você tenha a segurança e praticidade, caso precise reverter alguma alteração específica realizada em seu projeto, ou queira apenas avaliar a evolução de cada versão do mesmo. Estudando mais profundamente sobre como esta aplicação opera, é possível identificar o motivo do sistema ter vários "backups" dos arquivos de um repositório específico. Além dos documentos utilizados na elaboração do projeto estarem armazenados de forma dinâmica em servidores, os mesmos também se encontram nas máquinas que contribuem para a colaboração do projeto. Dessa forma, caso algum servidor seja afetado, os arquivos serão facilmente repostos por estarem armazenados de forma descentralizada, resultando também em uma rápida resposta de processamento ao realizar os **COMMITS**.

## GITHUB

O Github, se trata de um aplicação que é utilizada, em conjunto com o GIT, para que os arquivos sejam disponibilizados publicamente através de repositórios. É de grande serventia para os desenvolvedores, pois além de promover um ambiente de colaboração entre usuários, pode ser usado como portfólio de projetos. É quase como um cartão de visitas para grandes instituições interessadas em contratar novos desenvolvedores.

## Markdown

É uma linguagem simples para fazer marcações em textos , criar conteúdos para uma página HTML e produzir documentos prontos para impressão. É utilizada em aplicativos como Github e Slack. Usamos para informar pontos importantes de um texto, inserir tópicos, demarcar links e imagens, sem precisar editar a página HTML necessariamente.

## Construção do Modelo usando SQL Power Arquitect e corrigindo erros do projeto

Inicialmente, realizei a interpretação do projeto através do modelo já disponibilizado para correção de erros e criar o modelo ideal. Foi possível identificar erros como duplo relacionamento entre duas tabelas, cardinalidade incoerente com o relacionamento e relacionamentos criados de forma incorreta. Após corrigir estes erros e gerar o modelo expresso no arquivo "si1n_202204249_hr.architect", um script para criação das tabelas, constraints e relacionamentos em SQL é gerado para que não seja necessário digitar os comandos para criação destes elementos. Isso é uma mão na roda, principalmente para projetos muito grandes. A principal proposta desta aplicação é otimizar o tempo.

## Implementação do Script e Reflexão da trajetória do projeto

Primeiramente, foi preciso aprender as particularidades de cada SGBD para que fosse possível adaptar o script para rodá-lo no SGBD em questão. Para isso, foi necessário acessar a documentação dos dois sistemas de gerenciamento. Através desse projeto, foi possível observar as diferenças, tanto de recursos, quanto de restrições. Por exemplo, o PostgreSQL apresenta mais recursos para o desenvolvedor e além disso, é gratuito. Já o MariaDB, é mais tolerável à diferenças de escrita, porém não apresenta uma diversidade de funcionalidades como o PostgreSQL. Apesar das várias tarefas dentro deste trabalho, foi possível amadurecer o pensamento sobre Banco de Dados de forma mais concisa e objetiva. Não estava acostumado com esta profundidade de exercícios, nem com o inglês dos manuais e aplicações utilizadas para desenvolver as questões. Aos poucos estou aperfeiçoando cada vez mais o pensamento!