# Trabalhando com Branches

## - Criando branches 

```git
git branch <nome>
git branch
```

`git branch <nome>` - cria uma branch

`git branch` - visualiza os branchs disponíveis

## - Deletando branches

```git
git branch -d <nome>
```
`git branch -d <nome>` - deleta a branch

## - Mudando de branch

```git
git checkout <nome>
git checkout -b <nome>
```

`git checkout <nome>` - troca de branch

`git checkout -b <nome>` - cria uma branch e troca para ela

## - Unindo branches

```git
git merge <nome_da_branch>
```

`git merge <nome_da_branch>` - junta duas ou mais branchs, se os arquivos existentes forem compatíveis

# Trabalhando com Stash 

## - Utilizando stash

```git
git stash
```

`git stash` - separa as novas atualizações do diretório

## - Recuperando stash

```git
git stash list
git stash apply <numero>
```

`git stash list` - retorna uma lista de stash "salvos"
`git stash apply <numero>` - retorna o stash para o diretório

## - Removendo stash

```git
git stash drop <numero>
```

`git stash drop <numero>` - deleta o stash da lista

# Utilizando tags

* Utilizadas para **demarcar** os estágios de desenvolvimento

* Também utilizada como ponto de marcação e recuperação do projeto

* Utilizar tags após os commits

* Para bom costume, usar (*v1.0*, *v2.0*, *...*) para os nomes das tags

```git
git tag -a <nome> -m "<msg>"
```

## - Verificando tags

```git
git tag 
```

`git tag` - mostra uma lista de tags do projeto

## - Trocando de tags 

```git
git checkout <nome> 
```

`git checkout <nome>` - retorna os arquivos para a marcação da tag

## - Enviando tags ao repositório

* Serve para outros desenvolvedores acompanharem o desenvolvimento dos seus códigos

```git
git push origin <nome>
git push origin --tags
```

`git push origin <nome>` - envia a tag para o repositório

`git push origin --tags` - envia todas as tags para o repositório