# Mini Projeto Lista de Produtos 
**Integrantes:** Douglas Gonçalves, Carlos Eduardo, Carlos Manuel

Este é um programa simples em **JavaScript (Node.js)** que permite **cadastrar** e **listar produtos** utilizando entrada de dados via console com o pacote [`prompt-sync`](https://www.npmjs.com/package/prompt-sync).

## Funcionalidades
- Cadastrar produtos informando:
  - Nome
  - Preço
  - Quantidade em estoque
- Listar todos os produtos cadastrados
- Menu interativo no terminal
- Finalizar o programa quando desejar

---

## Pré-requisitos
- [Node.js](https://nodejs.org) instalado na sua máquina
- Gerenciador de pacotes `npm`

---

## Instalação
1. Clone este repositório ou copie o código para um arquivo chamado `app.js`
2. Instale o pacote `prompt-sync`:
   ```bash
 sudo  npm i prompt-sync
   
   
 Como executar

No terminal, rode o comando:

node app.js

 Exemplo de uso

 MENU 
1 - Cadastrar produto
2 - Listar produtos
0 - Sair
Escolha uma opção: 1

--- Cadastro de Produto ---
Digite o nome do produto: Teclado
Digite o preço do produto: 150
Digite a quantidade: 5
 Produto cadastrado com sucesso!

 Estrutura do código

cadastrarProduto() → Função para adicionar novos produtos ao array produtos.

listarProdutos() → Exibe todos os produtos cadastrados.

menu() → Controla as opções disponíveis e executa o loop principal do programa.

