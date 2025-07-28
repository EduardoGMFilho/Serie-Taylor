# Série de Taylor

Este projeto implementa, em Python, a aproximação de funções matemáticas utilizando a **Série de Taylor**. A ideia principal é ilustrar como a expansão em série pode aproximar funções reais a partir de polinômios, utilizando bibliotecas como `NumPy` e `Matplotlib` para os cálculos e visualizações.

## 📌 Objetivos

- Aproximar funções reais com a Série de Taylor;
- Visualizar graficamente o comportamento da aproximação;
- Avaliar a convergência da série em diferentes ordens (graus dos polinômios).

## 🧠 Conceitos Envolvidos

A Série de Taylor é uma forma de representar funções suaves como somas infinitas de termos derivados de uma função em um ponto específico. A fórmula geral é:

$$
f(x) \approx \sum_{n=0}^{N} \frac{f^{(n)}(a)}{n!} (x - a)^n
$$

Neste programa:
- `f(x)` é a função que será aproximada;
- `a` é o ponto de expansão (geralmente 0, a Série de Maclaurin);
- `N` é o grau da aproximação (número de termos).

## 📊 Demonstração

O script plota a função original junto com suas aproximações por polinômios de Taylor de diferentes ordens, para facilitar a visualização da convergência.



## 🛠️ Tecnologias Utilizadas

- [Python 3](https://www.python.org/)
- [NumPy](https://numpy.org/) – para cálculos matemáticos e diferenciação
- [Matplotlib](https://matplotlib.org/) – para gráficos e visualizações

## ▶️ Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/serie-de-taylor.git
