# Minimal MkDocs Page Example for rod2ik/TikZJax

This is an example of a normal MkDocs Markdown page, with **TiZJax** and **tkz-tab**.

Below you will find the two accepted syntaxes, both in Light / Dark Mode :

* Script Syntax: `<script type="text/tikz">... your code here </script>`
* tikzjax code bloc Syntax : ` ```tikzjax  ...your code here ``` `

## Script Syntax

Example 1: (Click on the Light/Dark Button to swap themes)

<script type="text/tikz">
\begin{tikzpicture}[line width=1.2pt, font=\Large]
    \tkzTabInit[lgt=6, espcl=3, lw=1.2pt]
        {$x$/1.5 , $f'(x)=3(x+1)(x-2)$/1.5 , $f(x)=x^3-3x^2-6x+1$/2.5}
        {$-\infty$, $-1$, $2$, $+\infty$}
    \tkzTabLine{,+,z,-,z,+,}
    \tkzTabVar{-/$-\infty$, +/$3$, -/$-15$, +/$+\infty$}
\end{tikzpicture}
</script>

Example 2: (Click on the Light/Dark Button to swap themes)

<script type="text/tikz">
\begin{tikzpicture}[line width=1.2pt, font=\Large]
    \tkzTabInit[lgt=6, espcl=2.5, lw=1.2pt]
        {$x$/1.5 , $f'(x)=\dfrac{(x-1)(x-3)}{(x-2)^2}$/1.8 , $f(x)=x+1+\dfrac{1}{x-2}$/3}
        {$-\infty$, $1$, $2$, $3$, $+\infty$}
    \tkzTabLine{,+,z,-,d,-,z,+,}
    \tkzTabVar{-/$-\infty$, +/$1$, -D+/$-\infty$ / $+\infty$, -/$5$, +/$+\infty$}
\end{tikzpicture}
</script>

## `tikzjax` Code Bloc Syntax

Example 1: (Click on the Light/Dark Button to swap themes)

```tikzjax
\begin{tikzpicture}[line width=1.2pt, font=\Large]
    \tkzTabInit[lgt=6, espcl=3, lw=1.2pt]
        {$x$/1.5 , $f'(x)=3(x+1)(x-2)$/1.5 , $f(x)=x^3-3x^2-6x+1$/2.5}
        {$-\infty$, $-1$, $2$, $+\infty$}
    \tkzTabLine{,+,z,-,z,+,}
    \tkzTabVar{-/$-\infty$, +/$3$, -/$-15$, +/$+\infty$}
\end{tikzpicture}
```

Example 2: (Click on the Light/Dark Button to swap themes)

```tikzjax
\begin{tikzpicture}[line width=1.2pt, font=\Large]
    \tkzTabInit[lgt=6, espcl=2.5, lw=1.2pt]
        {$x$/1.5 , $f'(x)=\dfrac{(x-1)(x-3)}{(x-2)^2}$/1.8 , $f(x)=x+1+\dfrac{1}{x-2}$/3}
        {$-\infty$, $1$, $2$, $3$, $+\infty$}
    \tkzTabLine{,+,z,-,d,-,z,+,}
    \tkzTabVar{-/$-\infty$, +/$1$, -D+/$-\infty$ / $+\infty$, -/$5$, +/$+\infty$}
\end{tikzpicture}
```
