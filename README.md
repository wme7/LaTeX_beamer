# LaTeX course : Beamer module
LaTex Beamer module's sample files and figures:

## Goal:
Build a simple presentation that contains:
- S1 : Title page
- S1 : Outline page
- S1 : Introduction with Loren Lipsum
- S1 : A frame that contains a list
- S1 : A frame that contains a table
- S1 : A frame with blocks
- S1 : A frame with a code
- S1 : A two-column frame that contains a figure
- S2 : A frame with list with overlays
- S2 : A frame with figures overlays
- S3 : A frame with breaks
- S3 : Introduce Fotenotes
- S3 : Build a Bibliography with bibtex

## Starting hint:
```latex
% Set Beamer class
\documentclass{Beamer}

% Set theme and color scheme, see [1].
\usetheme{Warsaw}
\usecolortheme{wolverine}

% Load basic packages
\usepackage{lipsum}

% Set basica parameters
\title{My Presentation}
\subtitle{using Beamer class!}
\author{Manuel A. Diaz}
\institute{University of Poitiers}
\date{\today}

% Beging document
\begin{document}

\begin{frame}
    \titlepage
\end{frame}

\begin{frame}{Outline}
    \tableofcontents
\end{frame}

%%%%%%%%%%%%%%%%%%%
\section{Section 1}
%%%%%%%%%%%%%%%%%%%

\subsection{Method 1}
\begin{frame}{Method 1}
    I tried this method, but didn't work.
\end{frame}

\subsection{Method 2}
\begin{frame}{Method 2}
    I tried this other method. It worked by don't known why!?
\end{frame}

%%%%%%%%%%%%%%%%%%%
\section{Section 2}
%%%%%%%%%%%%%%%%%%%
\begin{frame}{Some Results}
    This is what I got ...
\end{frame}

\end{document}
```

<img src="./figures/Mach03.png" alt="Subsonic Monopole" width="200"/>
<img src="./figures/Mach12.png" alt="Supersonic Monopole" width="197"/>

## References
1. The Beamer theme matrix by [hartwork.org](https://hartwork.org/beamer-theme-matrix/),
2. The Beamer tutorial by [overleaf.com](https://www.overleaf.com/learn/latex/Beamer_Presentations%3A_A_Tutorial_for_Beginners_(Part_1)—Getting_Started),
3. The Markdown [cheat sheet](https://www.markdownguide.org/cheat-sheet/).