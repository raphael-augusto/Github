

```bash
#inicar
1° - git init
2° - git add .
3  - git commit
4  - git remote add origin <server>
5 -  git push origin main


# COMANDOS PARA NOVA BRANCH

1° cria branch - git checkout -b feature_x
    1.0 - add - git add . ou git add arquivo
		1.1 - commit - git commit -m ""
		1.2 - push na banch -> git push origin branch
2° muda para main - git checkout main
4° pega a branch mais nova - git pull
5° faz o merge para main - git merge <branch>
3° faz o push para main- git push origin <branch>
6° deleta - git branch -d feature_x  (deletar local)
            git push origin :feature_x (deletar remota)
