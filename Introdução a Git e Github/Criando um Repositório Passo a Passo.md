# Passo a Passo da Criação de um Repositório

- Passo 1 - Crie uma pasta onde deseja endereçar seu repositório, no passo a passo a pasta de exemplo será Repositório 1.

- Passo 2 - Abra o Git Bash (caso não tenha instalado [clique aqui][Git (git-scm.com)](https://git-scm.com/)

- Passo 3 -  ao entrar no Git dê um comando ls, para checar se a pasta Repositório 1 se encontra no diretório em que está, caso esteja, siga para o passo 5, do contrário, siga para o passo 4.

- Passo 4 - caso precise mudar de diretório para encontrar sua pasta. Dê o comando cd + endereço da pasta. Ex.: cd /c/. Feito isso, dê o comando ls e verifique se sua pasta se encontra no repositório. Caso sim continue pro próximo passo, caso não verifique se digitou o endereço corretamente.

- Passo 5 - insira o comando cd Repositório 1e dê enter

- Passo 6 -Abra a pasta Repositório 1 e crie um arquivo de texto (botão direito>novo>arquivo de texto), chamaremos esse arquivo de Primeiros Passos no Git.md (md é a simbologia de formato markdown, caso deseja saber mais sobre o signficado desse formato [clique aqui ][][][[][Guia de Marcação (markdownguide.org)](https://www.markdownguide.org/)

- Passo 7 -  Dê um ls para ver se seu arquivo de texto se encontra no diretório, caso esteja, prosiga para o próximo passo.

- Passo 8 - Agora daremos inicio ao procedimento para criar seu repositório no Git. Dê o comando git init, caso esteja tudo certo, aparecerá a msg: "Initialized empty Git repository in C:/Repositório-1/.git/". 

  Dê um git status para verificar o status do seu arquivo, aparecerá  a msg:

  "On branch master

  No commits yet

  Untracked files:
    (use "git add <file>..." to include in what will be committed)
          Primeiros Passos no Git.md

  nothing added to commit but untracked files present (use "git add" to track)" indicando que seu arquivo tem alguma modificação, siga para o proximo passo.

- Passo 9 - Dê o comando git add *, caso não retorne nenhuma msg de erro, significa que ocorreu tudo certo. Para veririficar se ocorreu tudo bem, use o comando git status para verificar o status do seu arquivo. Deve aparecer a msg: 

  "On branch master

  No commits yet

  Changes to be committed:
    (use "git rm --cached <file>..." to unstage)
          new file:   Primeiros Passos no Git.md" indicando que seu arquivo foi adicionado mas ainda não recebeu o commit, siga para o próximo passo.

Passo 10 - Dê o comando git commit -m "declare um comentario sobre sua alteração ou do que se trata esse arquivo", deve retornar a seguinte msg: 

"git commit -m "declare um comentario sobre sua alteração ou do que se trata es
[master (root-commit) 8b0c073] declare um comentario sobre sua alteração ou do q
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Primeiros Passos no Git.md", inidicando que ocorreu tudo certo no seu commit, caso queira checar faça o comando git status deve retornar a seguinte msg: "

On branch master
nothing to commit, working tree clean" indicando que ocorreu tudo certo com seu commit



