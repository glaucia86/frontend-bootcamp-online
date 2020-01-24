# Comandos mais utilizados

## git status

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


## git status

Esse comando é responsável por mostrar os arquivos rastreados pelo   histórico de commits da branch local atual. No Terminal, use o comando `git log`.

#### Exemplo

```css
$ git log
```




## git status

Esse comando é responsável por mostrar os arquivos rastreados pelo git que foram modificados. No Terminal, use o comando `git status`.

#### Exemplo

```css
$ git status
```