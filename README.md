# semestre-empresarial-git-docker.
* $ docker pull hello-world
* $ docker run hello-world

## sql
* docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=root" --name sql -h imagensql -d mcr.microsoft.com/mssql/server:2019-latest

## GIT
*git init
*git add README.md
*git commit -m "first commit"
*git branch -M main
*git remote add origin https://github.com/SamuelJuarez1/semestre-empresarial-git-docker./edit/main/README.md.git
*git push -u origin main
