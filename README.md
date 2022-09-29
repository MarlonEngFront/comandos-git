COMANDOS GIT 

1 - passa a rastrear a branch origin/nome-da-branch
- git branch --set-upstream-to=origin/nome-da-branch  

2 - cria uma branch baseada na branch atual
- git checkout -b nome-da-branch 

3 - adiciona todos os arquivos ao commit
- git add . 

4 - commita o arquivo atual com a mensagem
- git commit -m "mensagem" 

5 - troca de branch
- git checkout nome-da-branch 

6 - publica o branch para o repositorio remoto
- git push --set-upstream origin nome-da-branch

7 - clona o repositório
- git clone 

8 - comando git que mostra o nome do usuário e o nome do repositório do projeto atual 
- git config --get remote.origin.url

9 - commit de uma nova brach em origin/nome-da-branch
- git push --set-upstream origin nome-da-branch

10 - cria uma branch temporaria com as alteraçoes que ainda não foram commitadas
- git stash

11 - volta a branch com as alteraçoes do stash
- git stash apply

12 - lista os stashs do repositório
- git stash list

13 - Voltar para um stash específico
- git stash apply stash@{2}

14 - Criar um branch a partir de um stash
- git stash branch meu_branch

15 - Executar o eslint
- npm run lint

16 - mergear a branch atual que esta atrasada com outra branch esta mais atual, colocar o nome da branch que esta mais atual.
- git merge nome-da-branch 

17 - cria uma nova branch local a partir de uma branch origin
- git checkout -b nome-da-branch origin/nome-da-branch

18 - lista as versoes do node instalado 
- nvm list 

19 - nvm install 14
- ele instala a versão 14 - se vc passar 14.8  ele instala a 14.8.0

20 - nvm use 8.16 ele passa a usar a versão.

21 - renomeia a branch local
- git branch -m nome-da-branch

22 - deletar uma branch local
- git branch -d nome-da-branch

23 - passos para renomer branch origin
- deletar o branch remoto - git push origin --delete nome-da-branch
- renomear o branch local - git branch -m nome-da-branch
- criar um branch remoto - git push origin nome-da-branch

24 - deleta a node_modules
- rm -rf node_modules

25 - renomear um branch local e remoto 
 - git branch -m new_name
 - git push origin :old_name new_name

26 - limpar o cache do git
- git rm -r --cached.

27 - limpar o cache do npm
- npm cache verify
- npm cache clean --force

