# Análise de Sentimentos em Tweets usando Google Colab

Este repositório contém um projeto de análise de sentimentos em tweets utilizando Python no ambiente Google Colab. O projeto foi desenvolvido como parte da disciplina "Dando Inteligência ao Software" no curso de Desenvolvimento Full Stack da Universidade Estácio de Sá.

## Introdução

O objetivo deste projeto é analisar a percepção das pessoas sobre clubes de futebol da Inglaterra com base nos tweets coletados da rede social Twitter. Para isso, utilizamos técnicas de Processamento de Linguagem Natural (PLN) e Análise de Sentimentos, empregando as bibliotecas `spacy` e `spacytextblob`.

## Procedimentos

### Instalação das bibliotecas necessárias

Para realizar a análise de sentimentos, é necessário instalar as bibliotecas Python `spacy` e `spacytextblob` no ambiente do Google Colab. Estas bibliotecas são fundamentais para o processamento de linguagem natural e análise de sentimentos.

### Importação das bibliotecas

Após a instalação, importamos as bibliotecas necessárias no notebook do Google Colab. Isso inclui `spacy` para processamento de texto e `spacytextblob` para análise de sentimentos.

### Definição do modelo e pipeline

Carregamos o modelo `en_core_web_sm` fornecido pelo `spacy` e adicionamos a pipeline `spacytextblob` ao modelo. Esta pipeline facilita a análise de sentimentos nos textos dos tweets.

### Texto inicial para validação

Para verificar a configuração do ambiente, definimos um texto inicial simples e realizamos uma análise de sentimentos para validar os resultados esperados.

### Análise dos tweets

Definimos uma lista de tweets que serão analisados para determinar a percepção das pessoas sobre os clubes de futebol. Cada tweet é submetido à análise de sentimentos e os resultados são exibidos para compreensão dos sentimentos expressos.


