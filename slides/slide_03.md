---
marp: true
theme: default
author: Michael Souza
footer: 'CC0443 - Seminários de Ciência de Dados'
math: mathjax
backgroundColor: #fff
paginate: true
style: |
  .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }
  .yellow-bg {
    background-color: #FFD700;
  }
---
# Seminários de Ciência de Dados

##### Universidade Federal do Ceará

*Prof. Michael Ferreira de Souza*
michael@ufc.br
(85) 99821 - 9955

![bg right:30% height:600px](slide_01/logo_QR.png)

---

# Índice de Rendimento Acadêmico (IRA)

---

### Cum Laude (C/ Honras)
Representa a terceira maior distinção e é o reconhecimento por obter alta qualificação em titulação universitária. 

No máximo 10 (dez) alunos por curso são 
agraciados anualmente.

![bg right:30% width:100%](figures/cum_laude.jpeg)

---

### Magna Cum Laude (C/ Grandes Honras) 
<br>
Representa a segunda maior distinção e é o reconhecimento por obter alta qualificação em titulação universitária. 

No máximo 4 (quatro) alunos por curso são agraciados anualmente.

![bg right:30% width:100%](figures/cum_laude.jpeg)

---

### Summa Cum Laude  (C/ a Maior das Honras) 
Representa a maior distinção e é o reconhecimento por obter a máxima qualificação possível em uma titulação universitária. 

No máximo 2 (dois) alunos por curso são agraciados anualmente.

![bg right:30% width:100%](figures/cum_laude.jpeg)

---

### Qual é a diferença entre IRA Geral e IRA Individual?

IRA Geral é o IRA calculado dentro do curso, ou seja, ele toma por base todos os alunos do próprio curso. IRA individual é o IRA do aluno calculado de acordo com o desempenho acadêmico dele.

---

### Como é calculado o IRA Geral?

$$IRA_{geral} = 6 + 2\left( \frac{ IRA - IRA_{m} }{ IRA_{dp} }\right),$$

calculado com três casas decimais.

**Observação:**
Depois do cálculo, limitamos $0\leq IRA_{geral} \leq 10$

---

### Como é calculado o IRA individual?

$$IRA = \left( 1 - \frac{0.5T}{C} \right) \times \left( \frac{\sum_i P_i\times C_i\times N_i}{\sum_i P_i\times C_i} \right) \times 1000,$$

$T$ = somatório de carga horária das disciplinas trancadas;
$C$ = somatório de carga horária das disciplinas cursadas ou trancadas;
$N_i$ = nota final da disciplina “$i$”;
$C_i$ = carga horária da disciplina “$i$”;
$P_i$ = período em que a disciplina “$i$” foi cursada, obedecendo à seguinte limitação: $P_i = \min${6, semestre em que a disciplina foi cursada}. Nas disciplinas anuais, será considerado o semestre de início delas.

---

### Onde posso olhar o meu IRA?
Você pode consultar o IRA no seu histórico.

### A matrícula institucional afeta o IRA?
Não, a matrícula institucional não afeta o IRA.

![bg right:30% width:100%](figures/search_document.webp)

---

### Se eu não fizer uma disciplina obrigatória do semestre que estou cursando, isso interfere no meu IRA?
Se você não se matricular, não tem problema. Se fizer a matrícula e logo após realizar o trancamento total, também não influencia. Mas se realizar o trancamento parcial, afetará o IRA.

### O trancamento parcial de matrícula afeta o IRA?
Sim, o trancamento parcial afeta o IRA.

### O trancamento total de matrícula afeta o IRA?
Não, o trancamento total não afeta o IRA.

---

### Cursar uma mesma disciplina mais de uma vez afeta o IRA?
Uma disciplina cursada mais de uma vez, no caso da existência de reprovação, será incluída no cálculo do IRA Individual o mesmo número de vezes em que ela consta no histórico do aluno.

---

### Reprovar uma disciplina por falta afeta o IRA?
Sim. A disciplina reprovada por freqüência terá nota final zero.

### O que afeta mais o IRA? Reprovação por falta ou por nota?
A reprovação por falta tem impacto negativo maior no IRA do que reprovação por nota.
 
![bg right:20% width:100%](figures/negative_trend.jpg)

---

### Como disciplinas aproveitadas influenciam no IRA?
Disciplinas inseridas no histórico por intermédio de aproveitamento, tanto interno como externo, não farão parte do cálculo do IRA Individual.

### E as Atividades complementares?
Atividades complementares de ensino não farão parte do cálculo do IRA Individual.

![bg right:20% width:100%](figures/negative_trend.jpg)

---

<!-- backgroundColor: orange -->
<!-- _color: black -->
# Dúvidas?
