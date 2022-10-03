## Incluir ou modificar todos arquivos do diretório:
```
git add .
```

## Fazer um commit com uma mensagem: 
```
git commit -m ""
```
### `O primeiro push de um repositório deve conter o nome do repositório e o branch`
```
git push -u origin master
```
### `Os demais pushes não precisam dessa informação`
```
git push
```

<hr/>
<br/>

## Verificar os estados dos arquivos/diretórios:
```
git status
```
## Exibir histórico:
```
git log
```
## Excluir commit: 
```
git reset --hard HEAD~1
```

<hr/>
<br/>

## Exibir repositório remoto:
```
git remote -v
```
## Vincular um repositório local com um remoto:
```
git remote add origin (Link do repositorio)
```
## Exibir informações dos repositórios remotos:
```
git remote show origin
```
### Desvincular um respositório remoto:
```
git remote rm (nome do repositorio remoto)
```