# Projeto DIO - APP de Cadastro de Séries
![.NET](https://img.shields.io/badge/.NET-5C2D91?style=plastic&logo=.net&logoColor=white)
![CSharp](https://img.shields.io/badge/C%23-239120?style=plastic&logo=c-sharp&logoColor=white)

## Descrição

Aprenda como criar um algoritmo simples de cadastro de séries para praticar seus conhecimentos de orientação a objetos, o principal paradigma de programação utilizada no mercado. Nesse projeto você vai aprender: Como pensar orientado a objetos, como modelar o seu domínio, como utilizar recursos de coleção para salvar seus dados em memória.

- Especialista: Eliézer Zarpelão
- Projeto base: https://github.com/elizarp/dio-dotnet-poo-lab-2

## Requisitos Básicos

- Lógica de programação
- Conhecimento básico de POO
- Conhecimento básico de .NET

## Conceitos abordados

- CRUD
  - **C**reate: Criar novos recursos
  - **R**ead: Ler recursos da memória/banco de dados
  - **U**pdate: Atualiza os recursos
  - **D**elete: Exclui recursos da memória/banco de dados

- Classes Abstratas
  > Uma classe abstrata é uma classe que serve de modelo para outras classes. Ela sempre será uma superclasse genérica, e suas subclasses serão mais específicas. Além disso, ela não pode ser instanciada e pode conter ou não métodos abstratos, podendo ser implementados nas classes descendentes. Ou seja, uma classe abstrata pode implementar ou não um método, sendo obrigatória a existência de pelo menos um método abstrato, sem corpo.

- Interfaces
  > As interfaces são padrões definidos através de contratos ou especificações. Um contrato define um determinado conjunto de métodos que serão implementados nas classes que assinarem esse contrato. Uma interface é 100% abstrata, ou seja, os seus métodos são definidos como abstract, e as variáveis por padrão são sempre constantes (static final).

## Comandos da CLI

Para iniciar a criação deste aplicativo utilizando a CLI:

```shell
dotnet new console -n aplicativo
```

Para executar o aplicativo utilizando a CLI:

```shell
dotnet run
```