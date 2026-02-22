# Lógica Proposicional (também chamada de lógica sentencial)

## Proposições e valores lógicos

Uma **proposição** é uma sentença declarativa que é **verdadeira ou falsa**.

### Exemplos de proposições

1. O morcego é um mamífero.  
2. Rio de Janeiro é a capital do Brasil.  
3. Há 36 macacos no zoológico de Londres.  
4. A taxa de juros do Banco Central vai subir amanhã.  
5. O trilionésimo algarismo decimal de π é 7.  

> Não é necessário saber se a sentença é verdadeira ou falsa no momento.

Isso pode depender de:

- Informações desconhecidas  
- Eventos futuros  
- Cálculos inviáveis  

---

### Frases que NÃO são proposições

- Interrogativas → “O que é isto?”  
- Imperativas → “Leia com cuidado”  
- Auto-referentes → “Esta frase é falsa”  

---

### Proposições com variáveis

Uma sentença com variáveis **não é proposição isoladamente**, mas torna-se uma quando a variável recebe valor.

Exemplo:

- “x é menor que 3” → não é proposição  
- Se x = 2 → torna-se proposição (verdadeira)

---

### Valor lógico

O **valor lógico (ou valor-verdade)** de uma proposição pode ser:

- **V** → Verdadeiro  
- **F** → Falso  

---

## Conectivos lógicos e proposições compostas

Línguas naturais possuem conectivos que permitem formar proposições complexas:

- e  
- ou  
- não  
- se... então  

### Exemplos

1. [Brasília é a capital do Brasil] **e** [Montevidéu é a capital da Argentina]  
2. [Brasília é a capital do Brasil] **ou** [Montevidéu é a capital da Argentina]  
3. **Se** [a taxa de juros cair amanhã], **então** [a inflação aumentará]  
4. **Não** [haverá sessão da meia-noite hoje]  

---

### Proposição simples (atômica)

Não pode ser dividida em proposições menores.

O valor lógico de uma proposição composta depende:

- Dos valores das proposições simples  
- Do conectivo usado  

Exemplo:

- “Brasília é a capital do Brasil” → V  
- “Montevidéu é a capital da Argentina” → F  

Então:

- Conjunção → F  
- Disjunção → V  

---

## Notação do cálculo proposicional

Para evitar ambiguidades da linguagem natural, usa-se uma notação formal.

### Representação

- Proposições → letras minúsculas: **p, q, r...**  
- Valores → **V** ou **F**  
- Conectivos → operadores lógicos  

---

### Principais operadores

- **Conjunção:** p ∧ q → “p e q”  
- **Disjunção:** p ∨ q → “p ou q”  
- **Negação:** ¬p → “não p”  
- **Implicação:** p → q → “se p então q”  
- **Equivalência:** p ↔ q → “p se e somente se q”  

---

## Operador de Conjunção (∧)

“p e q” é verdadeiro apenas se **p e q forem verdadeiros**.

### Tabela-verdade

| p | q | p ∧ q |
|---|---|-------|
| V | V |   V   |
| V | F |   F   |
| F | V |   F   |
| F | F |   F   |

### Exemplo

“José compra tijolos e vende casas”

> Nem todo “e” do português é conjunção lógica.

Exemplo:

“Maria gosta de arroz e feijão” → não é duas proposições separadas.

---

## Operador de Disjunção (∨)

“p ou q” é verdadeiro se **pelo menos uma for verdadeira**.

### Tabela-verdade

| p | q | p ∨ q |
|---|---|-------|
| V | V |   V   |
| V | F |   V   |
| F | V |   V   |
| F | F |   F   |

Este é o **ou inclusivo**.

### Exemplo

“O cliente tem celular ou laptop”

Verdadeiro se:

- Tem apenas celular  
- Apenas laptop  
- Ambos  

---

## Operador de Negação (¬)

Produz uma proposição com valor lógico oposto.

### Tabela-verdade

| p | ¬p |
|---|----|
| V | F  |
| F | V  |

### Exemplo

“A casa é de qualquer cor menos branca”

→ ¬(A casa é branca)

---

## Proposições viáveis

Uma proposição composta é **viável** se existe alguma atribuição de valores que a torna verdadeira.

### Exercícios

Verifique quais são viáveis:

a)  
(p ∨ q ∨ ¬r) ∧ (p ∨ ¬q ∨ ¬s) ∧ (p ∨ ¬r ∨ ¬s) ∧ (¬p ∨ ¬q ∨ ¬s) ∧ (p ∨ q ∨ ¬s)

b)  
(¬p ∨ ¬q ∨ r) ∧ (¬p ∨ q ∨ ¬s) ∧ (p ∨ ¬q ∨ ¬s) ∧ (¬p ∨ ¬r ∨ ¬s) ∧ (p ∨ q ∨ ¬r) ∧ (p ∨ ¬r ∨ ¬s)

c)  
(p ∨ q ∨ r) ∧ (p ∨ ¬q ∨ ¬s) ∧ (q ∨ ¬r ∨ s) ∧ (¬p ∨ r ∨ s) ∧ (p ∨ q ∨ ¬s) ∧ (p ∨ ¬q ∨ ¬r) ∧ (¬p ∨ ¬q ∨ s) ∧ (¬p ∨ ¬r ∨ ¬s)

---

## Operador de Implicação (→)

“Se p então q”

É falso apenas quando:

- p = verdadeiro  
- q = falso  

Nos demais casos → verdadeiro.

### Tabela-verdade

| p | q | p → q |
|---|---|-------|
| V | V |   V   |
| V | F |   F   |
| F | V |   V   |
| F | F |   V   |

---

### Observação importante

A implicação lógica **não exige relação causal**.

Exemplo:

“Se 2 é par então Brasília é a capital do Brasil” → verdadeiro.

---

### Exemplo

“Se José foi para casa, ele perdeu a reunião”

→ (José foi para casa) → (José perdeu a reunião)

---

## Interpretações equivalentes

Em português, p → q pode aparecer como:

- Se p, então q  
- Caso p, vale q  
- q segue de p  
- p implica q  
- q sempre que p  

---

## Termos importantes

- **p → q** → implicação  
- **q → p** → recíproca  
- **¬p → ¬q** → inversa  
- **¬q → ¬p** → contrapositiva  

A contrapositiva sempre tem o mesmo valor lógico de p → q.

---

## Forma contrapositiva

p → q ≡ ¬q → ¬p

Pode ser expressa como:

- Se não q, então não p  
- q é condição necessária para p  
- p é falsa sempre que q é falsa  

---

## Exercícios

Encontre:

a) A contrapositiva de ¬p → q  
b) A recíproca de ¬q → ¬p  
c) A inversa da recíproca de q → ¬p  
d) A negação de p → ¬q  
e) A recíproca de ¬p ∨ q  
