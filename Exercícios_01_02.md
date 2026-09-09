      Linguagens Formais, Alfabeto, Linguagens e Gramáticas 

Exercício:

Considere: 


$\epsilon = a, b, c$ 

1. Quantos símbolos existem no alfabeto?
2. Quais são os símbolos?
3. O símbolo a pertence ao alfabeto?
4. O símbolo d pertence ao alfabeto?
5. Escreva uma palavra formada por símbolos desse alfabeto

   Respostas

- Existem 3 símbolos no alfabeto
-  a, b, c
-  Sim, pertence a  $\epsilon$
-  Não, não pertence a  $\epsilon$
-  abc (cba, ab, ac)


Considere: 


$\epsilon = a, b$ 

Verifique quais das sequências abaixo são palavras construídas sobre esse alfabeto:


- abba  - abba $x \in A$  $\epsilon*$ Pertence ao conjunto de todas as palavras construidas sobre Sigma
- abc - c $x \notin A$   $\epsilon*$ 
- baab - abc   $x \notin A$    $\epsilon*$ 
- d - $x \notin A$    $\epsilon*$


Classifique cada palavra como válida ou não válida 

 $\epsilon = 0,1$ 

 0101 - 0101 $x \in A$  $\epsilon*$ 
 
 00110 - 00110 $x \in A$  $\epsilon*$ 
 
 012 - 012  $x \notin A$    $\epsilon*$
 
 111 - 111 $x \in A$  $\epsilon*$
 
 10a - a $x \notin A$    $\epsilon*$


 Considere:

 $\epsilon = 0,1$

 Determine se as afirmações são verdadeiras ou falsas:

1. 0 $x \in A$  $\epsilon$  - V
2. 1 $x \in A$  $\epsilon$  - V
3. 01 $x \in A$  $\epsilon$ - F, 01 é uma palavra não um símbolo individual
4. 01 $x \in A$  $\epsilon*$ - V
5. 2 $x \in A$  $\epsilon$ - F
6. 101 $\epsilon*$ - V, todos os símbolos pertencem ao alfabeto
   
Considere:

L = 0, 01, 011, 0111

Determine se cada palavra pertence à linguagem:

1. 0 $x \in A$ L - V
2. 01 $x \in A$ L - V
3. 0111 $x \in A$ L - V
4. 10 $x \in A$ L - X
5. 111 $x \in A$ L - X

Considere: 

$$
L = \{ b^n \mid n \ge 1 \}
$$

1. b, bb, bbb, bbbb, bbbbb
2. O conjunto das palavras formadas por n ocorrências de b, tal que n é maior ou igual a 1
3. Sim
4. Não

Explique a diferença entre:

A - L = $\emptyset$

B - L = $\epsilon$ 

1. $\epsilon$
2. $\emptyset$
3. $\epsilon$, possui comprimento zero

Considere:

G = (S, A, 0, 1, P, S)

com 

$$
P = \begin{cases} 
S \to 0A \\ 
A \to 1 
\end{cases}
$$

1. S, A
2. 0, 1
3. $$
P = \begin{cases} 
S \to 0A \\ 
A \to 1 
\end{cases}
$$    

4. S
5. $S \Rightarrow 0A \Rightarrow 01$

Considere:

$S \to 0S$

1. $S \to 0S$  
2. $S \to 00S$  
3. $S \to 000S$
4. $S \Rightarrow 0S \Rightarrow 00S \Rightarrow 000S$

Utilizando:

G:{ $S \Rightarrow aSS \Rightarrow abS \Rightarrow b$ }

gere: a

aaab

S ⇒ aS ⇒ aaS ⇒ aaaS

$S \Rightarrow b$

$aaaS \Rightarrow b$

S ⇒ aS ⇒ aaS ⇒ aaaS ⇒ aaab

Considere novamente:

G:{S ⇒ 0SS ⇒ 1}

1. 1 - S ⇒ 1
2. 01 - Não pode ser gerada
3. 001 - Não pode ser gerada
4. 0001 - Não pode ser gerada
5. 101 - Não pode ser gerada
6. 1001 - Não pode ser gerada

Desafio Final 

Considere:

G: {S ⇒ aSS}

1. S ⇒ b
2. Não pode ser gerada
3. Não pode ser gerada
4. Não pode ser gerada
5. Não pode ser gerada
6. Não pode ser gerada
