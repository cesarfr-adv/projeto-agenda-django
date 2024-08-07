Iniciar o projeto Django

```
python -m venv venv
. venv/bin/activate
pip install django
django-admin startproject project .
```

Configurar o git

```
# abra o git bash
# vá até o diretório do projeto
git config --global user.name 'Cesar Franca'
git config --global user.email 'cesarfr.adv@gmail.com'
git config --global init.defaultBranch main
# Configure o .gitignore
git init
git add .
git commit -m 'Mensagem'
# Crie um novo repositorio no github e cole o link SSH abaixo
git remote add origin git@github.com:cesarfr-adv/projeto-agenda-django.git

# para subir os arquivos
# acesse o Git Bash e vá até o diretório onde está o projeto
git add .
git log --oneline
git push origin main -u
```
