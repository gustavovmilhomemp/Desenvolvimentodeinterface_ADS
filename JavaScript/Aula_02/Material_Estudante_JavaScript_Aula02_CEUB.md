# DESENVOLVIMENTO DE INTERFACE ![Logomarca CEUB](logo-ceub-colorida\(10\).png)

# Módulo JavaScript — Aula 2
## Entrada de dados, manipulação do DOM e estruturas condicionais

**Material do estudante | ADS | Profa. Kadidja Valéria | CEUB**  
**Modalidade:** laboratório prático · **Duração:** 2h30 · **Pré-requisitos:** Aula 1 (variáveis, tipos e operadores).

---

## 1. Objetivos

Ao final da aula, você deverá ler valores digitados em uma interface HTML, converter dados, capturar cliques, validar campos, usar `if`, `else if` e `else` e apresentar mensagens ao usuário.

---

## 2. Roteiro de estudo (150 minutos)

| Etapa | Tempo |
| :--- | ---: |
| Revisão e preparação | 15 min |
| Entrada de dados e DOM | 25 min |
| Eventos e conversão | 25 min |
| Condicionais e validação | 30 min |
| Laboratórios | 40 min |
| Testes e entrega | 15 min |

---

## 3. Conceitos essenciais

* **DOM (Document Object Model)** é a representação da página que JavaScript consegue acessar e modificar.
* `document.getElementById("nome")` localiza um elemento pelo seu ID.
* `.value` lê o valor atual de um campo, que normalmente é uma string, mesmo quando o input tem `type="number"`.
* `Number()` converte a entrada para número.
* `addEventListener("click", ...)` executa uma função quando o botão é clicado.
* `textContent` apresenta mensagens de texto na página.

```javascript
const texto = document.getElementById("idade").value;
const idade = Number(texto);

console.log(typeof texto); // string
console.log(typeof idade); // number
