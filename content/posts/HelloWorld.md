---
title: "My very first post"
summary: hello first post
date: 2025-02-09
params:
  math: true
weight: 10
aliases: ["/helloWorld"]
tags: ["blog"]
---

## Getting Started ✨
### How Does Things Work?
## Syntax
### Links
This is a link to **[My Github](https://github.com/faw121)**.

https://github.com/faw121

### Expansions

Let's play hide and seek.
> {{< collapse summary="**Secret Folder 1**">}}
Not here!
{{</ collapse >}}

> {{< collapse summary="**Secret Folder 2**">}}
No-no.
{{</ collapse >}}

> {{< collapse summary="**Secret Folder 3**">}}
You found me!
{{</ collapse >}}

Expansion can be in code!
```text {linenos=true}
you may notice there are line numbers...
just use {linenos=true}
{{< collapse summary="**See this**">}}
Suprise!
{{</ collapse >}}
```

### Maths 🎉
Follow the guide **[here](https://gohugo.io/content-management/mathematics/)** to add math rendering.

This is an inline \(a^*=x-b^*\) equation.
And this $f(x)=\sin{\omega x + \phi}$.

These are also block equations:

$$a^*=x-b^*$$

$$ a^*=x-b^* $$

Double-escape `\\$` the symbol `$`:

A \\$5 bill _saved_ is a \\$5 bill _earned_. 

In integral you should use `\mathrm{d}` for $\mathrm{d}x$.

$$
\begin{align}
I &= \iint\limits_{\Omega} {\mathbf{n} \cdot \mathbf{w_{i}}} \, \mathrm{d}\mathbf{w_{i}}  \\
  &=\int_{0}^{2\pi} \int _{0}^{\pi/2} {\cos\theta}\, \mathrm{d}\theta  \, \mathrm{d}\phi \\
  &= \pi 
\end{align}
$$

Try some matrix.

Assume $M$ represents model transformation, then transformation matrix $Q$ for normal is:

$$
Q = (M^{-1})^{\mathsf{T}}_{3\times 3}
$$

Which transpose looks better?

`\intercal` : $M^{\intercal}$

`\top` : $M^{\top}$

`\mathsf{T}` : $M^{\mathsf{T}}$
