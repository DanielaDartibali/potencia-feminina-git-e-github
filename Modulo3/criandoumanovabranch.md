## Criando uma nova branch pelo terminal

Comando necessário para criação de uma nova Branch via Terminal: 

git checkout -b (nome da nova Branch)

Este comando irá criar e já trocar para essa nova Branch


## Criação de uma nova Branch via github 

1 - Acessar o repositório 
2 - Ir na sessão de listagens de Branch
3 - Criar a nova Branch inserindo o nome
4 - Confirmar a criação da Branch

obs.: Basta clicar em Master e descrever o nome que deseja e o mesmo irá verificar a possibilidade de nome caso exista ou não e para deixar como checkout master como visto no terminal, basta clicar em master --> master no github.


## Exclusão de Branchs no github

Podemos excluir as Branchs criadas tanto pelo terminal quanto no github no github com o comando :

Via github :   
1 - Vá na sessão de listagens de Branchs 
2 - Clique no ícone da lixeira para realizar a exclusão dessa Branch

Via Terminal:

git checkout main -->  git branch -D (Nome da Branch) 

Este comando irá verificar a Branch primeiro e o segundo comando irá excluir esta Branch.
Obs: Este comando só pode ser aplicado caso não tenha sido realizado o git add. e git push


# Correção e restauração de criações de branch devido possiveis erros

É possível restaurar o nome da branch caso tenha ocorrido erros pelo comando:

git restore (nome da Branch)


