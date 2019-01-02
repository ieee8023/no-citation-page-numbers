In order to use this style you must add these commands before the \documentclass{midl}

```
\RequirePackage{etoolbox}
\patchcmd{\bibliographystyle}{#1}{midl-nopagenum}{}{}

\documentclass{midl}
...
```
