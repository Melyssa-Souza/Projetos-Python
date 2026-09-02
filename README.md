# Trabalho: Métodos Numéricos e Cálculo de Raízes

Este notebook foca na implementação de algoritmos clássicos de cálculo numérico para a resolução de sistemas de equações lineares e busca de raízes de funções matemáticas.

**Algoritmos Implementados:**
* **Resolução de Sistemas Lineares:** Implementação de um método iterativo (similar ao de Jacobi) utilizando manipulação de matrizes e vetores, calculando a convergência até atingir uma taxa de tolerância/erro predefinida (0.01).
* **Método da Bisseção:** Busca de raízes para a função f(x) = x*log(x) - 1. O código avalia o comportamento da função dividindo o intervalo [a, b] iterativamente até isolar a raiz com precisão.
* **Método de Newton-Raphson:** Algoritmo avançado para localizar a raiz da função f(x) = e^x - 4x^2 utilizando o cálculo de derivadas numéricas (df(x)). A solução inclui a plotagem gráfica da convergência final da função.

**Bibliotecas e Ferramentas Utilizadas:**
* **NumPy:** Construção dos arrays multidimensionais, formatação do tipo double e cálculos matemáticos (exponencial e logaritmo).
* **Math:** Suporte para operações auxiliares de valor absoluto (fabs).
* **Matplotlib (Pyplot):** Geração da representação gráfica em linha da função analisada no último método.
