The transform is a method to convert a signal from one domain to another domain for extracting some other information contained in the signal which cannot be extracted from the signal in first domain. One of the important families of transforms is „Integral Transform‟. Actually, integral transform is an operator usedto transform a signal into its equivalent form with the help of a „kernel‟ function by integrating the kernel multiplied signal. The integration process involved in transformation has conferred the name as „Integral Transform‟.Fourier transforms play an important part in the theory of many branches of science. A waveform-optical, electrical or acoustical-and its spectrum are appreciated equally as physically picturable and measurable entities, an oscilloscope enables us to see an electrical waveform and a spectroscope or spectrum analyzer enables us to see optical or electrical spectra. Our acoustical appreciation is even more direct, since the ear hears spectra. Wave forms and spectra are Fourier transforms of each other; the Fourier transformation is thus an eminently physical relationship. The theory of Laplace transforms referred to as operational calculus has in recent years become an essential part of the mathematical background required of engineers, physicists, mathematicians and other scientist. This is because in addition to being of great theoretical interest in itself, Laplace transform methods provide easy and effective means for the solution of many problems arising in various fields of science and engineering.So these Fourier and Laplace transforms have various uses in many fields separately. On combining these two transforms i.e. Fourier-Laplace transforms also used for solving differential and integral equations. In this paper we find the Fourier-Laplace transform of some special functions which is help for solving differential equations.

## Fourier series

- Taylor series approximates a complicated function using a series of simpler polynomial functions that are often easier to evaluate. The key idea is to use a series of increasing powers to express complicated yet well-behaved (infinitely differentiable and continuous) functions.
- Unlike Taylor series, a Fourier series can describe functions that are
  not everywhere continuous and/or diﬀerentiable.
- There are also other advantages
  in using trigonometric terms. They are easy to diﬀerentiate and integrate, their
  moduli are easily taken and each term contains only one characteristic frequency.

The particular
conditions that a function f(x) must fulfil in order that it may be expanded as a
Fourier series are known as the Dirichlet conditions

- the function must be periodic
- it must be single-valued and continuous, except possibly at a finite number of finite discontinuities
- it must have only a finite number of maxima and minima within one period
- the integral over one period of `|f(x)|` must converge

> All the terms of a Fourier series are mutually orthogonal

> If we wish to ﬁnd the Fourier series of a non-periodic function only within a ﬁxed range then we may continue the function outside the range so as to make it periodic.

## 3B1B

![](./images/almost-fourier-transformation.png)

![](./images/fourier-transformation.png)

![](./images/decompose-fourier.png)

![](./images/decompose-fourier-2.png)

[selectedsolutions](http://www.selectedsolutions.net/)

[Use LT to solve DE](https://www.quora.com/Can-you-explain-how-the-Laplace-transform-is-used-to-solve-differential-equations-I-know-the-definition-of-the-transform-as-an-improper-integral-and-Ive-seen-a-visualization-of-it-but-Ive-got-no-idea-how-it-helps)

It must also be noted that not all functions have a Laplace transform. For example, the function 1/t does not have a Laplace transform as the integral diverges for all s. Similarly, tan(t) or e^(t^2) do not have Laplace transforms.

[Uniqueness](<https://math.libretexts.org/Bookshelves/Differential_Equations/Book%3A_Differential_Equations_for_Engineers_(Lebl)/6%3A_The_Laplace_Transform/6.1%3A_The_Laplace_Transform>)

[Laplace Transform of Periodic Function](https://proofwiki.org/wiki/Laplace_Transform_of_Periodic_Function)

[Final Value Theorem in Laplace Transform](https://www.electrical4u.com/final-value-theorem-of-laplace-transform/)

## How to memorize those transformation

The behavior of a laplace-transformed function F(s) as s->infinity depends on the function's behavior as x-> 0. For example, functions that don't decay near x=0, such as f(x)=1, f(x)=cos(x), f(x)=cosh(x), f(x)=e^-x , decay like 1/s as s gets large. Functions that decay lineary near x=0, such as f(x)=x, f(x)=sin(x), or f(x)=sinh(x) , decay like 1/s^2 as s gets large. The general relation being: if f(x)->0 faster as x->0, then F(s) has faster decay near s=infinity. You might also want to think about what happens when f(x) is identically zero near x=0.

## What is a Fourier series?

![](./images/function-as-sum.PNG)

Our goal is to express any arbitrary function f(t) as a sum of terms like this, so we need some way to pick out these constants one by one given the data of the function. The easiest one is the constant term. This term represents a sort of center of mass for the full drawing; if you were to sample a bunch of evenly spaced values for the input `t` as it ranges from 0 to 1, the average of all the outputs of the function for those samples will be the constant term C0. Or more accurately, as you consider finer and finer samples, their average approaches C0 in the limit. What I'm describing, finer and finer sums of f(t) for sample of `t` from the input range, is an integral of f(t) from 0 to 1. Normally, since I'm framing this in terms of averages, you'd divide this Integral by the length of the interval. But that length is 1. We want to think of the function as a sum of these rotating vectors.

![](./images/function-as-sum-02.PNG)

Each of these vectors make a whole number of rotations around 0, so its average value of as `t` goes from 0 to 1 will be 0. The only exception is that the constant term; since it stays static and doesn't rotate.

If you wanted to compute a different term like C_k in front of the vector rotating k cycles per second, then the trick is to first multiply f(t) by something which makes that vector hold still.

![](./images/function-as-sum-03.PNG)

## Fourier series

![](./images/change-interval.png)

![What is the difference between Fourier series and Fourier transformation?](https://math.stackexchange.com/questions/221137/what-is-the-difference-between-fourier-series-and-fourier-transformation)
