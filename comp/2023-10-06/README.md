## Converting LaTex to Markdown

```sh
pandoc -t markdown_strict --citeproc --standalone paper.tex -o outfile.md
# copy contents of outfile.md into .qmd file
```
