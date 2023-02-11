# Comandos GIT

### git clone

Realiza o download do repositório:

```
$ git clone https://...
```

Especifica a branch (galho) do repositório que será baixada, para o dispositivo local:

```
$ git clone https://... -b main
```

### git log

Listando os commits e branchs:

```
git log
```

Listando os commits e branchs com uma linha para cada commit:

```
git log --oneline
```

Listando os commits e branchs em forma de gráfico:

```
git log --graph
```

Listando os commits e todas as branhcs:

```
git log --all
```

### git branch

Criando uma nova branch:

```
$ git branch $1 
```

$1 = Nome da nova branch
