# Ignite paper source

## Install additional packages

### arxiv-style
```cd src && git clone https://github.com/kourgeorge/arxiv-style.git
cp arxiv-style/arxiv.sty .
```

### nicefrac

```
tlmgr install units
```

## How to build

```
cd src
pdflatex main && bibtex main && pdflatex main
```
