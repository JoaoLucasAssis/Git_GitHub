# Trabalhando com Branches e Stash

<div align="center">
    <a href="#criando_branches">Criando branches •</a>
    <a href="#deletando_branches">Deletando branches •</a>
    <a href="#mudando_de_branch">Mudando de branch •</a>
    <a href="#unindo_branches">Unindo branches</a>
</div>
<div align="center">
<a href="#utilizando_stash">Utilizando stash •</a>
<a href="#recuperando_stash">Recuperando stash •</a>
<a href="#removendo_stash">Removendo stash</a>
</div>

## Criando branches

```git
git branch <nome>
git branch
```

`git branch <nome>` - cria uma branch

`git branch` - visualiza os branchs disponíveis

## Deletando branches

```git
git branch -d <nome>
```
`git branch -d <nome>` - deleta a branch

## Mudando de branch

```git
git checkout <nome>
git checkout -b <nome>
```

`git checkout <nome>` - troca de branch

`git checkout -b <nome>` - cria uma branch e troca para ela

## Unindo branches

```git
git merge <nome_da_branch>
```

`git merge <nome_da_branch>` - junta duas ou mais branchs, se os arquivos existentes forem compatíveis

## Utilizando stash

```git
git stash
```

`git stash` - separa as novas atualizações do diretório

## Recuperando stash

```git
git stash list
git stash apply <numero>
```

`git stash list` - retorna uma lista de stash "salvos"
`git stash apply <numero>` - retorna o stash para o diretório

## Removendo stash

```git
git stash drop <numero>
```

`git stash drop <numero>` - deleta o stash da lista