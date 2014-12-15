## Latex Graphics

#### Packages
```latex
\usepackage{graphics} % includegraphics
\usepackage{subfigure} % subfigure
```

#### Syntax
```latex
\includegraphics[attr1=val1, attr2=val2, ..., attrn=valn]{imagename}
```

#### Examples
```latex
% width = 34% of the text width
\includegraphics[width=0.34\textwidth]{FIGS/figlp.pdf} 

% height = 40% text width trim=left bottom right top, clip should set to true
\includegraphics[height=0.4\textwidth,trim=45mm 105mm 45mm 45mm, clip=true]{FIGS/articulated.pdf} 
```

#### General References
* [Latex/Importing Graphics](http://en.wikibooks.org/wiki/LaTeX/Importing_Graphics)

