# My Pandoc User Setting & Template

Custom template can be found at `my-template/`

-  `template-th.tex`: template for using thai language with followings pandoc variables (can be used in markdown YAML header)
   -  `font-th`: Thai font family, if not provided, default is "TH Sarabun New".


To convert `test.md` to `test.pdf` using `template-th.tex` in the same dir, use the following shell command.


```zsh
pandoc test1.md -o test1.pdf --template template-th.tex --pdf-engine=xelatex
```