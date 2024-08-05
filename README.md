## LHopital Rule

If $\lim_{x \to a} f(x)$ ln $f(x) = L$, then

$\lim_{x \to a} f(x)$ = $\lim_{x \to a} e^{ln f(x)}$ = $e^L$.

Here $\alpha$ may be either finite or infinite.



## __*EXAMPLE 8*__

Show that $\lim_{x \to 0^+}$  $(1+x)^{\frac{1}{x}}$ = *e*.

### __*Solution:-*__   
The limit leads to the indeterminate form  $1^\infty$. We let $f(x)$ = $(1+x)^{\frac{1}{x}}$ 

and find $\lim_{x \to 0^+}$ ln $f(x)$ . Since

$ln f(x) = ln (1+x)^{\frac{1}{x}}$

 = $\frac{1}{x} ln (1+x)$ ,
 

 l'hopital's rule now applies to give    
 
 $\lim_{x \to 0^+}$ ln *f(x)* =  $\lim_{x \to 0^+}$  $(\frac{ln(1+x)}{x} \)$         $\( \frac{0}{0} \)$

$=\lim_{x \to 0^+}$ $(\frac{ln(1/1+x)}{x} \)$

$= \frac{1}{1}  = 1$ .

Therefore,

$\lim_{x \to 0^+} (1+x)^{\frac{1}{x}}  = \lim_{x \to 0^+} f(x)  =  \lim_{x \to 0^+}  e^{ln f(x)}  = e^1  = e$

## __*EXAMPLE 9*__

Find $\lim_{x \to \infty} (x)^{\frac{1}{x}}$.

### __*Solution:-*__
The limit leads to the indeterminate form $\infty^0$. We let $f(x) =(x)^{\frac{1}{x}}$ and

find  $\lim_{x \to \infty} ln f(x)$. Since 

$lnf(x) = ln (x)^{\frac{1}{x}}$

=  $(\frac{ln x}{x} \)$ ,

L'Hopital's rule gives

$\ \lim_{x \to \infty}$ ln *f(x)* = $\ \lim_{x \to \infty}$ $(\frac{ln x}{x} \)$                    $\( \frac{infty}{infty} \)$

= $\ \lim_{x \to \infty}$  $(\frac{1/x}{1} \)$

= $(\frac{0}{1} \)$ = 0.

Therefore,

$\ \lim_{x \to \infty}$ $\( (x)^{\frac{1}{x}} )\$ = $\ \lim_{x \to \infty}$ *f(x)* = $\ \lim_{x \to \infty}$ $\( e^{ln f(x)} )\$ =  $\ e^0 \$
= 1



## EXERCISE 6.6

### Applying l'Hopital's Rule
 Use l'Hopital's rule to find the limits in Exercise 1-42.
 
 ## 1. $\lim_{x \to 2}$ $\ \frac{(x-2)}{x^2 - 4} \$

 ## 2. $\lim_{x \to -5}$ $\ \frac{(x^2-25)}{(x+5)} \$
 
 ## 3. $\lim_{t \to -3}$ $\ \frac{(t^3-4t+15)}{(t^2-t-12)} \$
 
 ## 4. $\ \lim_{t \to 1}$ $\ \frac{(t^3-1)}{(4t^3-t-3)} \$

 ## 5. $\ \lim_{x \to \infty}$ $\ \frac{(5x^2-3x)}{(7x^2+1)} \$

 ## 6. $\ \lim_{x \to \infty}$ $\ \frac{(x-8x^2)}{(12x^2+5x)} \$

 ## 7. $\ \lim_{t \to 0}$ $\ \frac{(sint^2)}{(t)} \$

 ## 8. $\ \lim_{t \to 0}$ $\ \frac{(sin5t)}{(t)} \$

 ## 9. $\ \lim_{x \to 0}$ $\ \frac{(8x^2)}{(cos x-1)} \$

 ## 10. $\ \lim_{x \to \infty}$ $\ \frac{(sinx-x)}{(x^3)} \$

 ## 11. $\lim_{\theta \to \frac{x}{2}}$ $\frac{2\theta - \pi}{\cos(2\pi - \theta)}$

 ## 12. $\lim_{\theta \to \frac{x}{3}}$ $\frac{3\theta + \pi}{\sin(\theta + \{(\pi/3)})}$

 ## 13. $\lim_{\theta \to \frac{x}{2}}$ $\frac{1-sin\theta}{1+cos 2\theta}$

 ## 14. $\ \lim_{x \to 1}$ $\frac{x-1}{ln x-sin\pi x}$

 ## 15. $\ \lim_{x \to 0}$ $\ \frac{(x^2)}{(ln(sec x))} \$

 ## 16. $\lim_{x \to \frac{x}{2}}$ $\frac{x}{(x- (\pi/2))^2}$

 ## 17. $\ \lim_{t \to 0}$ $\ \frac{t(1-cost)}{t-sint} \$

 ## 18. $\ \lim_{t \to 0}$ $\ \frac{t sint}{1-cost} \$

 ## 19. $\lim_{x \to \frac{\pi}{2}^-} (x - \frac{\pi}{2}) \sec(x)$

 ## 20. $\lim_{x \to \frac{\pi}{2}^-} \left( \frac{\pi}{2} - x \right) \tan(x)$

 ## 21. $\lim_{\theta \to 0}$ $\frac{3^{\sin \theta} - 1}{\theta}$

 ## 22. $\lim_{\theta \to 0}$ $\frac{\left(\frac{1}{2}\right)^\theta - 1}{\theta}$

 ## 23. $\ \lim_{x \to 0}$ $\frac{x 2^x}{2^x - 1}$

 ## 24. $\ \lim_{x \to 0}$ $\frac{3^x - 1}{2^x - 1}$

 ## 25. $\ \lim_{x \to \infty}$ $\frac{\ln(x+1)}{\log_2 x}$

 ## 26. $\ \lim_{x \to \infty}$ $\frac{\log_2 x}{\log_3 (x+3)}$

 ## 27. $\ \lim_{x \to 0^+}$ $\frac{ln(x^2 + 2x)}{ln x}$

 ## 28. $\ \lim_{x \to 0^+}$ $\frac{ln(e^x - 1)}{ln x}$

 ## 29. $\ \lim_{y \to 0}$ $\frac{\sqrt{5y + 25} - 5}{y}$

 ## 30. $\ \lim_{y \to 0}$ $\frac{\sqrt{ay + a^2} - a}{y}$   , a>0

 ## 31. $\ \lim_{x \to \infty}$ $(\ln2x - \ln(x + 1))$

 ## 32. $\ \lim_{x \to 0^+}$ $(lnx - \ln sinx)$

 ## 33. $\ \lim_{x \to 0^+}$ $(\frac{1}{x} - \frac{1}{\sin x})$

 ## 34. $\ \lim_{x \to 0^+}$ $(\frac{3x+1}{x} - \frac{1}{\sin x})$

 ## 35. $\ \lim_{x \to 1^+}$ $(\frac{1}{x-1} - \frac{1}{ln x})$

 ## 36. $\ \lim_{x \to 0^+}$ $(\csc x - \cot x + \cos x)$

 ## 37. $\ \lim_{x \to \infty}$ $\int_{x}^{2x} \frac{1}{t} \ dt$

 ## 38. $\ \lim_{x \to \infty}$ $\frac{1}{x \ln x} \int_{1}^{x} \ln t \ dt$

 ## 39. $\lim_{\theta \to 0}$ $\frac{cos\theta - 1}{e^\theta - \theta - 1}$

 ## 40. $\lim_{h \to 0}$ $\frac{e^h-(1+h)} {h^2}$

 ## 41. $\ \lim_{t \to \infty}$ $\frac{e^t+t^2} {e^t-t}$

 ## 42. $\ \lim_{x \to \infty}$ $x^2 e^{-x}$


 ### Limits Involving Bases and Exponents
 Find the limits in Exercise 43-52.

 ## 43. $\ \lim_{x \to 1^+}$ $x^{\frac{1}{1-x}}$

 ## 44. $\ \lim_{x \to 1^+}$ $x^{\frac{1}{x-1}}$

 ## 45. $\ \lim_{x \to \infty}$ $\left(\ln x\right)^{\frac{1}{x}}$

 ## 46. $\ \lim_{x \to e^+}$ $\left(\ln x\right)^{\frac{1}{x-t}}$

 ## 47. $\ \lim_{x \to 0^+}$ $\left(x\right)^{\frac{-1}{ln x}}$

 ## 48. $\ \lim_{x \to \infty}$ $\left(x\right)^{\frac{1}{ln x}}$

 ## 49. $\ \lim_{x \to \infty}$ $\left(1+2x\right)^{\frac{1}{2 ln x}}$

 ## 50. $\ \lim_{x \to 0}$ $\left(e^x + x\right)^{\frac{1}{x}}$

 ## 51. $\ \lim_{x \to 0^+}$ $x^x$

 ## 52. $\ \lim_{x \to 0^+}$ $\left(1 + \frac{1}{x}\right)^x$


 ### Theory and Applications
 L'Hopital's Rule does not help with the limits in Exercise 53-56. Try
 it--you just keep on cycling. Find the limits some other way.

 ## 53. $\ \lim_{x \to \infty}$ $\(\frac{\sqrt{9x + 1}}{\sqrt{x + 1}}\)$

 ## 54. $\ \lim_{x \to 0^+}$ $\(\frac{\sqrt{x}}{\sqrt{sin x}}\)$

 ## 55. $\ \lim_{x \to \left(\frac{\pi}{2}\right)^-} \frac{\sec x}{\tan x} \$

 ## 56. $\ \lim_{x \to 0^+}$ $\( \frac{\cot x}{\csc x} \)$

 ## 57. Which one is correct,and which one is wrong? Give reasons for your answers.

 ## a. $\ \lim_{x \to 3}$ $\( \frac{x - 3}{x^2 - 3} \)$ = $\ \lim_{x \to 3}$ $\( \frac{1}{2x} \)$ = $\(\frac{1}{6}\)$

 ## b. $\ \lim_{x \to 3}$ $\( \frac{x - 3}{x^2 - 3} \)$ = $\(\frac{1}{6}\)$ = 0

 ## 58. Which one is correct,and which one is wrong? Give reasons for your answers.

 ## a. $\lim_{x \to 0} \frac{x^2 -2x}{x^2 - sin x}  =  \lim_{x \to 0} \frac{2x-2}{2x-cosx} = \lim_{x \to 0} \frac{2}{2+sinx} = \frac{2}{2+0} = 1$

 ## b. $\lim_{x \to 0} \frac{x^2 -2x}{x^2 - sin x}  = \lim_{x \to 0} \frac{2x-2}{2x-cosx} = \frac{-2}{0-1} = 2$

 ## 59. Only one of these calculations is correct. Which one? Why are the other things wrong? Give reasons for your answers.

 
$$ 
\lim_{x \to 0} \frac{2x}{\sin 2x} = 1 
$$

$$ 
\lim_{x \to 0} \frac{2x - 2}{\sin 2x - \sin 2} = 2 
$$


$$
\lim_{x \to 0} \frac{x - \sin x}{x^3} = 1/6
$$

$$
\lim_{x \to 0} \frac{x^3 - \sin^3 x}{x^3 - x \sin x} = 1/2
$$

## 59.  Only one of these answers is correct. Which one? Why are the others wrong? Give reasons for your answers.

$$
\lim_{x \to \infty} \left( \frac{1}{x} - \frac{1}{\sin x} \right) = -1 
$$

$$
\lim_{x \to 0} x \sin \frac{1}{x} = 0 
$$

$$ 
\lim_{x \to \infty} \frac{\ln x}{x} = 0 
$$

$$
\lim_{x \to \infty} x \sin \frac{1}{x} = 0 
$$

## 60.  Let 
$$ f(x) = \begin{cases} 
2x + 2, & x \neq 0 \\
0, & x = 0
\end{cases} $$

and 

$$ g(x) = \begin{cases} 
x, & x \neq 0 \\
0, & x = 0
\end{cases} $$

Show that 

$$ 
\lim_{x \to 0} \frac{f'(x)}{g'(x)} =1 
$$

but that 

$$ 
\lim_{x \to 0} \frac{f(x)}{g(x)} = 2 
$$


Doesn't this contradict L'Hôpital's rule? Give reasons for your answers.

5. Find a value of \(c\) that makes the function 
\[ f(x) = \begin{cases} 
9x - 3 \sin 3x, & x \neq 0 \\
c, & x = 0
\end{cases} \]

continuous at \(x = 0\). Explain why your value of \(c\) works.

6. Find a value of \(c\) that makes the function 
\[ f(x) = \begin{cases} 
\frac{\tan (6x)}{x}, & x \neq 0 \\
c, & x = 0
\end{cases} \]

continuous from the right at \(x = 0\). Explain why your value of $ works.

## 71. The continuous compound interest formula. In deriving the formula $A(t) = A_0 e^{rt}$ in Section 6.5, we claimed that 

$$
\lim_{n \to \infty} \left( 1 + \frac{r}{n} \right)^{nt} = e^{rt} 
$$

This equation will hold if 

$$
\lim_{n \to \infty} \left( 1 + \frac{r}{n} \right)^n = e^r 
$$

and this, in turn, will hold if 

$$
\lim_{n \to \infty} \left( 1 + \frac{1}{n} \right)^n = e 
$$

As you can see, the limit leads to the indeterminate form $1^\infty$ . Verify the limit using L'Hôpital's rule.

64. Given that $x > 0$, find the maximum value, if any, of 
a) $\frac{x}{e^x}$
b) $\frac{x}{e^{x^2}}$
c) $x^x$ (for $n$ a positive integer)

Show that $\lim_{x \to \infty} x^x = 1$ for every positive integer $n$ .

## Grapher Explorations

65. Determining the value of $e$
a) Use L'Hôpital's rule to show that 

$$
\lim_{n \to \infty} \left( 1 + \frac{1}{n} \right)^n = e 
$$

b) CALCULATOR See how close you can come to 

$$
e = 2.71828 1828 459 045 
$$

by evaluating $\left( 1 + \frac{1}{n} \right)^n$ for $x = 10, 10^2, 10^3$ , and so on. You can expect the approximations to approach $e$ at first, but on some calculators they will move away again as round-off errors take their toll.

c) If you have a grapher, you may prefer to do part (b) by graphing $f(x) = \left( 1 + \frac{1}{x} \right)^x$ for large values of $x$ , using TRACE to display the coordinates along the graph. Again, you may expect to find decreasing accuracy as $x$ increases and, beyond $x = 10^8$ or so, erratic behavior.

66. This exercise explores the difference between the limit 

$$ 
\lim_{x \to \infty} \left( 1 + \frac{1}{x} \right)^x = e
$$

and the limit 

$$ 
\lim_{x \to \infty} \left( 1 + \frac{1}{x} \right)^{x^2} = e 
$$

studied in Exercise 65.
a) Graph 

$$ 
f(x) = \left( 1 + \frac{1}{x} \right)^x
$$

$$ 
g(x) = \left( 1 + \frac{1}{x} \right)^{x^2} 
$$

together for $x \ge 0$. How does the behavior of \(f\) compare with that of \(g\)? Estimate the value of $\lim_{x \to \infty} f(x)$.

b) Confirm your estimate of $\lim_{x \to \infty} f(x)$ by calculating it with L'Hôpital's rule.

## 67. a) Estimate the value of 

$$
\lim_{x \to \infty} \left( 1 + \frac{x}{x^2 + x} \right)
$$

by graphing $f(x) = \frac{x - x^2 + x}{x}$ over a suitably large interval of $x$-values.


## 68.  Estimate the value of

$$
\lim_{{x \to 2}} \frac{{x^2 - 5}}{{x - 3}}
$$

by graphing. Then confirm your estimate with l'Hôpital's rule.

## 69.  Estimate the value of

$$
\lim_{{x \to 1}} \frac{{2x^2 - (3x + 1)^{1/2} + 2}}{{x - 1}}
$$

by graphing. Then confirm your estimate with l'Hôpital's rule.

## 70. (a) Estimate the value of

$$
\lim_{{x \to 1}} \frac{{x - 1}}{{x - \cos x}}
$$

by graphing $f(x) = (x - 1)/(x - \cos x)$ near $x = 1$ . Then confirm your estimate with l'Hôpital's rule.

(b) Graph $f$ for $0 < x \le 1$.

## 71. The continuous extension of $\sin^2 x \) for \( 0 \le x \le \pi$ .

(a) Graph $f(x) = \sin^2 x$ on the interval $0 \le x \le \pi$. What value would you assign to $f$ to make it continuous at $x = 0$ ?

(b) Verify your conclusion in (a) by finding $\lim_{{x \to 0}} f(x)$ with l'Hôpital's rule.

(c) Returning to the graph, estimate the maximum value of $f$ on $[0, \pi]$. About where is $\max f$ taken on?

(d) Sharpen your estimate in (c) by graphing $f$ in the same window you use to see which graph crosses the x-axis. To simplify your work, you might want to delete the exponential factor from the expression for $f$ and graph just the factor that has a zero.

(e) Sharpen your estimate of the location of max $f$ further still by solving the equation $f' = 0$ numerically.

**Calculator Estimation.** Max $f$ by evaluating $f$ at the locations you found in (c), (d), and (e). What is your best value for $\max f$ ?

## 72. The function $\sin(x)$.

(a) Graph $f(x) = \sin(x)$ on the interval $-7 \le x \le 7$. How do you account for the gaps in the graph? How wide are the gaps?

(b) Now graph $f$ on the interval $0 \le x \le \pi$. The function is defined at $x = \pi/2$, but what happens at $x = \pi/2$? What is going on? Why? What values of $x$ cause trouble?

(c) For $x$ at $x = n\pi$ (integer $n$). Use l'Hôpital's rule to confirm the graph by graphing

$$
f(x) = \frac{{2x}}{{x^2 - 1}}, \quad x \ne 0
$$

Continuing with the graphs in (b), find max $f$ and min $f$ accurately as you can and estimate the values of $f$ at these locations.

## 73.  The place of ln x among the powers of x. The natural logarithm

$$
\ln x = \int_1^x \frac{{1}}{{t}} \, dt
$$

fills the gap in the set of formulas

$$
\int_a^x t^k \, dt = \frac{{x^{k+1} - a^{k+1}}}{{k+1}}, \quad k \ne 0,
$$

but the formulas themselves do not reveal how well the logarithm fits in. We can see the nice fit graphically if we select from (a), (b), and (c) the specific antiderivatives

$$
\int \frac{{1}}{{t}} \, dt = \ln t + C, \quad \ln \left( \frac{{x}}{{a}} \right) = \ln x - \ln a, \quad \text{and}
$$

and compare their graphs with the graph of ln x.

(a) Graph the functions $f(x) = \ln \left( \frac{{x}}{{a}} \right)$ together with $a = 1$, and on the interval $0.5 \le x \le 50$ for $k = 1, \pm 0.5, \pm 0.1,$ and $\pm 0.0$.

(b) Show that

$$
\lim_{{x \to 1}} \frac{{\ln x}}{{x - 1}} = 1.
$$

(Based on "The Place of ln x Among the Powers of x" by Henry C. Finlayson, American Mathematical Monthly, vol. 94, No. 5, May 1987, p. 450.)

## 74.  Confirmation of the limit in Section 5.7, Exercise 42. Estimate the value of

$$
\lim_{{\theta \to 0}} \frac{{\sin \theta - \cos \theta}}{{\theta - \cos \theta}}
$$

as closely as you can by graphing. Then confirm your estimate with l'Hôpital's rule.






 






 

 

 





 









 

