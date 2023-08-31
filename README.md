README-PARTNERS CI


# API-QA.CODERS
# AUTOMAÇÃO BACK-END - PARTNERS

**PROJETO QA.CODERS ACADEMY - AUTOMAÇÃO DA API PARTNERS**

## Instalação do Ambiente

* NodeJs

## Comando para instalar o Newman:
```sh default
* npm install -g newman
```
## Comando para executar apenas com a Collection:
```sh default
* newman run nomeCollection.json
```
## Comando pra executar com as variáveis:
```sh default
* newman run NomeCollection.json -e NomeEnvironments.json
```
## Comando pra instalar o Report:
```sh default
* npm install -g newman-reporter-htmlextra
```
## Comando pra executar o Newman e gerar o Relatório HTML:
```sh default
* newman run nomeCollection.json -e NomeEnvironments.json -r htmlextra
```
