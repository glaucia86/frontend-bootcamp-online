# Vocabulário do Git

Neste vocabulário reunimos as expressões mais comuns, utilizadas para referenciar comandos de versionamento de projetos com Git (que valem para GitHub também!)

## Versionamento

O versionamento de software é um processo de controle de versões, estabelecido por meio de "numerações" de históricos diferentes. Isso permite que os programadores e programadoras saibam quando e quais alterações foram realizadas, acompanhando as mudanças aplicadas no software.

## Repositório

O repositório é a pasta do projeto. Todo repositório tem uma pasta oculta .git. Isso é o que mostra para o git e para você que existe um repositório naquela pasta.

## Change \(ou Diff\)

O Git mantém o controle de versão rastreando as mudanças ou diferenças entre as versões dos arquivos.Você pode alterar um arquivo fazendo uma das duas coisas:

1. Criação, renomeação ou exclusão de arquivos. 
2. Inserção ou exclusão de uma linha em um arquivo \(uma linha modificada é uma inserção e uma exclusão\) 

O Git representa inserções ou alterações adicionadas com um `+` e exclusões ou alterações removidas com um `-`

## Commit

Um commit é um grupo de alterações no código. Toda vez que você quiser "salvar" as alterações feitas por você no repositório, você commita essas mudanças. Um commit contém as alterações que foram feitas nele e uma mensagem descritiva, além de informações meta \(data, autor, etc\).

## Branch

Branches são separações de código. O branch padrão do projeto é o master. Branches normalmente são utilizados para separar alterações grandes ou novas funcionalidades do projeto.

## Merge

Um merge é a união de duas branches, normalmente, merges são feitos na branch master. No exemplo do blog, quando a alteração do blog for terminada, alguém vai unir essas alterações na branch master para que elas possam finalmente fazer parte do projeto de fato.

## Clone

Um clone de um repositório funciona como uma branch de um repositório online em um repositório local. Ou seja, quando se deseja trabalhar em um repositório hospedado no github, clona-se esse repositório para o seu computador, trabalha-se nele, e então é pedida a permissão para atualizar as alterações online.

## Pull

É uma atualização do repositório local. É feito um merge do repositório online com o local para que os conflitos sejam resolvidos e seja possível enviar o código \(sem conflitos\) para o repositório online por meio de um push.

## Push

Envia o código para o repositório online.

## Fork

O fork é como um clone, porém dentro do github. Isso quer dizer que o repositório não vai ser baixado para seu computador, mas será criado um igual na sua conta.

## Pull Request

Um pull request é um pedido que se faz ao dono do repositório para que esse atualize o código dele com o seu código. Ou seja, você pede para que o dono do projeto ao qual você quer contribuir adicione suas modificações ao projeto oficial.
