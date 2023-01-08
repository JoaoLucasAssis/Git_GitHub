# Compartilhamento e atualização de repositórios

## - Encontrando Branches

* Seu diretório pode não conter todas as branches e tags criadas por outros devs

```git
git fetch -a
```

`git fetch -a` - atualiza seu diretório com todos os branches e tags

## - Utilizando o remote

```git
git remote -v
git remote remove origin
git remote add origin (url)
```

`git remote -v` - mostra a url do repositório
`git remote remove origin` - remove a url 
`git remote add origin (url)` - adiciona a url

## - Utilizando submodulos

* Maneira de possuir dois ou mais repositórios em um diretório

* **.gitsubmodules** é criado para controlar os submódulos

* Para enviar/atualizar arquivos ao repositório:
    * abrir o terminal do submódulo
    * commitar a atualização
    * utilizar o comando `git push --recurse-submodules=on-demand`

```git
git submodule add (url) <nome>
git submodule
git push --recurse-submodules=on-demand
```

`git submodule add (url) <nome>` - adiciona um submódulo ao diretório
`git submodule` - mostra a quantidade de submódulos
`git push --recurse-submodules=on-demand` - comando para mandar arquivos para o submódulo