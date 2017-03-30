
# <span style="font-family: serif">L<sup>A</sup>T<sub>E</sub>X</span> Presentations made Quicker

## Introduction

This library provides an easy way to create standarized beamer presentations
within simple steps. Users would be partially isolated with the back-end
environment and would not have to worry about the styles and formattings.

The template is optimized for CJK characters, and is highly suggested that a
Unicode encoding is to be used. Most common characters are rendered properly
in this template.

However, this template is still under heavy development, its appearence and
functional behaviors should be expected to change over time until a
forseeable future where stable versions are anticipated.

## Installation

Copy the template file `lpq.sty` to your project / presentation folder or to the
<span style="font-family: serif">L<sup>A</sup>T<sub>E</sub>X</span> installation
folder where other packages are located.

This template is used after the `\documentclass` invocation and implemented as a
package, which follows the `\usepackage` method.

## Usage

The template could also be found in the template `lpq.sty`.

```tex
% !TEX TS-program = xelatex
% !TEX encoding = UTF-8

\documentclass[compress, aspectratio = 1610]{beamer}
\usepackage{lpq}

\title{Your Title Here}
\author{Author Here}
\institute{Institute Here}
\date{1 January, 1970}

\begin{document}
\begin{lpqcontext}

\section{Lorem Ipsum}
\subsection{Content}
\begin{lpqframe}
  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
  incididunt ut labore et dolore magna aliqua.\n
  Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
  aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
  voluptate velit esse cillum dolore eu fugiat nulla pariatur.\n
  Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia
  deserunt mollit anim id est laborum.
\end{lpqframe}

\end{lpqcontext}
\end{document}
```

Similar approaches can be used.

## Issues
Please report any problems to the issues page, and I will try to fix them
as soon as possible.
