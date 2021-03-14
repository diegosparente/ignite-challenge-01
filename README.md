# Desafio 01

O objetivo desse pequeno projeto é consolidar o aprendizado adquirido sobre manipulação de estado no ReactJS.

## O que deve ser feito?
A proposta era construir a funcionalidade de três funções presente no arquivo [src/components/TaskList.tsx](https://github.com/diegosparente/ignite-challenge-01/blob/main/src/components/TaskList.tsx). *handleCreateNewTask*, *handleToggleTaskCompletion* e handleRemoveTask. Cada uma obedecendo as seguintes orientações:

* handleCreateNewTask: Deve ser possível adicionar uma nova `task` no estado de tasks, com os campos `id` que deve ser gerado de forma aleatória, `title` que deve ser um texto e `isComplete` que deve iniciar como false.
* handleToggleTaskCompletion: Deve alterar o status de `isComplete` para uma task com um `id` específico que é recebido por parâmetro.
* handleRemoveTask: Deve receber um `id` por parâmetro e remover a `task` que contém esse `id` do estado.

## Resolução
* ### handleCreateNewTask
* ### handleToggleTaskCompletion
* ### handleRemoveTask

## Instalação

Para executar o projeto em sua máquina é preciso seguir alguns passos abaixo:

```bash
git clone git@github.com:diegosparente/ignite-challenge-01.git
```
O comando acima irá clonar o projeto para um diretório/pasta de sua preferência. Após concluir acesse o projeto:
```bash
cd ignite-challenge-01
```
E dentro do diretório do projeto execute o comando abaixo para instalar todas as dependências necessárias para o funcionamento do mesmo:

```bash
yarn
```

## Uso

Para executar em ambiente de desenvolvimento:

```bash
yarn dev
```
É possível também rodas os testes feitos com `jest` rodando o comando abaixo:

```bash
yarn test
```
