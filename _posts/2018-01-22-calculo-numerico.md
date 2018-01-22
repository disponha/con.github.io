---
layout: post
title: Cálculo Numérico
---

# Sistemas Lineares

## Resolução de Sistemas Lineares por Métodos Numéricos} 

A resolução de sistemas lineares é um problema que surge nas mais diversas áreas: previsão de tempo, otimização de sinais de transito, mecânica quântica, etc. 

Considere o sistema linear $$Ax=b$$ tal que 

$$A=(a_{ij}); ~ i,j=1,...,n $$ 

$$x=(x_j)^{t}; ~ j=1,...,n $$ 

$$b=(b_i); ~i=1,...,n$$ 




Neste caso iremos supor $$det \neq 0$$(garantia de solução única). 

Representamos o sistema linear: 

$$a_{11}x_1+a_{12}x_2+ \dots + a_{1n}x_n = b_1$$ 

$$ a_{21}x_1+a_{22}x_2+\dots +a_{2n}x_n=b_2 $$ 

$$  \vdots $$ 

$$ a_{n1}x_1+a_{n2}x_2+\dots + a_{nn}x_n = b$$  




$$ \left( \begin{array}{cccc} 
a_{11} & x_{12} & \dots  & a_{1n}\\ 
x_{21} & x_{22} & \dots & a_{2n} \\
 \vdots & \vdots & \vdots & \vdots \\ 
 a_{n1} & a_{n2} & \dots & a_{nn} 
  \end{array} \right) \left( \begin{array}{c} 
  x_1\\ 
  x_2 \\
  \vdots \\ 
  a_n  
  \end{array} \right) = \left( \begin{array}{ccc} 
  b_1\\ 
  b_2 \\
  \vdots \\ 
  b_n  
  \end{array} \right) $$ 



  Resolver o sistema dado consiste em determinar um vetor $ \overrightarrow{x}=(x_1,x_2,...,x_n)^{T}$ que satisfaça as equações simultaneamente. 
  
  Graficamente no $R^2 $ podemos representar um sistema considerando o seguinte exemplo: 
  
  $$  \left\{ \begin{array}{c} 
  -x_1+2x_2=3\\ 
  x_1+x_2=3 
  \end{array} \right.  \quad \mbox{det} \neq 0 $$ 
  
  $$\underbrace{  \left[ \begin{array}{cc} 
  -1 & 2 \\ 
  1 & 1 
  \end{array} \right]}_{ \mbox{A}} \left[ \begin{array}{c} 
  x_1\\ 
  x_2 
  \end{array} \right]= \left[ \begin{array}{c} 
  3 \\ 
  3
  \end{array} \right]$$ 
  
  Logo, $\mbox{det}(A)  \neq 0.$ 
  
 ![Gráfico]({{ site.baseurl }}/assets/img/img1.png)




Jekyll supports the use of [Markdown](http://daringfireball.net/projects/markdown/syntax) with inline HTML tags which makes it easier to quickly write posts with Jekyll, without having to worry too much about text formatting. A sample of the formatting follows.

Tables have also been extended from Markdown:

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

Here's an example of an image, which is included using Markdown:

![Geometric pattern with fading gradient]({{ site.baseurl }}/assets/img/sample2.png)

Highlighting for code in Jekyll is done using Pygments or Rouge. This theme makes use of Rouge by default.

{% highlight js %}
// count to ten
for (var i = 1; i <= 10; i++) {
    console.log(i);
}

// count to twenty
var j = 0;
while (j < 20) {
    j++;
    console.log(j);
}
{% endhighlight %}

Type on Strap uses KaTeX to display maths. Equations such as $$S_n = a \times \frac{1-r^n}{1-r}$$ can be displayed inline.

Alternatively, they can be shown on a new line:

$$ f(x) = \int \frac{2x^2+4x+6}{x-2} $$

Seja a função $$f(x): \rightarrow E(x):$$