# Análise e inspeção de repositórios

## - Exibir detalhes de branch e tags

```git
git show
git show <tag>
```

`git show` - traz informações dos commits na branch atual

`git show <tag>` - traz informações das diferenças entre tags

## - Verificando diferenças

```git
git diff
git diff <branch>
git diff <arquivo> <arquivo_b>
```
`git diff` - exibe as diferenças entre o branch atual e o repositório

`git diff <branch>` - exibe as diferenças entre o branch atual e outro

`git diff <arquivo> <arquivo_b>` - exibe a diferença entre arquivos

## - Log das atividades resumido

```git
git shortlog
```

`git shortlog` - retorna um resumo dos commits e dos autores