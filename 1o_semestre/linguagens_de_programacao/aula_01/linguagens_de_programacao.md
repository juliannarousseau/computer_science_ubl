# Conceitos de Linguagens de Programação

## Conteúdo

- Razões para estudar conceitos de linguagens de programação  
- Domínios de programação  
- Critérios para avaliação de linguagens  
- Influências no projeto de linguagens  
- Categorias de linguagens  
- Métodos de implementação  

---

## Razões para estudar conceitos de linguagens de programação

Estudar conceitos de linguagens de programação traz diversos benefícios:

- **Aumentar a capacidade de expressar ideias**
- **Melhorar a escolha da linguagem adequada para cada problema**
- **Aumentar a capacidade de aprender novas linguagens**
- **Melhorar o uso das linguagens já conhecidas**
- **Entender a importância da implementação**
- **Contribuir para o avanço da área de computação**

---

## Por que existem tantas linguagens?

Existem muitas linguagens de programação como **C, Java, Python e JavaScript**.  
À primeira vista, isso pode parecer um **labirinto sem fim**.

Isso acontece porque **programar não é apenas decorar palavras-chave**, mas aprender **conceitos e formas de resolver problemas**.

Quando entendemos conceitos fundamentais como:

- **Funções**
- **Classes**
- **Variáveis**

fica muito mais fácil aprender novas linguagens.

O que muda normalmente é apenas **a sintaxe**, ou seja, a forma de escrever.

### Analogia com idiomas

Aprendemos que:

- **Cachorro** em português  
- **Dog** em inglês  
- **Perro** em espanhol  

representam o **mesmo conceito**, apenas com palavras diferentes.

Em programação acontece algo parecido:

- `int`
- `def`
- `public`

são apenas formas diferentes de expressar **conceitos semelhantes**.

**O conhecimento real está nos conceitos por trás da sintaxe.**

---

## Domínios de programação

As linguagens de programação surgiram para resolver **tipos específicos de problemas**.

Podemos pensar nelas como **ferramentas em uma caixa de ferramentas**.

Cada domínio da computação possui necessidades diferentes.

### Evolução histórica

#### Anos 50
Aplicações científicas e militares exigiam **cálculos complexos**.

#### Anos 60
Bancos e comércio precisavam de **relatórios e cálculos decimais**.

#### Anos 70
Sistemas operacionais exigiam **eficiência e controle de baixo nível**.

#### Anos 90
A web trouxe a necessidade de **manipulação de texto e comunicação em rede**.

---

### Exemplos de domínios

| Domínio | Linguagem | Característica principal |
|--------|--------|--------|
| Científico | FORTRAN | Arrays e matrizes |
| Negócios | COBOL | Relatórios e formatação |
| Sistemas | C | Eficiência e controle |
| Web | JavaScript | Manipulação de strings |

---

## Critérios para avaliação de linguagens

Podemos avaliar linguagens de programação usando **quatro critérios principais**:

1. **Legibilidade**
2. **Escrita (writability)**
3. **Confiabilidade**
4. **Custo total**

---

### Legibilidade

A **legibilidade** é a facilidade de **ler e entender um programa**.

Código legível:

- possui menos erros
- é mais fácil de manter
- reduz custos de manutenção

#### Ortogonalidade

Um conceito importante dentro da legibilidade é a **ortogonalidade**.

Isso significa que os elementos da linguagem devem ser **consistentes e previsíveis**.

Exemplo simples:

- `1 + 1` sempre resulta em **2**

Por outro lado, algumas operações podem gerar comportamentos inesperados.

Exemplo:

- operações com **ponteiros em C** podem ser difíceis de prever.

---

### Escrita (Writability)

A **escrita** é a facilidade de **usar uma linguagem para criar programas**.

Ela é influenciada principalmente por:

- **abstração**
- **expressividade**

Ou seja:

> quão fácil é transformar uma ideia complexa em código?

Uma linguagem com boa escrita **permite focar no problema**, e não na complexidade da linguagem.

Exemplo:

Multiplicar matrizes em **C** pode exigir várias linhas e loops.  
Em **Python**, pode ser feito **em apenas uma linha**.

---

### Confiabilidade

A **confiabilidade** é a capacidade de um programa **funcionar conforme especificado**.

Uma forma importante de aumentar a confiabilidade é a **verificação de tipos**.

Ela funciona como uma **rede de segurança**, impedindo erros como:

- somar um **número** com uma **string**

Esses erros podem ser detectados **antes da execução do programa**.

---

### Custo

O **custo** envolve o impacto econômico total do uso de uma linguagem.

Inclui fatores como:

- treinamento da equipe
- tempo de compilação
- desempenho de execução
- manutenção do sistema

Ou seja, não se trata apenas de **velocidade de execução**.

Também envolve perguntas como:

- Quanto custa treinar novos desenvolvedores?
- Quanto custará manter o sistema daqui a **5 ou 10 anos**?

---

## Influências no projeto de linguagens

O projeto de uma linguagem de programação é influenciado por diversos fatores, como:

- **domínio de aplicação**
- **paradigmas de programação**
- **tecnologia disponível na época**
- **necessidades da indústria**

Por exemplo:

- linguagens de sistemas priorizam **eficiência**
- linguagens científicas priorizam **operações matemáticas**
- linguagens modernas priorizam **produtividade**

---

## Categorias de linguagens

As linguagens de programação podem ser classificadas em diferentes categorias.

Algumas das principais são:

- **Linguagens imperativas**
- **Linguagens orientadas a objetos**
- **Linguagens funcionais**
- **Linguagens lógicas**

Cada categoria possui **formas diferentes de estruturar programas**.

---

## Métodos de implementação

As linguagens podem ser implementadas de diferentes maneiras.

As principais são:

### Compilação

O código é traduzido completamente para **código de máquina** antes da execução.

Exemplo: **C**

---

### Interpretação

O código é executado **linha por linha por um interpretador**.

Exemplo: **Python**

---

### Implementação híbrida

Combina **compilação e interpretação**.

Exemplo: **Java**

O código é compilado para **bytecode**, que depois é executado pela **máquina virtual (JVM)**.

---

## A linguagem certa para o problema certo

Cada linguagem faz **trocas de design** entre diferentes características.

### Exemplos

**Java**

- prioriza **confiabilidade**
- código mais **verboso**

**Python**

- prioriza **facilidade de escrita**
- menor desempenho de execução

Não existe linguagem perfeita.

Cada uma representa **uma escolha de design**.

O objetivo não é encontrar **a melhor linguagem**, mas sim **a melhor ferramenta para o problema específico**.

A pergunta correta não é:

> "Essa linguagem é boa?"

Mas sim:

> **"Qual problema essa linguagem resolve melhor?"**