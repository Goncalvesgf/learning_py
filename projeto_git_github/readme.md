 # primeiro projeto de configuração de arquivos usando terminal git bash e vs code
 
  comandos utilizados no terminal git bash

  **code .**  (inicia o vs code)

  **git init** (criou arquivo oculto .git e definiu o diretorio escolhido como master do branch do projeto)
  **git config --global user.name** (definiu as iniciais do projeto Nome de Usuário "Guilherme Goncalves Figueiredo")
  **git config --global user.email**  (Definiu o email do usuário - "goncalvesgfmkt@hotmail.com" que é o mesmo da conta do github)
 
  ---- as informacoes configuradas de user são utilizadas para vincular o repositorio na conta do GitHub ----

 foi criado o arquivo **readme.md** (vulgo esse arquivo) pelo vs code ("extensão .md significa markdown - extensão utilizada também pelo Jupyter Notebook)
 
 vs code detetou o arquivo **untracked** na aba **controle de versionamento** do lado esquerdo
 abrimos o terminal com **control+'** e selecionamos os terminal git bash dentro do git bash
 
 **git status** (identificamos que o arquivo estava untracked pelo terminal)
 
 **git add readme.md** (adicionamos o arquivo como tracked, porém não commited - está preparado para ser commited)
 
 **git commit -m "primeiro commit feito"** ( -m retorna a mensagem na versão do arquivo) - agora está comitado!

 ### Alterei o nome de usuario para "Goncalvesgf" [git config --global user.name] - fiz isso depois do processo de commited se der erro --- refazer todo o processo novamente!
 ---
 ### Percebi que esse projeto estava indo para um outro caminho e resolvi adicionar uma pasta **projeto_git_github**
 ### Pelo vs code fiz isso e movi o arquivo readme.md para essa pasta o que fez com que ficasse untracked novamente
 
 ### Refiz todo o processo na nova pasta add commit no arquivo readme.md 
 ### Ativei o autosave no vs code e o arquivo gerou status de modified
 ### No controle de versionamento agora, existem 2 arquivos mapeados e o primeiro esta com status deleted.
 **git status** novamente para confirmar o status modified "M" no vscode
 **git add readme.md** novamente para adicionar ele na **Stage**
 

