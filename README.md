# Questões Práticas 

1° Atividade de linguagem de script    
<br>

> [!NOTE]
> Perguntas e Respostas:

### 1° O que é JSON e por que ele se tornou tão popular para troca de dados entre aplicações?

**JSON (JavaScript Object Notation) é um formato de troca de dados leve e fácil de ler/escrever. Ele é amplamente utilizado para trocar dados entre aplicações, especialmente em ambientes web e se tornou popular devido à sua simplicidade e facilidade de uso em diferentes linguagens de programação.**


### 2° Qual a diferença fundamental entre `JSON.stringify()` e `JSON.parse()`? Dê um exemplo prático de quando usar cada um.
**`JSON.stringify()`: Converte um objeto JavaScript para uma string JSON.**
**`JSON.parse()`: Converte uma string JSON para um objeto JavaScript.**

```

// stringify
const obj = { nome: "Kaique", idade: 10 };
const jsonString = JSON.stringify(obj); // '{"nome":"Kaique","idade":10}'

// parse
const json = '{"nome":"Kaique","idade":10}';
const objParse = JSON.parse(json); // { nome: "Kaique", idade: 10 }


```

### 3°: Considerando a string "JavaScript é baseada em ECMA Script", quais métodos você usaria para:
  -Verificar se contém a palavra "Script"*: `includes()`
  -Remover a palavra "JavaScript"*: `replace()`
  -Substituir "baseada" por "tem origem"*: `replace()`
```
const str = "JavaScript é baseada em ECMA Script";

console.log(str.includes("Script")); // true
console.log(str.replace("JavaScript", "")); // " é baseada em ECMA Script"
console.log(str.replace("baseada", "tem origem")); // "JavaScript é tem origem em ECMA Script"

```
### 4°: Qual a vantagem de usar template strings (``) em vez de concatenação com + para criar strings complexas?
**A vantagem é que template strings permitem uma sintaxe mais clara, legível e menos erros, para strings complexas com variáveis.**

> [!NOTE]
> CÓDIGO EXEMPLO:
```
const nome = "Kaique";
const idade = 10;

// Concatenação
const str1 = "Olá, " + nome + " tem " + idade + " anos.";

// Template string
const str2 = `Olá, ${nome} tem ${idade} anos.`;
```
