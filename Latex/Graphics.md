## Latex Graphics

#### Packages
```latex
\usepackage{graphics} % figure / includegraphics
\usepackage{subfigure} % subfigure
\usepackage{grffile} % if filename contains dot
```

#### Syntax
```latex
\includegraphics[attr1=val1, attr2=val2, ..., attrn=valn]{imagename}
```

#### Figure
```latex
\begin{figure}[th]
\centering
\includegraphics[width=0.34\textwidth]{FIGS/fig.pdf}\label{fig:your_fig_label}}
\caption{figure_caption}
\end{figure}
```

#### Examples
```latex
% width = 34% of the text width
\includegraphics[width=0.34\textwidth]{FIGS/figlp.pdf} 

% height = 40% text width trim=left bottom right top, clip should set to true
\includegraphics[height=0.4\textwidth,trim=45mm 105mm 45mm 45mm, clip=true]{FIGS/articulated.pdf}

% subfigure with caption and label
\subfigure[env6]{\includegraphics[height=0.28\textwidth]{FIGs/env6-2.pdf}\label{fig:intro-env6poly}}
```

**filename contains dot ('.')**
```latex
\usepackage{grffile} % if filename contains dot
\includegraphics{figures/miura_3_3_me_0.1.def.eps} 
```

#### General References
* [Latex/Importing Graphics](http://en.wikibooks.org/wiki/LaTeX/Importing_Graphics)

