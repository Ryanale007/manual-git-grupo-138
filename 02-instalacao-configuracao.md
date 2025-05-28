# Instalação e Configuração

## Como instalar o Git

### **Instalando no Windows:**
1 - Abre o seu navegador.

2 - Acesse o site oficial do Git: https://git-scm.com

3 - Clique em **Download for Windows**.

4 - Aperte em **Click here to download** e então ele vai começar a instalar.

5 - Após instalar, abra o instalador.

6 - Aperte em **Next**.

7 - Escolha o caminho que você gostaria de baixar. Você pode deixar no padrão e então aperte em **Next**.

8 - Em **Select Components** aperte em **Next** novamente.

9 - Em **Select Start Menu Folder**, aperte em **Next**. Ou se você não queira criar uma pasta no menu iniciar, você pode clicar no quadrado onde está escrito **Don't create a Start Menu Folder** e aperte em **Next**.

10 - Em **Chose the default editor used by Git** você deve escolher o seu editor padrão. Após escolher, aperte em **Next** novamente.

11 - Nas próximas, você pode apertar tudo em **Next**, até chega no **Install** e então você aperte em **Install**. E então, o Git começará a ser instalado em seu Windows.

12 - Após a instalação terminar, aperte em **Finish**. E pronto, o o Git está instalado em seu Windows. 

### **Instalando no Mac**

A forma mais fácil de instalar é usando o **Homebrew**, que é um gerenciador de pacotes para Mac.

1 - Primeiro, abra o terminal.

2 - Digite:
   ```bash
   brew install git
   ```

   3 - E espere a instalação terminar.

   4 - Pronto, o Git foi instalado em seu Mac.

   ### **Instalando no Linux**
   1 - Abra o terminal.

   2 - Digite esse comando:
   ```bash
   sudo apt update
   ```
3 - Digite o último comando:
   ```bash
   sudo apt install git
   ```
4 - Pronto, o Git foi instalado em seu Linux.

## **Configurando**

1 - Abra o terminal
- No Windows, abra o Git Bash

- No Mac ou Linux, abra o Terminal

2 - Digite esses comandos (com seu e-mail e nome que você usou para criar sua conta no GitHub) 
   ```bash
   git config --global user.name "Seu Nome Aqui"

    git config --global user.email "seu@email.com"
   ```

   3 - Para ver se o Git guardou seu nome e e-mail, digite:
   ```bash
   git config --list
   ```

   4 - Pronto, a configuração está pronta!

   ## **Checagem da instalação**

   1 - No terminal (ou Git Bash), digite:
   ```bash
   git --version
   ```

   2 - Se aparecer algo como: 
   ```bash
   git version 2.49.0
   ```

   3 - O Git foi instalado com sucesso!