# Comandos mais utilizados

## git add

Após criar um arquivo, adicione o arquivo no rastreamento do Git. No Terminal, use o comando `git add` seguido do nome do arquivo ou somente `.` para adicionar todos os arquivos ainda não rastreados.

```css
$ git add index.html
```

## git commit

Depois de adicionar o arquivo a ser rastreado, confirme as alterações a serem rastreadas usando o Git. No Terminal, use `git commit - m` seguido por uma mensagem curta para confirmar as mudanças.

```css
$ git commit -m "commit inicial"
```

{% hint style="info" %}
Dica: tente tornar suas mensagens curtas, mas significativas. 
{% endhint %}

#### Exemplo

```css
$ git commit -m "Página inicial e pastas de CSS e JS"
```

## git pull

Depois de confirmar as alterações, sincronize seu repositório local de sua máquina com o repositório remoto. No Terminal, use o comando `git pull` seguido do nome da branch que você buscar as alterações.

#### Exemplo

```css
$ git pull origin master
```


## git push

Depois de confirmar as alterações, envie as alterações de sua máquina local para o repositório remoto. No Terminal, use o comando `git push` seguido do nome da branch que você está enviando.

#### Exemplo

```css
$ git push origin master
```


## git log

Esse comando é responsável por mostrar o histórico de commits da branch local atual. No Terminal, use o comando `git log`.

#### Exemplo

```css
$ git log
```

## git status

Dentro do seu repositório local, execute o comando `git status` para monitorar os arquivos e pastas rastreados pelo git que sofreram modificações. No Terminal, use o comando `git status`.

#### Exemplo

```css
$ git status
```

## git branch

Dentro do seu repositório local, execute o comando `git branch` para listar, criar ou remover as branches do seu repositório local. No Terminal, use o comando `git branch` para listar as branches, para criar use o comando `git branch` seguido pelo nome da nova branch, para remover use o comando `git branch -D` seguido pelo nome da branch a ser removida.

#### Exemplo para listar
```css
$ git branch
```
#### Exemplo para criar nova branch
```
$ git branch nome_nova_branch
```
#### Exemplo para remover uma branch
```
$ git branch -D nome_da_branch
```

## git checkout

Dentro do seu repositório local, execute o comando git checkout seguido pelo nome da branch para alternar entre as branches do seu repositório local. No Terminal, use o comando `git checkout`.

#### Exemplo

```css
$ git checkout developer
```