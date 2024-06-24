# Estruturas-de-Dados

<h1 align="center">Desenvolvendo Lógica de Programação em C</h1>



<div align="center">
  <strong>🚀 Exemplos de exercicios e desafios de lógica computacional 📚</strong>
</div>

<div align="center">
  <p>Um repositório com ideias de exercicios para praticar C e lógica! 🎉</p>
  <p>Aqui você encontrará informações de cada projeto, tecnologias utilizadas, instruções para configurar o ambiente de desenvolvimento e muito mais.</p>
  <p>Explore, colabore e divirta-se! 😄</p>
</div>

## 📖 Índice

- [Visão Geral](#visão-geral)
- [Tecnologias](#tecnologias)
- [Configuração do Ambiente](#configuração-do-ambiente)
- [Como Contribuir](#como-contribuir)
- [Licença](#licença)

## 🔭 Visão Geral

Esse repositorio foi criado com o objetivo de ajudar outras pessoas que queiram ingressar na área de tecnologia e desejam praticar seus conhecimentos iniciais em Lógica Para Programação, aqui terá a descrição de cada questao, e as resolução estará nesse repositorios referente ao numero da questao, todas em C.
<br>
Isso é um compilado de algumas das atividades que foram desenvolvidas durante o meu 2 semestre da faculdade de Ciências da Computação, no Instituto Federal do Ceará, semestre 2023.2

## 💻 Questões

- Questão 1:
- Questão 2:
- Questão 3:
- Questão 4:
- Questão 5:
- Questão 6:
- Questão 7:
- Questão 8:
- Questão 9:
- Questão 10:
- Questão 11:
- Questão 12:
- Questão 13:
- Questão 14:
- Questão 15:
- Questão 16:
- Questão 17:
- Questão 18:
- Questão 19:
- Questão 20:


## ⚙️ Configuração do Ambiente

## 🤝 Como Contribuir

## 📄 Licença

Este projeto está licenciado sob a [MIT]. Consulte o arquivo [LICENSE](LICENSE) para obter mais informações sobre os termos de licenciamento.

---

Aproveite o projeto e fique à vontade para personalizar este README de acordo com as necessidades do seu repositório. Divirta-se codificando! 🎉😄


### EX21: IMPLEMENTAÇÃO PILHA
### *REQUISITOS:*
- Implemente um tipo abstrato de dados do tipo “Pilha" chamado TPilha.
Este deve manipular dados do tipo char e oferecer os seguintes serviços:
Exibir todos os elementos que estão na pilha
Esvaziar toda a pilha
Função push
Função pop
Não esqueça que o último elemento que entra na pilha deverá ser o primeiro a sair (LIFO - Last in First out
Entrada e saída de dados:
Seu programa deve ler como comandos de entrada e seus respectivos valores (separados por espaços). Os comandos possíveis são:
-s : exibe a pilha inteira
-c : esvaziar toda a pilha
-i : inserir (empilhar) um novo elemento na fila
-r : remover (desempilhar) um elemento da fila
Obs: após a execução do comando "-s", o programa deve ser encerrado.

//================================================================================//
### EX22: IMPLEMENTAÇÃO FILA
### *REQUISITOS:*
- Implemente um tipo abstrato de dados do tipo “Fila", chamado TFila.
Este deve manipular dados do tipo int e oferecer os seguintes serviços:
Exibir todos os elementos que estão na fila
Esvaziar toda a fila
Função para enfileirar
Função para desenfileirar
Não esqueça que o primeiro elemento que entra na fila deverá ser o primeiro a sair (FIFO - First in First out).
Entrada e Saída de dados:
Seu programa deve ler como comandos de entrada e seus respectivos valores (separados por espaços). Os comandos possíveis são:
-s : exibe a fila inteira
-c : esvaziar toda a fila
-i : inserir (enfileirar) um novo elemento na fila
-r : remover (desenfileirar) um elemento da fila
Obs: após a execução do comando "-s", o programa deve ser encerrado.

//===============================================================================//
### EX23: IMPLEMENTAÇÃO LISTA SIMPLESMENTE ENCADEADA
### *REQUISITOS:*
- Crie um tipo abstrato de dados para manipulação de uma Lista Simplesmente Encadeada. A Lista deve ser capaz de manipular dados do tipo int.
Atente para os requisitos solicitados e implemente as funcionalidades desejadas.
Seu programa deve ser capaz de ler como comandos de entrada os possíveis valores:
-s : exibe a lista inteira
-c : esvaziar toda a lista
-a < valor > : inserir um novo elemento na lista com o valor especificado (inserção estilo FIFO)
-a < valor > < posicao > : inserir um novo elemento na lista em uma posição especificada pelo parâmetro “posicao"
-r < valor > : remover todas as ocorrências de um elemento especificado da lista
-m : exibe o maior valor da lista
-sl : exibe o último elemento da lista
-sf : exibe o primeiro elemento da lista
-ss : exibe o tamanho da lista
-sg < valor > : exibe a quantidade de elementos da lista são maiores que o valor especificado
O comando -s deve exibir a lista e encerrar o programa.

//====================================================================================//
### EX24: IMPLEMENTAÇÃO LISTA SIMPLESMENTE ENCADEADA CIRCULAR
### *REQUISITOS:*
- Crie um tipo abstrato de dados para manipulação da Lista Simplesmente Encadeada Circular.
Atenção! A lista deve armazenar dados do tipo float.
Atente para os requisitos solicitados e implemente as funcionalidades desejadas.
Seu programa que deve ser capaz de ler como comandos de entrada os possíveis valores:
-s : exibe a lista inteira
-c : esvaziar toda a lista
-a < valor > : inserir um novo elemento na lista com o valor especificado (a inserção segue o padrão FIFO)
-a < valor > < posicao > : inserir um novo elemento na lista em uma posição especificada pelo parâmetro “posicao"
-r < valor > : remover todas as ocorrências de um elemento especificado da lista
-m : exibe o maior valor da lista
-sl : exibe o último elemento da lista
-sf : exibe o primeiro elemento da lista
-ss : exibe o tamanho da lista
-sg < valor > : exibe a quantidade de elementos da lista são maiores que o valor especificado
O comando -s deve exibir a lista e encerrar o programa.

//==========================================================================================//
### EX25: IMPLEMENTAÇÃO LISTA DUPLAMENTE ENCADEADA
### *REQUISITOS:*
- Crie um tipo abstrato de dados para manipulação de uma Lista Duplamente Encadeada. A Lista deve ser capaz de manipular dados do tipo char.
Atente para os requisitos solicitados e implemente as funcionalidades desejadas.
Seu programa deve ser capaz de ler como comandos de entrada os possíveis valores:
-s : exibe a lista inteira
-c : esvaziar toda a lista
-a < valor > : inserir um novo elemento na lista com o valor especificado (inserção estilo FIFO)
-a < valor > < posicao > : inserir um novo elemento na lista em uma posição especificada pelo parâmetro “posicao"
-r < valor > : remover todas as ocorrências de um elemento especificado da lista
-m : exibe o maior valor da lista
-sl : exibe o último elemento da lista
-sf : exibe o primeiro elemento da lista
-ss : exibe o tamanho da lista
-sg < valor > : exibe a quantidade de elementos da lista são maiores que o valor especificado
O comando -s deve exibir a lista e encerrar o programa.

//==========================================================================================//
### EX26: IMPLEMENTAÇÃO LISTRA DUPLAMENTE ENCADEADA CIRCULAR
### *REQUISITOS:*
- Crie um tipo abstrato de dados para manipulação da Lista Duplamente Encadeada Circular.
Atenção! A lista deve armazenar dados do tipo int.
Atente para os requisitos solicitados e implemente as funcionalidades desejadas.
Seu programa que deve ser capaz de ler como comandos de entrada os possíveis valores:
-s : exibe a lista inteira
-c : esvaziar toda a lista
-a < valor > : inserir um novo elemento na lista com o valor especificado (a inserção segue o padrão FIFO)
-a < valor > < posicao > : inserir um novo elemento na lista em uma posição especificada pelo parâmetro “posicao"
-r < valor > : remover todas as ocorrências de um elemento especificado da lista
-m : exibe o maior valor da lista
-sl : exibe o último elemento da lista
-sf : exibe o primeiro elemento da lista
-ss : exibe o tamanho da lista
-sg < valor > : exibe a quantidade de elementos da lista são maiores que o valor especificado
O comando -s deve exibir a lista e encerrar o programa.

//=======================================================================================================//
