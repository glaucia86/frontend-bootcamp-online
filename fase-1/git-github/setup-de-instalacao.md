# Setup de Instalação

## Instalando o Git

Instale o Git no seu computador, através do Terminal para Mac ou Ubuntu e instalador para Windows.

### Mac

Para instalar no Mac, você precisará ter o [Homebrew](https://brew.sh/index_pt-br) instalado, abrir o Terminal e digitar o comando:

```css
$ brew install git
```

Após digitar este comando, aperte enter e aguarde a execução da instalação.

### Ubuntu / Linux

Abra o seu terminal e digite o seguinte comando

```css
$ apt-get install git
```

### Windows

Para instalar no Windows, faça download do instalador em: [http://git-scm.com/downloads](http://git-scm.com/downloads)

Dica: se você estiver com algum problema, tente seguir este[ passo a passo detalhado](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Instalando-o-Git).

Dica: Para verificar se o git já está instalado, abra o Terminal e digite `$ git`

## Configurando sua conta em seu computador

Configure suas informações de usuário, para que todos os repositórios que você irá trabalhar localmente estejam atrelados à sua conta. Para isso, abra o Terminal e digite os seguintes comandos:

* Nome de usuário:

```css
$ git config --global user.name "[nome]"
```

* E-mail da sua conta:

```css
$ git config --global user.email "[endereco-de-email]"
```

{% hint style="info" %}
 Lembre-se de substituir a informação entre `[colchetes]`pelos seus dados.
{% endhint %}

