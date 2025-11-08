# Questões Práticas 

1° Atividade de linguagem de script    
<br>

> [!NOTE]
> Perguntas e Respostas:

###### 1° O que é JSON e por que ele se tornou tão popular para troca de dados entre aplicações?
** JSON (JavaScript Object Notation) é um formato de troca de dados leve e fácil de ler/escrever. Ele se tornou popular devido à sua simplicidade e facilidade de uso em diferentes linguagens de programação.**


###### 2° Qual a diferença fundamental entre `JSON.stringify()` e `JSON.parse()`? Dê um exemplo prático de quando usar cada um.
**`JSON.stringify()`: Converte um objeto JavaScript para uma string JSON.
- `JSON.parse()`: Converte uma string JSON para um objeto JavaScript.**

```

// stringify
const obj = { nome: "Kaique", idade: 10 };
const jsonString = JSON.stringify(obj); // '{"nome":"Kaique","idade":10}'

// parse
const json = '{"nome":"Kaique","idade":10}';
const objParse = JSON.parse(json); // { nome: "Kaique", idade: 10 }


```

###### 3: Considerando a string "JavaScript é baseada em ECMA Script", quais métodos você usaria para:
- *Verificar se contém a palavra "Script"*: `includes()`
- *Remover a palavra "JavaScript"*: `replace()`
- *Substituir "baseada" por "tem origem"*: `replace()`

** **

> [!NOTE]
> CARACTERÍSTICAS-GERAIS:


##### -VANTAGENS:
**Funções anônimas, atribuição a variáveis ,possibilidade de autoexecução, não há elevação (hoisting).**

##### -DESVANTAGENS:
**Não é ultilizado para códigos grandes pela falta de estrutura, segurança e dificuldades no desenpenho.**


> [!TIP]
> CÓDIGO DE EXEMPLO:

```

const calcularArea = function(largura, altura) {
  return largura * altura;
};


const area = calcularArea(15, 2);
console.log(`A área é: ${area}`);

```

## ARROW:
**Tem como objetivo reduzir/responder códigos curto, deixa o código mais limpos e consequentemente aumentado a legibilidade, 
ultiliza o sinal "=>" para subistituir o (fuction).**


> [!TIP]
> CÓDIGO DE EXEMPLO:

```
 const cumprimentar = (sobrenome) => `Olá, ${sobrenome}!`;
    console.log(cumprimentar("sra.Guedes")); 
  ```  


> [!NOTE]
> CARACTERÍSTICAS-GERAIS:

##### -VANTAGENS:
**Retorno implícito, simplificação de callbacks , sintaxe concisa.**

##### -DESVANTAGENS:
**Falta do ```this``` (herdando ```this``` do escopo).**

> [!TIP]
> CÓDIGO DE EXEMPLO:

```
const soma = (U, P) => U+ P;

```
> [!IMPORTANT]
> CONCLUSÃO:

**Portanto pode-se conccluir que as funçoẽs tem como objetivo principal organizar em pequenos blocos para facilitar o gerênciamento do código,os quais estão sendo ultilizado. De modo, que as funções iram automatomatizar as tarefas.**



l
