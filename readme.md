### Features
- Nice and Formatted Resume using Latex 

## Install Latex 
### For Mac[Install pdflatex]
```
$ brew install basictex.
```
Restart the Terminal

### Update the Latex File with your Details.
```
\begin{document}
\thispagestyle{empty} % this page has no header  
\name{ACHUTHANANDA MP\\[12pt]}% the \\[12pt] adds a blank line after name
```

### Generate the pdf file.
```
$pdflatex achuthResume.tex -o achuthResume.pdf
```

