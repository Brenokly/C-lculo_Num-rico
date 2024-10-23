# Cálculo Numérico 📊

## Sobre o Projeto

Este repositório contém implementações de métodos numéricos para resolver problemas matemáticos e de engenharia/computação. Os métodos abordados são amplamente utilizados na resolução de problemas complexos, proporcionando soluções precisas e eficientes. Cada unidade do curso é representada por um pacote separado, facilitando a organização e o entendimento das diferentes abordagens numéricas.

## Conteúdo Programático

### Unidade I: Zeros de Funções Reais 🔍

- **Sistemas de Numeração**: Decimal, binário, octal e hexadecimal. Conversão entre bases. Sistemas de ponto flutuante.
- **Erros**: Tipos, modelagem, erro na fase de resolução (conversão entre bases e representação numérica), erro absoluto, erro relativo e propagação de erros.
- **Zeros de Funções Reais**: Isolamento de raízes, refinamento, critérios de parada.
  - **Métodos**:
    - Bissecção
    - Falsa Posição
    - Ponto Fixo
    - Newton-Raphson
    - Secante

### Unidade II: Resolução de Sistemas Lineares ⚖️

- **Métodos Diretos**: Decomposição LU, Determinante, Método de Cholesky, Método Gaussiano.
- **Métodos Iterativos**: Método de Gauss-Jacobi, Método de Gauss-Seidel.
- **Número de Condicionamento**: Avaliação da sensibilidade de um sistema linear às mudanças nos dados de entrada.

### Unidade III: Aproximação de Funções e Integração Numérica ✏️

- **Aproximação de Funções**: Método dos Mínimos Quadrados, aproximações linear, polinomial, potência, exponencial e logarítmica.
- **Integração Numérica**: Soma de Riemann, Regra do Trapézio, Regra de Simpson 1/3, Regra de Simpson 3/8, e erros limitantes na integração numérica.
- **Solução Numérica de EDO**: Problema de Valor Inicial, Método de Euler, Métodos de Runge-Kutta (2ª e 4ª ordens), Método de Lagrange e Método de Newton.

## Métodos Implementados

### 1. Método da Bissecção 🔪

Técnica que busca encontrar a raiz de uma função contínua dividindo um intervalo e escolhendo o subintervalo onde a função muda de sinal.

### 2. Método da Falsa Posição ⚖️

Utiliza interpolação linear para encontrar uma nova aproximação para a raiz baseada na interseção da linha que conecta os pontos finais do intervalo.

### 3. Método da Secante ✏️

Calcula novas aproximações a partir de duas aproximações iniciais, sem requerer que a função seja contínua.

### 4. Método de Newton 🚀

Utiliza a derivada da função para iterar a partir de uma aproximação inicial, convergindo rapidamente.

### 5. Método do Ponto Fixo 🔄

Reformula a função na forma \( x = g(x) \) e itera a partir de uma aproximação inicial.

### 6. Decomposição LU 🔍

Método que decompõe uma matriz em duas matrizes triangulares, facilitando a resolução de sistemas lineares.

### 7. Método de Cholesky 🛠️

Um caso especial de decomposição LU que é usado para matrizes simétricas e definidas positivas.

### 8. Método de Gaussiano ⚖️

Utiliza operações elementares em linhas para transformar a matriz do sistema linear em uma forma escalonada.

### 9. Método de Gauss-Jacobi 🌀

Um método iterativo que usa aproximações anteriores para calcular novas soluções.

### 10. Método de Gauss-Seidel 🔄

Uma variante do método de Gauss-Jacobi que atualiza as soluções imediatamente após calcular uma nova aproximação.

### 11. Método de Euler ⏱️

Usado para resolver equações diferenciais ordinárias, aproximando a solução ao longo de pequenos passos.

### 12. Métodos de Runge-Kutta 📈

Técnicas mais avançadas para resolver EDOs, oferecendo maior precisão do que o método de Euler.

### 13. Método de Lagrange 📊

Usa a interpolação polinomial para encontrar valores de uma função em pontos não conhecidos, com base em valores conhecidos.

### 14. Método de Newton 📈

Uma técnica de interpolação que utiliza derivadas para encontrar uma aproximação de uma função em um ponto.

### 15. Regra do Trapézio 📊

Método simples para aproximação de integrais, calculando a área sob a curva como uma série de trapézios.

### 16. Regras de Simpson 1/3 e 3/8 📉

Métodos de integração numérica que oferecem maior precisão ao usar polinômios de grau 2 e 3, respectivamente.

### 17. Cálculo do Determinante 🔍

Algoritmo que calcula o determinante de uma matriz, essencial para determinar a inversibilidade da matriz e propriedades de sistemas lineares.

### 18. Cálculo de Condicionamento 🔄

Avaliação da estabilidade de um sistema linear, medindo como pequenas mudanças nas entradas podem afetar a solução.

### 19. Soma de Riemann 📈

Utiliza divisões em subintervalos para aproximar a integral de uma função, servindo como uma base para outros métodos de integração.

## Instalação e Uso

Para usar os métodos, clone o repositório e navegue até o diretório do projeto:

```bash
git clone https://github.com/seu-usuario/Cálculo_Numérico.git
cd Cálculo_Numérico
```

Cada pacote contém suas respectivas implementações e exemplos de uso.

## Referências Bibliográficas 📚

- Franco, N. Bertoldi. *Cálculo Numérico*. Pearson Prentice Hall, 2006. ISBN: 978-85-7605-087-2.
- Burden, R. L. *Análise Numérica*. Cengage Learning, 2015. ISBN: 978-85-221-2340-7.
- Ruggiero, M. A. Gomes. *Cálculo Numérico: Aspectos Teóricos e Computacionais*. 2. ed. Pearson Makron Books, 1996. ISBN: 978-85-346-0204-4.

## Agradecimentos 🙏

Agradeço a todos, principalmente ao professor [Paulo César] que contribuíram para o aprendizado nesta disciplina de Cálculo Numérico e pela oportunidade de explorar esses métodos valiosos!
