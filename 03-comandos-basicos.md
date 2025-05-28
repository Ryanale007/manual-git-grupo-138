# Comandos Básicos do Git

Este módulo apresenta os comandos essenciais para começar a usar o Git em seus projetos locais. Todos os exemplos foram feitos em um repositório de teste.

---

## `git init`

Inicializa um repositório Git em uma pasta.

```bash
git init

Você cria uma pasta chamada projeto e entra nela:

bash
Copiar
Editar
mkdir projeto
cd projeto
git init

Isso cria uma pasta oculta chamada .git, que é onde o Git guarda todo o histórico do projeto.

git status
Mostra o status atual dos arquivos no repositório (modificados, adicionados, etc).

bash
Copiar
Editar
git status
Exemplo de saída:

bash
Copiar
Editar
On branch main

Untracked files:
  (use "git add <file>..." to include in what will be committed)
    index.html

nothing added to commit but untracked files present
git add
Adiciona arquivos para a área de preparação (staging area), preparando-os para serem salvos (commitados).

bash
Copiar
Editar
git add nome-do-arquivo
Exemplo:

bash
Copiar
Editar
git add index.html
Para adicionar todos os arquivos de uma vez:

bash
Copiar
Editar
git add .
git commit
Salva de fato os arquivos no repositório Git, com uma mensagem.

bash
Copiar
Editar
git commit -m "mensagem explicando a mudança"
Exemplo:

bash
Copiar
Editar
git commit -m "feat: adiciona estrutura inicial do HTML"
git log
Mostra o histórico de commits do projeto.

bash
Copiar
Editar
git log
Exemplo de saída:

bash
Copiar
Editar
commit 9fceb02a...
Author: Ryan Alexandre <RyanF4k3@UmEmail.com>
Date:   Sat May 25 14:30:21 2025 -0300

    feat: adiciona estrutura inicial do HTML
Simulação com Captura de Tela

Essa imagem mostra como o comando git status aparece após modificar arquivos e antes de fazer o commit.

Resumo
Comando	Função
git init	Inicia o repositório Git
git status	Mostra arquivos modificados e rastreados
git add	Adiciona arquivos à preparação
git commit	Salva os arquivos com uma mensagem
git log	Mostra o histórico de commits