# Julia logo for LaTeX

This is a LaTeX version of the logo implemented by John Wickerson ([https://johnwickerson.github.io/]) and describe on stackexchange: [https://tex.stackexchange.com/a/113557]. It has been updated to  match official Julia colors and font ([https://github.com/JuliaGraphics/julia-logo-graphics]).

The official font is Tamil MN font, which is included (version 12.0d2e1). Note that although this font is included in macOS, macOS High Sierra has a newer version that has a slightly different shape.

Note that this package requires the LaTeX package `fontspec` and usage of `lualatex` or `xelatex`.

## Usage

Check out the [example](example.tex) or:

``` latex
\usepackage{julialogo}

\begin{document}

This is the \julia~logo

\end{document}
```
