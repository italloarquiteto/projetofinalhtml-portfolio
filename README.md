# **TAREFA METODOLOGIA DENTRO DO CSS** (A metodologia escolhida foi a B.E.M)

### Metodologia **B.E.M** (Block Element Modifier)
#### A **BEM** é uma metodologia usada para criar CSS escalável e modular, promovendo organização e clareza. Ela divide o código em três partes principais:
- IBloco (Block): É uma unidade independente, como componentes reutilizáveis (ex.: card ou button).
- Elemento (Element): Parte de um bloco que não pode existir sem ele, identificada com __ (ex.: card__image).
- Modificador (Modifier): Define variações ou estados de um bloco ou elemento, usando -- (ex.: card--dark ou card__image--large).
---

### Metodologia **S.M.A.C.S.S** (Scalable and Modular Architecture for CSS)
#### **SMACSS** é uma abordagem modular e escalável que organiza CSS em cinco categorias principais:

- Base: Define os estilos padrões como resets e regras gerais para HTML.
- Layout: Foca em dividir a estrutura geral do site em seções, como cabeçalhos e rodapés.
- Módulos: Componentes reutilizáveis independentes, como botões ou carrosséis.
Estados: Regras que definem variações de um componente, como estados hover, active ou is-hidden.
- Temas: Estilos específicos que alteram a aparência geral, como paletas de cores.
---
> Aqui estão dois exemplos simples para demonstrar as metodologias BEM e SMACSS, lado a lado:

### **BEM**
#### HTML:
<pre>
<code>
&lt;div class="card card--dark"&gt;
  &lt;h2 class="card__title"&gt;Título&lt;/h2&gt;
  &lt;p class="card__description"&gt;Descrição do conteúdo.&lt;/p&gt;
&lt;/div&gt;
</code>
</pre>

#### CSS:
<pre>
<code>
.card {
  background: white;
  color: black;
  padding: 10px;
}

.card--dark {
  background: black;
  color: white;
}

.card__title {
  font-size: 1.5rem;
}

.card__description {
  font-size: 1rem;
}
</code>
</pre>

---

### **SMACSS**
#### HTML:
<pre>
<code>
&lt;div class="module card theme-dark"&gt;
   &lt;h2 class="module__title"&gt;Título&lt/h2&gt;
    &lt;p class="module__content"&gt;Descrição do conteúdo.&lt;/p&gt;
&lt;/div&gt;
</code>
</pre>

#### CSS:
<pre>
<code>
/* Base */
body {
  font-family: Arial, sans-serif;
}

/* Module */
.module {
  padding: 10px;
}

.module__title {
  font-size: 1.5rem;
}

.module__content {
  font-size: 1rem;
}

/* Theme */
.theme-dark {
  background: black;
  color: white;
}
</pre>
</code>

> 
---
---
---
---
---
---
---
---
---
---
---
--- 
---
---
---
---
---


EXEMPLO DE MARCAÇÃO MARKDOWN

<!-- Cabeçalhos -->
# Cabeçalho de nível 1
## Cabeçalho de nível 2
### Cabeçalho de nível 3
#### Cabeçalho de nível 4
##### Cabeçalho de nível 5
###### Cabeçalho de nível 6

<!-- Ênfase -->
**Texto em negrito**

<!-- Listas -->
- Item 1
- Item 2
- Item 3

<!-- Listas ordenadas -->
1. Primeiro item
2. Segundo item
3. Terceiro item

<!-- Blocos de Citação -->
> Este é um bloco de citação.

<!-- Blocos de código -->
```javascript
function hello() {
    console.log("Hello, world!");
}