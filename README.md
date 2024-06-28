# Estruturas-de-Dados

<h1 align="center">Estrutura de Dados</h1>



<div align="center">
  <strong>🚀 Exemplos de aplicações de estruturas de dados em algumas linguagens 📚</strong>
</div>

## 📖 Índice

- [Visão Geral](#visão-geral)
- .[Estruturas de Dados](#estrutura-de-dados)
- [Tecnologias](#tecnologias)

## 🔭 Visão Geral

Esse repositorio foi criado com o objetivo de dar exemplificações de aplicações de estruturas de dados em algumas linguagens, além de ajudar estudantes que estão em busca desse conhecimento tao utilizado e útil atualmente.
<br>
Cada estrutura tem uma descrição e exigencias do que devera conter nela.
<br>
Isso é um compilado de algumas das atividades que foram desenvolvidas durante o meu 2 semestre da faculdade de Ciências da Computação, no Instituto Federal do Ceará, semestre 2023.2

## Estruturas de Dados

1. <strong>Pilha:</strong> Implemente um tipo abstrato de dados do tipo “Pilha" chamado TPilha.<br>
Este deve manipular dados do tipo char e oferecer os seguintes serviços:<br>
Exibir todos os elementos que estão na pilha<br>
Esvaziar toda a pilha<br>
Função push<br>
Função pop<br>
Entrada e saída de dados:<br>
Seu programa deve ler como comandos de entrada e seus respectivos valores (separados por espaços). Os comandos possíveis são:<br>
-s : exibe a pilha inteira<br>
-c : esvaziar toda a pilha<br>
-i : inserir (empilhar) um novo elemento na fila<br>
-r : remover (desempilhar) um elemento da fila<br>
Obs: Não esqueça que o último elemento que entra na pilha deverá ser o primeiro a sair (LIFO - Last in First out<br>
após a execução do comando "-s", o programa deve ser encerrado.

2. <strong>Fila:</strong> Implemente um tipo abstrato de dados do tipo “Fila", chamado TFila.<br>
Este deve manipular dados do tipo int e oferecer os seguintes serviços:<br>
Exibir todos os elementos que estão na fila<br>
Esvaziar toda a fila<br>
Função para enfileirar<br>
Função para desenfileirar<br>
Não esqueça que o primeiro elemento que entra na fila deverá ser o primeiro a sair (FIFO - First in First out).<br>
Entrada e Saída de dados:<br>
Seu programa deve ler como comandos de entrada e seus respectivos valores (separados por espaços). Os comandos possíveis são:<br>
-s : exibe a fila inteira<br>
-c : esvaziar toda a fila<br>
-i : inserir (enfileirar) um novo elemento na fila<br>
-r : remover (desenfileirar) um elemento da fila<br>
Obs: após a execução do comando "-s", o programa deve ser encerrado.

3. <strong>Lista Simplesmente Encadeada: </strong>Crie um tipo abstrato de dados para manipulação de uma Lista Simplesmente Encadeada. A Lista deve ser capaz de manipular dados do tipo int.
Atente para os requisitos solicitados e implemente as funcionalidades desejadas.
Seu programa deve ser capaz de ler como comandos de entrada os possíveis valores:<br>
-s : exibe a lista inteira<br>
-c : esvaziar toda a lista<br>
-a < valor > : inserir um novo elemento na lista com o valor especificado (inserção estilo FIFO)<br>
-a < valor > < posicao > : inserir um novo elemento na lista em uma posição especificada pelo parâmetro “posicao"<br>
-r < valor > : remover todas as ocorrências de um elemento especificado da lista<br>
-m : exibe o maior valor da lista<br>
-sl : exibe o último elemento da lista<br>
-sf : exibe o primeiro elemento da lista<br>
-ss : exibe o tamanho da lista<br>
-sg < valor > : exibe a quantidade de elementos da lista são maiores que o valor especificado<br>
O comando -s deve exibir a lista e encerrar o programa.<br>

4. <strong>Lista Simplesmnete Encadeada Circular:</strong> Crie um tipo abstrato de dados para manipulação da Lista Simplesmente Encadeada Circular.
Atenção! A lista deve armazenar dados do tipo float.
Atente para os requisitos solicitados e implemente as funcionalidades desejadas.
Seu programa que deve ser capaz de ler como comandos de entrada os possíveis valores:<br>
-s : exibe a lista inteira<br>
-c : esvaziar toda a lista<br>
-a < valor > : inserir um novo elemento na lista com o valor especificado (a inserção segue o padrão FIFO)<br>
-a < valor > < posicao > : inserir um novo elemento na lista em uma posição especificada pelo parâmetro “posicao"<br>
-r < valor > : remover todas as ocorrências de um elemento especificado da lista<br>
-m : exibe o maior valor da lista<br>
-sl : exibe o último elemento da lista<br>
-sf : exibe o primeiro elemento da lista<br>
-ss : exibe o tamanho da lista<br>
-sg < valor > : exibe a quantidade de elementos da lista são maiores que o valor especificado<br>
O comando -s deve exibir a lista e encerrar o programa.<br>

5. <strong>Lista Duplamente Encadeada: </strong>Crie um tipo abstrato de dados para manipulação de uma Lista Duplamente Encadeada. A Lista deve ser capaz de manipular dados do tipo char.
Atente para os requisitos solicitados e implemente as funcionalidades desejadas.
Seu programa deve ser capaz de ler como comandos de entrada os possíveis valores:<br>
-s : exibe a lista inteira<br>
-c : esvaziar toda a lista<br>
-a < valor > : inserir um novo elemento na lista com o valor especificado (inserção estilo FIFO)<br>
-a < valor > < posicao > : inserir um novo elemento na lista em uma posição especificada pelo parâmetro “posicao"<br>
-r < valor > : remover todas as ocorrências de um elemento especificado da lista<br>
-m : exibe o maior valor da lista<br>
-sl : exibe o último elemento da lista<br>
-sf : exibe o primeiro elemento da lista<br>
-ss : exibe o tamanho da lista<br>
-sg < valor > : exibe a quantidade de elementos da lista são maiores que o valor especificado<br>
O comando -s deve exibir a lista e encerrar o programa.<br>

6. <strong>Lista Duplamente Encadeada Circular:</strong> Crie um tipo abstrato de dados para manipulação da Lista Duplamente Encadeada Circular.
Atenção! A lista deve armazenar dados do tipo int.
Atente para os requisitos solicitados e implemente as funcionalidades desejadas.
Seu programa que deve ser capaz de ler como comandos de entrada os possíveis valores:<br>
-s : exibe a lista inteira<br>
-c : esvaziar toda a lista<br>
-a < valor > : inserir um novo elemento na lista com o valor especificado (a inserção segue o padrão FIFO)<br>
-a < valor > < posicao > : inserir um novo elemento na lista em uma posição especificada pelo parâmetro “posicao"<br>
-r < valor > : remover todas as ocorrências de um elemento especificado da lista<br>
-m : exibe o maior valor da lista<br>
-sl : exibe o último elemento da lista<br>
-sf : exibe o primeiro elemento da lista<br>
-ss : exibe o tamanho da lista<br>
-sg < valor > : exibe a quantidade de elementos da lista são maiores que o valor especificado<br>
O comando -s deve exibir a lista e encerrar o programa.<br>

   
## 💻 Tecnologias

- Linguagem C

## 📄 Licença

Este projeto está licenciado sob a [MIT LICENSE]. Consulte o arquivo [LICENSE](LICENSE) para obter mais informações sobre os termos de licenciamento.
