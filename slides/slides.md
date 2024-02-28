---
marp: true
theme: default
paginate: true
transition: none
---
<style>
    section {
        display: flex;
        justify-content: start;
    }
</style>

<style scoped>
    section {
        display: flex;
        justify-content: center;
    }
</style>

# Red-Black Ordering

Michael Souza

---

# Independent Set

Given an undirected graph $G=(V, E)$, an ***independent set*** $S\subset V$ is a set of vertices such that for every two vertices in $S$, there is no edge connecting them.

![bg right:30% height:80%](figures/example_sets.png)


# Maximal Independent Set

A ***maximal independent set*** is an independent set that is not a subset of any other independent set.

---
# Related Problems

### Maximum Independent Set Problem
The input is an undirected graph $G = (V, E)$ and the output is an undirected grap, and the out is a maximum independent set.

### Maximum Weighted Independent Set Problem
The input is an undirected graph with weights on the vertices, and the output is a maximum weight independent set.

---
# Related Problems

### Maximal Independent Set Listing Problem
The input is an undirected graph and the output is a list of ***all maximal independent sets***.

### Independent Set Decision Problem
The input is an undirected graph and a number $k$, and the output is a boolean value indicating whether there is an independent set of size $k$.

---
# Complexity

The maximum independent set

---
![bg height:80%](figures/boxplot_nRedEqs.png)

---
![bg height:80%](figures/boxplot_nBlocksRed.png)