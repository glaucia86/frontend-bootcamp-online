<p align="center"><img src="https://miro.medium.com/max/590/0*zBqamGxtqcZQA3hI"></p>
<h1 align="center">Git & GitHub</h1>



#### GIT 


Se trata de um sistema de controle de versionamento para o seu código. Por meio dele é possível desenvolver projetos em que diversos desenvolvedores podem contribuir simultaneamente, editando, criando arquivos sem o risco destas alterações serem sobrescritas.  É necessário fazer a instalação dele na máquina, assim temos acesso aos recursos via terminal, caso não ache tão amigável as linhas de comandos, existe também a versão amigável com um interface (GUI) e pode variar dependendo do seu Sistema Operacional.  Sua instalação é bem simples e basta seguir o passo a passo que o próprio site disponibiliza. 
Com ele instalado em sua máquina, é necessário fazer algumas configurações, como o seu nome e email de cadastro. Para configurar o seu nome execute o seguinte código no seu terminal ```git config --global user.name “Seu Nome”``` , e para seu email, ```git config --global user.email “email@provedor.com”```. Caso queira copiar as suas configurações globais, basta copiar o arquivo .gitconfig que fica em sua pasta de usuário. 
Para compreender como se dá todo o processo de versionamento de um código é necessário compreender alguns termos, como “repositório”, “commit”, “pull”, “branches” e alguns outros. Não se assuste, conforme vai praticando fica mais simples.

<a href="git-scm.com/downloads">Download Git</a>

##### Repositório

Nada mais é do que a pasta onde ficam os arquivos do projeto. É possível criar um ou até mesmo clonar/baixar um de algum site de hospedagem de repositórios. 
	Na prática o repositório fica hospedado em algum site, servidor pois assim facilita na hora de trabalhar em grupos, onde cada desenvolvedor faz uma cópia para o seu computador podendo assim então fazer as alterações necessária sem comprometer o repositório principal. 
 
``` Commit ```

Feito as alterações em seu repositório local, é hora de efetuar o ```commit```. Ou seja, estamos confirmando as mudanças no código. É como se estivéssemos tirando uma foto do nosso código e preparando ele para enviar ao repositório remoto. 

``` Pull ``` 

Seria “empurrar” o seu código para o repositório remoto, estaria subindo os arquivos para um destino (o repositório propriamente dito no caso)



```Branches ```

Se trata de uma forma de deixar organizado o nosso repositório. Existe a branch chamada master, nela termos a versão oficial do nosso projeto. Quando é necessário fazer alguma alteração, é feita uma ramificação desta branch principal, assim podendo trabalhar nela sem afetar o código oficial. Quando finalizado o trabalho na ramificação, podemos juntar com a master (que no caso chamamos esta soma de branches de merge) 

#### GITHUB

O Github é um serviço web que oferece diversas funcionalidades extras aplicadas ao git. Resumindo, você poderá usar gratuitamente o github para hospedar seus projetos pessoais. Além disso, quase todos os projetos/frameworks/bibliotecas sobre desenvolvimento open source estão no github, e você pode acompanhá-los através de novas versões, contribuir informando bugs ou até mesmo enviando código e correções. 

<a href="https://github.com">GitHub</a>

<h4>Links utéis</h4>

- [Documentação do GIT](https://git-scm.com/book/pt-br/v1/)

###### Links para praticar sem preocupação 

- [Learn Git](https://learngitbranching.js.org/)

- [Git School](http://git-school.github.io/visualizing-git/#free)

###### Podcast

- [Git e Github – Hipsters #109](https://open.spotify.com/episode/5Ld1auhh0vLPuSSnTGE0eR?si=J3FfP76tR9mLZMx7-pZl0A)


###### Curso Gratuito 

- [Git e GitHub para iniciantes](https://www.udemy.com/git-e-github-para-iniciantes)

###### Referências 

- [Trabalhando com repositórios remotos - William Oliveira](https://woliveiras.com.br/posts/trabalhando-com-reposit%C3%B3rios-remotos-git-e-github/)

- [Versionamento de código - William Oliveira](https://woliveiras.com.br/posts/introdu%C3%A7%C3%A3o-a-versionamento-de-c%C3%B3digo-e-conhecendo-o-git/)

- [Plano para estudar Git e GitHub enquanto aprende programação - William Oliveira](https://medium.com/trainingcenter/plano-para-estudar-git-e-github-enquanto-aprende-programa%C3%A7%C3%A3o-f5d5f986f459)

- [Tudo que você queria saber sobre Git e GitHub, mas tinha vergonha de perguntar - Daniel Schmitz](https://tableless.com.br/tudo-que-voce-queria-saber-sobre-git-e-github-mas-tinha-vergonha-de-perguntar/)

- [What is git](https://www.edureka.co/blog/what-is-git/)

- [Git Guide](https://rogerdudler.github.io/git-guide/index.pt_BR.html)
