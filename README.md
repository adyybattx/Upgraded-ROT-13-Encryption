\documentclass{article}
\usepackage[margin=1in]{geometry}
\usepackage{xcolor}
\usepackage{fontenc}
\usepackage{titlesec}
\usepackage{mdframed}
\usepackage{courier}
\usepackage{hyperref}

\definecolor{accentblue}{RGB}{30, 100, 200}
\definecolor{codebg}{RGB}{245, 245, 245}
\definecolor{mutedgray}{RGB}{100, 100, 100}

\titleformat{\section}{\large\bfseries}{}{0em}{}[\titlerule]

\hypersetup{colorlinks=true, linkcolor=accentblue, urlcolor=accentblue}

\begin{document}

\begin{center}
    {\Huge\bfseries Upgraded ROT-13 Encryption}\\[0.4em]
    {\color{mutedgray}\large A slight upgrade from the vanilla ROT-13}
\end{center}

\vspace{1.5em}
\hrule
\vspace{1.5em}

Upgraded ROT-13 Encryption from vanilla ROT-13, which pushes the \textbf{full ASCII range} by \texttt{+13} and encodes output as \textbf{zero-padded 3-digit integers}.

\vspace{1em}

\begin{mdframed}[backgroundcolor=codebg, linecolor=accentblue, linewidth=1.5pt, leftmargin=0em, innerleftmargin=1em, innerrightmargin=1em, innertopmargin=0.75em, innerbottommargin=0.75em]
\ttfamily\small
Classical ROT-13 only shifts A--Z. \\
This shifts the \textbf{entire ASCII space}.\\[0.5em]
The numerical encoding layer on top means even the output \\
format carries no recognizable structure.\\[0.5em]
{\color{accentblue} No letters. No patterns. Just numbers.}
\end{mdframed}

\vspace{1em}

A slight upgrade from the vanilla ROT-13.

\vspace{2em}
\begin{center}
    {\color{mutedgray}\itshape Happy Encrypting.}
\end{center}

\end{document}
