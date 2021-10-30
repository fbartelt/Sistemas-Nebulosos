# Lista 1 - Sistemas Nebulosos

## Felipe Bartelt de Assis Pessoa - 2016026841

---

[TOC]

# Q1

## Involução

$$
\overline{\overline{A}}=A,\ \mu_A(x) = \begin{cases}1,&sse\ x\in A \\0,&c.c\end{cases}\\
\mu_\overline{A} = 1-\mu_A\\
\mu_{\overline{\overline{A}}} = 1-\mu_\overline{A} = 1 - (1-\mu_A) = \mu_A\\
\therefore \overline{\overline{A}}=A\\
\hfill \blacksquare
$$

## Absorção

$$
A\cup(A\cap B)= A,\ \mu_A(x) = \begin{cases}1,&sse\ x\in A \\0,&c.c\end{cases}\\
\mu_{A\cap B}= \min(\mu_A,\mu_B)\\
\mu_{A\cup (A\cap B)} = \max\left(\mu_A,\min(\mu_A,\mu_B)\right)\\
\text{Suponha }\min(\mu_A,\mu_B)=\mu_A \implies \mu_{A\cup (A\cap B)}=\max(\mu_A,\ \mu_A)=\mu_A\\
\text{Suponha }\min(\mu_A,\mu_B)=\mu_B \implies \mu_{A\cup (A\cap B)}=\max(\mu_A,\ \mu_B)=\mu_A, \text{ uma vez}\\\text{que }\min(\mu_A,\ \mu_B)=\max(\mu_A, \mu_B)\iff \mu_A=\mu_B\\
\hfill\blacksquare
$$

## Contradição

$$
A\cap\overline{A}= \O,\ \mu_A(x) = \begin{cases}1,&sse\ x\in A \\0,&c.c\end{cases}\\
\mu_{A\cap\overline{A}} = \min(\mu_A,\ \mu_\overline{A}) = \min(\mu_A,\ 1- \mu_A)\\
\text{Suponha que } \mu_A=1 \text{ ou }\mu_A=0\\
\text{Se }\mu_A = 1\implies\min(1,1-1)=\min(1,0)=0\\
\text{Se }\mu_A = 0\implies\min(0,1-0)=\min(0,1)=0\\
\implies \mu_{A\cap\overline{A}}(x)=0\ \forall\ x\in X\\
\therefore x\notin A\cap\overline{A}\ \forall\ x\in X\implies A\cap\overline{A}= \O\\
\hfill\blacksquare
$$

## De Morgan

$$
\overline{A\cup B}=\overline{A}\cap\overline{B},\ \mu_A(x) = \begin{cases}1,&sse\ x\in A \\0,&c.c\end{cases}\\
\mu_{\overline{A\cup B}}=1-\mu_{A\cup B}=1-\max(\mu_A,\ \mu_B)\\
\mu_{\overline{A}\cap\overline{B}}=\min(1-\mu_A,\ 1-\mu_B)\\
\text{Suponha que }\mu_A=1 \text{ ou } \mu_B=1\implies\max(\mu_A,\mu_B)=1\implies\mu_{\overline{A\cup B}}=0, \\
\text{ainda}\ \min(1-\mu_A,1-\mu_B)=0\therefore \mu_{\overline{A\cup B}}=\mu_{\overline{A}\cap\overline{B}}\\
\text{Suponha que } \mu_A=\mu_B=0\implies\max(\mu_A,\mu_B)=0\implies\mu_{\overline{A\cup B}}=1,\\
\text{ainda}\ \min(1-\mu_A,1-\mu_B)=1\therefore \mu_{\overline{A\cup B}}=\mu_{\overline{A}\cap\overline{B}}\\

\hfill\blacksquare
$$

# Q2

## Involução

$$
\overline{\overline{A}}=A,\ \mu_A(x) : X\rightarrow[0,1], x\in X\\
\mu_\overline{A} = 1-\mu_A\\
\mu_{\overline{\overline{A}}} = 1-\mu_\overline{A} = 1 - (1-\mu_A) = \mu_A\\
\therefore \overline{\overline{A}}=A\\
\hfill \blacksquare
$$

## Absorção

$$
A\cup(A\cap B)= A,\ \mu_A(x) : X\rightarrow[0,1], x\in X\\
\mu_{A\cap B}= \min(\mu_A,\mu_B)\\
\mu_{A\cup (A\cap B)} = \max\left(\mu_A,\min(\mu_A,\mu_B)\right)\\
\text{Suponha }\min(\mu_A,\mu_B)=\mu_A \implies \mu_{A\cup (A\cap B)}=\max(\mu_A,\ \mu_A)=\mu_A\\
\text{Suponha }\min(\mu_A,\mu_B)=\mu_B \implies \mu_{A\cup (A\cap B)}=\max(\mu_A,\ \mu_B)=\mu_A, \text{ uma vez}\\\text{que }\min(\mu_A,\ \mu_B)=\max(\mu_A, \mu_B)\iff \mu_A=\mu_B\\
\hfill\blacksquare
$$

## Contradição

$$
A\cap\overline{A}= \O,\ \mu_A(x) : X\rightarrow[0,1], x\in X\\
\mu_{A\cap\overline{A}} = \min(\mu_A,\ \mu_\overline{A}) = \min(\mu_A,\ 1- \mu_A)\\
\text{Suponha que }\mu_A\ge 0.5\implies\min(\mu_A,\ 1- \mu_A)=1-\mu_A\\
\text{Suponha que }\mu_A< 0.5\implies\min(\mu_A,\ 1- \mu_A)=\mu_A\\
\implies \exists\  x\in X \text{ t.q } A\cap\overline{A}(x)\neq\O\\
\text{Ainda, se }\mu_A\notin\{0,1\}\implies A\cap\overline{A}\neq\O\\
\hfill\blacksquare
$$

## De Morgan

$$
\overline{A\cup B}=\overline{A}\cap\overline{B},\ \mu_A(x) : X\rightarrow[0,1], x\in X\\
\mu_{\overline{A\cup B}}=1-\mu_{A\cup B}=1-\max(\mu_A,\ \mu_B)\\
\mu_{\overline{A}\cap\overline{B}}=\min(1-\mu_A,\ 1-\mu_B)\\
\text{Suponha } \mu_A\le\mu_B\implies \mu_{\overline{A\cup B}}=1-\max(\mu_A,\ \mu_B)=1-(\mu_B),\\\text{ por outro lado }1-\mu_B\le1-\mu_A\implies  \mu_{\overline{A}\cap\overline{B}}=\min(1-\mu_A,\ 1-\mu_B)=1-\mu_B.\\
\text{Suponha }\mu_A>\mu_B\implies\mu_{\overline{A\cup B}}=1-\max(\mu_A,\ \mu_B)=1-(\mu_A),\\
\text{ por outro lado }1-\mu_B>1-\mu_A\implies  \mu_{\overline{A}\cap\overline{B}}=\min(1-\mu_A,\ 1-\mu_B)=1-\mu_A.\\
\mu_{\overline{A\cup B}}=\mu_{\overline{A}\cap\overline{B}}\therefore\overline{A\cup B}=\overline{A}\cap\overline{B}\\
\hfill\blacksquare
$$

# Q3

$$
N(a)=\frac{1-a}{1+sa}, s\in(-1,\infty)
$$

- Axioma N1: $N(0)=1,\ N(1)=0$
  $$
  N(0) = \frac{1-0}{1+0s}=1\\
  N(1) = \frac{1-1}{1+s}=0
  $$

- Axioma N2: $N(a)\ge N(b),\ se\ a\le b$

$$
\text{Suponha }a\le b.\\
N(a)=\frac{1-a}{1+sa},\ N(b)=\frac{1-b}{1+sb},\ s\in(-1,\infty)\\
\text{Suponha também } N(a)< N(b)\\
\frac{1-a}{1+sa}<\frac{1-b}{1+sb}\\
(1-a)(1+sb)<(1-b)(1+sa)\\
1-asb+sb-a<1-asb+sa-b\\
b(s+1)< a(s+1),\ s> -1 \text{ por definição}\\
\therefore b<a.\\ \text{O que contradiz a premissa inicial e, portanto, se } a\le b\implies N(a)\ge N(b)\\
\hfill\blacksquare
$$

- Axioma N4: $N\left(N(a)\right) = a$
  $$
  N(a) = \frac{1-a}{1+sa}\implies N(N(a)) = \frac{1-\frac{1-a}{1+sa}}{1+s\frac{1-a}{1+sa}}\\
  N(N(a)) = \frac{1+sa-1+a}{1+sa+s-sa}=\frac{a(s+1)}{1+s} = a, \text{ já que } s>-1
  $$

# Q4

$$
S(a,b) = a+b-ab
$$

- Axioma S1: $S(0,0) = 0, S(a,0)=S(0,a)=a$
  $$
  S(0,0)=0+0-(0\cdot0)=0\\
  S(a,0)=a+0-(a\cdot0)=a\\
  S(0,a)=0+a-(0\cdot a)=a
  $$

- Axioma S2: $S(a,b)\le S(c,d),\ se\ a\le c, b\le d$
  $$
  \text{Suponha } a\le c, b\le d.\text{Ainda, suponha } S(a,b)>S(c,d)\\
  S(a,b)>S(c,d)\\
  a+b-ab>c+d-cd\ \quad(1)\\
  $$

  $$
  \text{Como }a,b,c,d\in[0,1]:\\
  a\le c \implies ab\le cb\\
  b\le d\implies cb\le cd\\
  \therefore ab\le cb\le cd\\
  \text{Ainda, }\\
  a\le c \implies a-c\le 0\\
  b\le d\implies b-d\le 0\\
  \implies a+b-c-d\le0\\
  \therefore a+b\le c+d\\
  \text{Dado } S:[0,1]\times[0,1]\mapsto[0,1], \text{tem-se:}\\
  0\le a \le 1 \implies 0\le1-a\\
  0\le b \le 1 \implies 0\le1-b\\
  0\le (1-a)(1-b)\\
  0\le 1-a-b+ab\\
  \therefore a+b\le ab+1. \text{ Resultado análogo para } c,d.\text{ Assim}\\
  a+b-ab-1\le0,\ c+d-cd-1\le0\\
  a+b-ab-1-c-d+cd+1\le0\\
  a+b-ab\le c+d-cd\\
  \text{Uma contradição com (1), demonstrando a veracidade do axioma para o } S(a,b) \text{ em questão}\\\hfill\blacksquare
  $$
  
- Axioma S3: $S(a,b) = S(b,a)$
  $$
  S(a,b) = a+b-ab\\
  S(b,a) = b+a-ba\\
  a,b\in\R\implies ba=ab\\\therefore S(a,b)=S(b,a)
  $$
  
- Axioma S4: $S(a,S(b,c))=S(S(a,b),c)$

  $$
  S(a,S(b,c)) = a+(b+c-cb) -a\left(b+c-cb\right)=a(1-b-c+cb)+b+c-cb\\
  S(S(a,b),c) = (a+b-ab)+c-\left(a+b-ab\right)c=a(1-b-c+cb)+b+c-cb\\
  \therefore S(a,S(b,c))=S(S(a,b),c)
  $$
# Q5
$$
S(a,b) = \min(1,a+b)
$$

- Axioma S1: $S(0,0) = 0, S(a,0)=S(0,a)=a$
  $$
  S(0,0)=\min(1,0+0)=0\\
  S(a,0)=\min(1,a+0)=a\\
  S(0,a)=\min(1,0+a)=a
  $$

- Axioma S2: $S(a,b)\le S(c,d),\ se\ a\le c, b\le d$
  $$
  \text{Suponha } a\le c, b\le d.\text{Ainda, suponha } S(a,b)>S(c,d)\\
  S(a,b)>S(c,d)\\
  \implies \min(1,a+b)>\min(1,c+d)\ \quad(1)\\
  $$

  $$
  \text{Tem-se}\\
  a\le c \implies a-c\le 0\\
  b\le d\implies b-d\le 0\\
  \implies a+b-c-d\le0\\
  \therefore a+b\le c+d\quad (2)\\\\
  \bullet\ \text{Se }\ c+d<1\implies \min(1,c+d)=c+d,\\
  \text{como }a+b\le c+d<1,\text{ segue que } a+b<1\implies\min(1,a+b)=a+b.\\
  \text{Por (2), nota-se que, para } c+d<1,\ \min(1,a+b)\le\min(1,c+d),\text{ o que contradiz (1).}\\
  \bullet\ \text{Se } c+d\ge1\implies\min(1,c+d)=1.\text{ E há duas possibilidades para } \min(1,a+b):\\
  \text{Caso } a+b<1\implies \min(1,a+b)=a+b.\ \text{Nesse caso, }\min(1,a+b)<\min(1,c+d)\\ 
  \text{Caso } 1\le a+b<c+d\implies\min(1,a+b)=1\therefore\min(1,a+b)=\min(1,c+d).\\
  \text{Em todos os casos, vê-se uma contradição com (1), portanto segue o axioma}\\\hfill\blacksquare
  $$
  
  Axioma S3: $S(a,b) = S(b,a)$
  $$
  S(a,b) = \min(1,a+b)\\
  S(b,a) = \min(1,b+a)\\
  \therefore S(a,b)=S(b,a)
  $$
  
- Axioma S4: $S(a,S(b,c))=S(S(a,b),c)$

  $$
  S(a,S(b,c)) = \min(1,a+\min(1,b+c))=\min(1,a+x)\\
  S(S(a,b),c) = \min(1,\min(1,a+b)+c)=\min(1,y+c)\\
  \text{Se }\ a+x\ge1\ \and\ y+c\ge1,\text{ o mínimo de ambos são iguais a }1.\\
  \text{Suponha } a+x<1\ ou\ y+c<1\\
  \text{Se } a+x<1\implies\min(1,a+x)=a+x=a+\min(1,b+c) = a+b+c\ \or\ a+1,\\
  \text{como }a+x<1,\ a+1\text{ não é solução possível, já que implica }a+1<1\therefore a<0\notin[0,1],\\
  \text{o que não condiz com a forma de conjuntos nebulosos, portanto }a+x>1\implies x=b+c,\\
  \therefore S(a,S(b,c))=a+b+c<1\implies a+b<1,\\
  \text{segue então }S(S(a,b),c)=\min(1,\min(1,a+b)+c)=\min(1,a+b+c)=a+b+c\\
  \therefore S(a,S(b,c))=S(S(a,b),c)\\
  \text{Analogamente, se } y+c<1\implies\min(1,y+c)=y+c=\min(1,a+b)+c = a+b+c\ \or\ 1+c\\
  \therefore S(S(a,b),c)=a+b+c<1\implies b+c<1\\
  \text{segue } S(a,S(b,c))=\min(1,a+\min(1,b+c))=\min(1,a+b+c)=a+b+c\\
  \therefore S(S(a,b),c)=S(a,S(b,c))\\\hfill\blacksquare
  $$
  

# Q6

$$
T(a,b) = ab;\ a,b\in[0,1]
$$

- Aximoa T1: $T(0,0)=0,\ T(a,1)=T(1,a)=a$
  $$
  T(0,0) = 0\cdot 0=0\\
  T(a,1)=a\cdot1=a\\
  T(1,a)=1\cdot a=a\\\therefore T(1,a)=T(a,1)
  $$
  
- Axioma T2: $T(a,b)\le T(c,d)$ se $a\le c,\ b\le d$
  $$
  \text{Suponha } a\le c \ \and \ b\le d\\
  \implies a\cdot b\le c\cdot b\ \and\ c\cdot b\le c\cdot d\\
  \implies ab\le cb\le cd\\
  \therefore T(a,b)=ab\le cd=T(c,d)\\\hfill\blacksquare
  $$

- Axioma T3: $T(a,b)=T(b,a)$
  $$
  T(a,b)=ab\\
  T(b,a)=ba\\\text{Como há comutatividade no corpo }\R,\text{ segue } T(a,b)=T(b,a)
  $$

- Axioma T4: $T(a,T(b,c))=T(T(a,b),c)$
  $$
  T(a,T(b,c)) = T(a, bc)=abc\\
  T(T(a,b),c)=T(ab,c)=abc\\\therefore T(a,T(b,c))=T(T(a,b),c)
  $$
# Q7
$$
T(a,b) = \max(0,a+b-1);\ a,b\in[0,1]
$$

- Aximoa T1: $T(0,0)=0,\ T(a,1)=T(1,a)=a$
  $$
  T(0,0) = \max(0,0+0-1)=0\\
  T(a,1)=\max(0,a+1-1)=a\\
  T(1,a)=\max(0,1+a-1)=a\\\therefore T(1,a)=T(a,1)
  $$
  
- Axioma T2: $T(a,b)\le T(c,d)$ se $a\le c,\ b\le d$
  $$
  \text{Suponha } a\le c \ \and \ b\le d\\
  \implies a+b\le c+d\\
  \text{Suponha }\ c+d\le1\implies a+b\le1\therefore\max(0,c+d-1)=0\ \and\ \max(0,a+b-1)=0\\
  \therefore T(a,b)= T(c,d)\\
  \text{Suponha } c+d>1\implies\max(0,c+d-1)=c+d-1,\\
  \text{se }a+b\le1\implies\max(0,a+b-1)=0<1<c+d-1\therefore T(a,b)<T(c,d),\\
  \text{se }1<a+b\le c+d\implies\max(0,a+b-1)=a+b-1, \\
  \text{como }a+b\le c+d\implies a+b-1\le c+d-1\\
  \therefore T(a,b)=\max(0,a+b-1)\le \max(0,c+d-1)=T(c,d)\\\hfill\blacksquare
  $$
  
- Axioma T3: $T(a,b)=T(b,a)$
  $$
  T(a,b)=\max(0,a+b-1)\\
  T(b,a)=\max(0,b+a-1)\\\therefore T(a,b)=T(b,a)
  $$

- Axioma T4: $T(a,T(b,c))=T(T(a,b),c)$
  $$
  T(a,T(b,c)) = \max(0,a+\max(0,b+c-1)-1)=\max(0,a+x-1)\\
  T(T(a,b),c)=\max(0,\max(0,a+b-1)+c-1)=\max(0,y+c-1)\\
  \text{Como os conjuntos são nebulosos, }a,b,c\in[0,1],\text{ assim }b+c\le2\ \and\ a+b\le2\\
  \implies b+c-1\le1\ \and\ a+b-1\le1\\
  \therefore a+x-1\le a\le1\ \and\ y+c-1\le c\le 1\\\\
  \text{Suponha } a+x-1\le0\ \and\ y+c-1\le0.\\
  \text{Então é óbvio que } T(a,T(b,c))=0=T(T(a,b),c)\\
  \\\text{Suponha }a+x-1>0\ \or\  y+c-1>0.\\
  \text{Se }a+x-1>0\implies\max(0,a+x-1)=a+x-1=a+0-1\ \or\ a+b+c-2,\\
  \text{porém }a+x-1=a-1\implies a>1\notin[0,1],\text{ portanto a única solução possível é}\\
  a+x-1=a+b+c-2>0\implies a+b+c>2\\
  \therefore T(a,T(b,c))=a+b+c-2, \\
  \text{ uma vez que } a+b+c>2\text{ implica que todos os conjuntos são não nulos e dois deles}\\
  \text{ são representados por 1, ou seja, é impossível que }a+b-1\le0,\text{ já que }a+b>1,\\\text{então } T(T(a,b),c)=\max(0,a+b+c-2), \text{ porém }a+b+c>2\\
  \implies T(T(a,b),c)=a+b+c-2=T(a,T(b,c))\\\\
  \text{ O resultado é análogo para } y+c-1>0\\
  \therefore T(a,T(b,c))=T(T(a,b),c)\\\hfill\blacksquare
  $$

# Q8

$$
T(a,b)=N\left(S\left(N\left(a\right),N\left(b\right)\right)\right),\\
S(a,b)=a+b-ab,\\
N(a)=1-a\\
T(a,b)=ab
$$

Tomando como dado $S(a,b)$:
$$
S(a,b)=a+b-ab\\
N(a)=1-a,\ N(b)=1-b\\
T(a,b)=N(S(1-a, 1-b))=N(1-a+1-b-\left((1-a)(1-b)\right))\\
=N(2-a-b-(1+ab-a-b))=N(1-ab)\\
\therefore T(a,b)=N(1-ab)=1-(1-ab)=ab\\\hfill\blacksquare
$$
Tomando como dado $T(a,b)$:
$$
T(a,b)=ab\\
N(a)=1-a,\ N(b)=1-b\\
T(a,b)=ab=N(S(1-a,1-b))=1-S(1-a,1-b)\\
\implies S(1-a,1-b)=1-ab\\
\text{Tomando }\ a=1-a\ \and\ b=1-b:\\
S(a,b)=1-(1-a)(1-b)=1-(1-a-b+ab)=a+b-ab\\\hfill\blacksquare
$$
