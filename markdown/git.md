# Git fundamental 

## - Criando um repositório

```git
git init 
git add . 
git commit -a -m "description"
git branch -M main
git remote add origin (url)
git push -u origin main
```

`git init` - cria ou reinicializa um repositório git

`git add` - adiciona os arquivos ao repositório

`git commit` - registra alterações no repositório

`git push` - envia os arquivos registrados para o repositório

## - Verificando alterações

```git
git status
git log
```
`git status` - retorna se houve alterações nos arquivos

`git log` - retorna informações dos commits realizados

## - Recebendo alterações

```git
git pull
```

`git pull` - retorna alterações feitas no repositório para o diretório


## - Clonando repositórios

```git
git clone (url) .
```

`git clone` - clona os arquivos do repositório em um novo diretório
