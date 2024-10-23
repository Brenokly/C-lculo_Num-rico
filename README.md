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

- **Métodos Diretos**: Eliminação de Gauss e Fatoração LU.
- **Métodos Iterativos**: Método de Gauss-Jacobi e Gauss-Seidel.
- **Interpolação**: Polinomial, Interpolação Linear, Fórmulas Interpolatórias de Lagrange e Newton, Interpolação Inversa.

### Unidade III: Aproximação de Funções e Integração Numérica ✏️

- **Aproximação de Funções**: Método dos Mínimos Quadrados, aproximações linear, polinomial, potência, exponencial e logarítmica.
- **Integração Numérica**: Fórmulas de Newton-Cotes, Regra dos Trapézios, 1/3 de Simpson, 3/8 de Simpson e erros limitantes na integração numérica.
- **Solução Numérica de EDO**: Problema de Valor Inicial, Método de Euler.

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

Agradeço a todos que contribuíram para o aprendizado nesta disciplina de Cálculo Numérico e pela oportunidade de explorar esses métodos valiosos!
