# Trabalhando com estado

## Reatividade com o data

No Vue nós temos algo que seria o estado do componente, é um objeto onde você pode definir propriedades, e essas propriedades são reativas, assim, quando você alterar o valor dessas propriedades, todos os lugares que estiverem as utilizando, irão reagir a mudança e fazendo assim a reatividade no nosso componente.

## Definindo nosso data

Nós já temos a aplicação padrão do Vue CLI, então vamos alterar o componente HelloWorld que está dentro do diretório src/components, vamos tirar todas as coisas que não estamos utilizando no momento e deixar o componente mais simples possível, vai ficar mais ou menos assim:

```
<template>
  <div>
    <h1>Hello World</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>
```

Partindo desse ponto, vamos adicionar o data com uma propriedade:

```
<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      mensagem: ''
    }
  }
}
</script>
```

E reproduzir essa mensagem dentro do template do nosso componente:

```
<template>
  <div>
    <h1>Hello World</h1>
    <p>Minha mensagem é: {{ mensagem }}</p>
  </div>
</template>
```

Pronto, nosso componente está utilizando uma propriedade reativa, se você alterar o valor para ```mensagem: 'Minha frase'```, irá ser mostrado no nosso componente, mas ainda não estamos utilizando da reatividade, para isso vamos adicionar um input acima da tag p com nossa mensagem para alterar o valor da nossa propriedade reativa e alterar no nosso template ao mesmo tempo:

```
<div>
  <input 
    type="text"
    placeholder="Digite uma mensagem"
    v-model="mensagem"
  >
</div>
```

Acima estamos utilizando uma diretiva chamada v-model, que vai ser detalhada ela e outras nos próximos tópicos, mas basicamente ela recebe o valor de uma propriedade e seta no input, e quando o input for alterado, ela seta o valor na propriedade dentro do nosso data. Agora está finalizado o nosso exemplo, se você digitar no input, vai ser alterado no template o resultado da mensagem, o código completo do nosso exemplo fica assim no final:

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
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      mensagem: ''
    }
  }
}
</script>
```
