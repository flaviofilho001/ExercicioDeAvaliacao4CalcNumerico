Aluno: Flávio Mesquita Marinho Filho
Matrícula: 20230146390

## Os códigos estão disponibilizados aqui no github, foram feitos no jupyter notebook e na linguagem python.

# Exercicio 04 de Avaliação

Este relatório apresenta a resolução de três questões sobre equações diferenciais ordinárias utilizando métodos numéricos. As resoluções são feitas em Python com a utilização dos métodos de Euler e Runge-Kutta para aproximações numéricas.

## Questão 01

### Enunciado

Usando os métodos de Euler e Runge-Kutta de 3ª ordem com \( h = 0.2 \), calcule \( y(1) \), sabendo que \( y(x) \) é a solução da equação diferencial:

\[
y' = f(x, y)
\]

Sabendo que a solução exata do problema de valor inicial (PVI) é fornecida, calcule para os dois métodos o erro absoluto cometido na aproximação de \( y(1) \).

### Solução

A equação diferencial foi resolvida utilizando os métodos de Euler e Runge-Kutta de 3ª ordem, com um passo \( h = 0.2 \). Os códigos utilizados para a resolução são mostrados abaixo:

#### Método de Euler

#### Método de Runge-Kutta de 3ª ordem

### Resultado

- **Euler**: \( y(1) \) aproximado = 0.53888
- **Runge-Kutta de 3ª ordem**: \( y(1) \) aproximado = 0.5671710710308493

Os erros absolutos podem ser calculados comparando com a solução exata fornecida.

## Questão 02

### Enunciado

Um projétil de massa \( m = 0.11 \) kg, lançado verticalmente para cima com velocidade inicial \( v(0) = 8 \) m/s, é detido pela força gravitacional \( F_g = mg \) e a resistência do ar \( F_r = -kv|v| \), onde \( g = -9.8 \) m/s² e \( k = 0.002 \) kg/m. A equação diferencial para a velocidade é:

\[
m v' = mg - kv|v|
\]

#### (a) Calcule a velocidade depois de \( t = 0.1s, 0.2s, ..., 1s \).
#### (b) Encontre o tempo no qual o projétil começa a cair.

### Solução

Utilizamos o método de Euler para resolver a equação diferencial da velocidade. 

### Resultado

- A velocidade em diferentes instantes de tempo é calculada aqui, e esse é o resultado.

- t = 0.0s, v = 8.00m/s
- t = 0.1s, v = 8.86m/s
- t = 0.2s, v = 9.70m/s
- t = 0.3s, v = 10.51m/s
- t = 0.4s, v = 11.29m/s
- t = 0.5s, v = 12.04m/s
- t = 0.6s, v = 12.75m/s
- t = 0.7s, v = 13.44m/s
- t = 0.8s, v = 14.09m/s
- t = 0.9s, v = 14.71m/s
- t = 1.0s, v = 15.30m/s

## Questão 03

### Enunciado

Seja \( P(t) \) o número de indivíduos de uma população. A taxa de nascimentos é constante \( b \), e a taxa de mortalidade \( d \) é proporcional ao tamanho da população. O crescimento da população é descrito pela equação logística:

\[
P'(t) = bP(t) - dP(t)^2
\]

Sabendo que \( P(0) = 50.976 \), \( b = 2.9 \times 10^{-2} \) e \( k = 1.4 \times 10^{-7} \), calcule a população estimada depois de 5 anos utilizando Runge-Kutta de 4ª ordem.

### Solução

Usamos o método de Runge-Kutta de 4ª ordem para resolver a equação logística. 
   
### Resultado

- **População estimada após 5 anos**: \( P(t) \approx \) 56751 pessoas.
