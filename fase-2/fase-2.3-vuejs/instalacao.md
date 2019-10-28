# Instalando o **Vue.js**

## Requisitos

Iremos instalar o Vue pelo CLI(interface de linha de comando) dele, e para isso é necessário ter o node e npm/yarn instalado, quando você instala o node, o npm é instalado junto.
Para [instalar o Vue CLI](https://cli.vuejs.org/guide/installation.html), execute o comando ```npm install -g @vue/cli```, teste a instalação utilizando ```vue -V```, se estiver tudo certo, irá retornar a versão instalada na sua maquina.

## Criando nosso projeto

Depois de instalado o Vue CLI, a criação de projetos é bem simples, navegue até a pasta desejada utilizando o terminal e digite "vue create" e o nome desejado do seu projeto, exemplo ```vue create meuProjeto```, irá ser criado uma pasta chamada meuProjeto e irá ser feito a instalação dentro desse diretório.

![Tela de instalação](https://cli.vuejs.org/cli-new-project.png)

Ao executar o comando vue create, selecione a opção default para criar nosso projeto e irá começar a instalação de todas as dependências e criação da estrutura básica do projeto.
Depois de finalizado, é só entrar na pasta do seu projeto e executar ```yarn serve``` ou ```npm run serve```, por padrão o projeto vai estar disponível na porta 8080 do localhost.

Agora o nosso projeto está instalado e configurado com tudo o que é necessário para começar a aprender como o Vue funciona e desenvolver nossas aplicações.