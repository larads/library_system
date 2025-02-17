# Sistema de Gestão de Biblioteca

Sistema de Gestão de Biblioteca! projeto desenvolvido como parte de um desafio da Java. O objetivo é aplicar conceitos fundamentais de Java, incluindo herança, polimorfismo, estruturas de repetição, e manipulação de datas.

## Funcionalidades

### Gerenciamento de Livros
- **Listar todos os livros disponíveis**: Exibe apenas os livros que estão disponíveis para empréstimo.
- **Realizar empréstimo de um livro**: Permite que um usuário escolha um livro disponível e registre o empréstimo.


## Estrutura do Projeto

O projeto é dividido nas seguintes classes principais:

- **Livro**: Representa os livros na biblioteca, com atributos como `id`, `titulo`, `autor`, `disponivel`, `dataCadastro` e `dataAtualizacao`.
- **Autor**: Representa os autores dos livros, com atributos como `id`, `nome`, e `dataNascimento`.
- **Emprestimo**: Gerencia os empréstimos de livros, com informações sobre o livro emprestado e datas de empréstimo e devolução.
- **Biblioteca**: Gerencia a coleção de livros, autores e empréstimos.

## Requisitos

- Java Development Kit (JDK) 8 ou superior
- IDE de sua escolha (Eclipse, IntelliJ IDEA, NetBeans, vsCode etc.)

## Após iniciar
A aplicação irá perguntar se você deseja ver os livros disponíveis.
Após escolher um livro, você pode realizar o empréstimo, que será registrado e o livro marcado como indisponível.
