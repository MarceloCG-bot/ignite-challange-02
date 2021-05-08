# Desafio 02 : Componentizando a aplicação

Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no ReactJS

Essa será uma aplicação onde o seu principal objetivo é refatorar uma página para listagem de filmes de acordo com gênero.

A aplicação já está totalmente funcional mas grande parte do seu código está diretamente no arquivo App.tsx. Para resolver isso da melhor forma, é necessário dividir a aplicação em pelo menos duas partes principais: sidebar e o conteúdo principal que possui o header e a listagem de filmes.

## Como baixar e executar o projeto

 - Clone o repositório ou baixe como ZIP e descompacte;
 - Execute o backend do repositório `https://github.com/MarceloCG-bot/ignite-challenge-02`
 - Abra seu terminal na pasta raiz do projeto e execute `yarn` para baixar as dependências;
 - Para iniciar a aplicação execute o comando  `yarn dev`
 - Fake API com JSON Server, execute o comando `yarn server`
 - A aplicação será executada na porta `8080`

## Fake API com JSON Server

Utilizamos o JSON Server para simular uma API que possui as informações de gêneros e filmes. 

## Ações da aplicação
- A aplicação possui apenas uma funcionalidade principal que é a listagem de filmes;
- Na sidebar é possível selecionar qual categoria de filmes deve ser listada;
- A primeira categoria da lista (que é "Ação") já deve começar como marcada;
- O header da aplicação possui apenas o nome da categoria selecionada que deve mudar dinamicamente.