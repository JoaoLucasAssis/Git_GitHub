# Trabalhando com Branches

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