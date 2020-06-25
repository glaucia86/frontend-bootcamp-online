# Métodos

## Meus primeiros métodos

Métodos no Vue são as nossas funções/rotinas, usamos métodos para separar lógica dentro do componente para seus devidos fins, para se criar nossas funções em um componente Vue, temos a chave ```methods``` dentro do nosso script. O ```this``` dentro dos métodos tem o [contexto da instância Vue](https://br.vuejs.org/v2/api/#methods).
Já criamos um método na parte anterior, vamos modificar para alterar nosso data do componente.

Vamos fazer o seguinte, pela nossa função, vamos adicionar uma string para o nosso input, alterar a o valor da condição e alterar nosso array de items que estão sendo renderizados. Iremos acessar o data usando o ```this```, colocamos um ```.``` e atribuimos valor com um ```=``` para cada item do data.

A nossa função vai ficar assim

```
minhaFuncao () {
  this.mensagem = 'Mensagem setada pela minha função'
  this.condicao = -1
  this.items = ['Javascript', 'Vue', '!JQuery']
}
```

Métodos são fundamentais no Vue, e podem ser chamados de diversas formas dentro do nosso componente, por eventos de clique(como o que tem no nosso componente), por outros métodos, nos [eventos do ciclo de vida](https://br.vuejs.org/v2/guide/instance.html#Ciclo-de-Vida-da-Instancia) da aplicação, etc.