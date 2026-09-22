# LearnGit
Learning GitHub and best programming practices;

Bibliography https://git-scm.com/book/en/v2

Markdown https://www.craftmarkdown.com/markdown-cheat-sheet and https://www.markdownlang.com/pt/advanced/math.html

## Initializing Git:

- git config --global user.name "Nome"
- git config --global user.email nome@example.com

- git init

- git clone
- git clone -b branchname 'directory link.git'
- git clone --branch branchname --single-branch 'directory link.git'

## Commands:

- git status
- git add .
- git add something.py
- git commit -m "Description"
- git commit --amend -m "New Message"
- git push
- git diff
- git diff --staged
- git log --oneline --decorate --graph --all
- git push --force-with-lease origin main

## Using branches:

From Git version 2.23 onwards you can use git switch instead of git checkout to:

Switch to an existing branch: 
- git switch testing-branch.

Create a new branch and switch to it:
- git switch -c new-branch. 
- git switch --create.

Return to your previously checked out branch: git switch -

## Conventional Commits:

| Tipo     |  Uso                                  |
|----------|---------------------------------------|
| feat     | nova funcionalidade                   |
| fix      | correção de bug                       |
| refactor | reorganização sem mudar comportamento |
| test     | criação/modificação de testes         |
| docs     | documentação                          |
| style    | formatação, espaços etc               |
| chore    | manutenção/configuração               |