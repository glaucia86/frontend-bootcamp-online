# Diretivas

## O que são diretivas?

Diretivas é algo como um atributo que você coloca na sua tag do seu HTML ou componente e o Vue irá identificar isso e tratar na manipulação do seu DOM, facilitando assim a manipulação dos seus dados dentro do template. Vamos aprender as diretivas mais comuns do Vue.

Para validações de condições, temos ```v-if, v-else e v-else-if```

```
<div v-if="condicao > 0">
  O valor de ```condicao``` é maior que 0
</div>
<div v-else-if="condicao < 0">
  O valor de ```condicao``` é menor que 0
</div>
<div v-else>
  O valor de ```condicao``` não é verdadeiro para nenhuma condição acima
</div>
```
Se definirmos uma propriedade chamada ```condicao``` no nosso data, com o código acima irá fazer a validação se é maior que 0, menor que 0 e se não é nenhuma dessas condições.

Para iterações, temos o ```v-for```, geralmente utilizamos para iterar array ou objeto, mas também aceita outros tipos.

```
<div 
  v-for="(item, key) in items" 
  :key="key"
>
  {{ item }}
</div>
...
items: ['a', 'b', 'c', 'd']
```
Nesse caso podemos definir um array de nome itens no nosso data, e iteramos ele no nosso template, o primeiro campo extraído é o valor e o segundo é a posição no array, se fosse um objeto, o segundo seria o nome da chave no objeto.

Para colocar e receber um valor de um campo de input, select, textarea, podemos utilizar o ```v-model```, que já foi utilizado no nosso projeto, quando ele já tem valor, isso é setado para o elemento e quando alteramos no elemento, é alterado também na nossa variável, isso é chamado de two-way binding. Podemos utilizar v-model em componentes, mas é assunto para depois da fase de adaptação com o Vue.

Podemos trabalhar com eventos de click, change, submit e outros utilizando o ```v-on```.

```
<button v-on:click="minhaFuncao">
  Chamar minha função no click
</button>
...
methods: {
  minhaFuncao () {
    alert('minha função foi chamada')
  }
}
```
Acima temos um exemplo de click em um botão que chama uma função no nosso componente.

Essas são apenas algumas das diretivas do Vue, na [documentação](https://vuejs.org/v2/api/#Directives) tem muito mais, mais detalhadas e com exemplos. O código final do nosso componente de exemplo ficou assim:

```
<template>
  <div>
    <h1>Hello World</h1>
    <div>
      <input 
        type="text"
        placeholder="Digite uma mensagem"
        v-model="mensagem"
      >
    </div>
    <p>Minha mensagem é: {{ mensagem }}</p>
    <div v-if="condicao > 0">
      O valor de ```condicao``` é maior que 0
    </div>
    <div v-else-if="condicao < 0">
      O valor de ```condicao``` é menor que 0
    </div>
    <div v-else>
      O valor de ```condicao``` não é verdadeiro para nenhuma condição acima
    </div>

    <div 
      v-for="(item, key) in items" 
      :key="key"
    >
      {{ item }}
    </div>

    <button v-on:click="minhaFuncao">
      Chamar minha função no click
    </button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      mensagem: '',
      condicao: 0,
      items: ['a', 'b', 'c', 'd']
    }
  },
  methods: {
    minhaFuncao () {
      alert('minha função foi chamada')
    }
  }
}
</script>
```
