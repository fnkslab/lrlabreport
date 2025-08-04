# lrlabreport

### Template to create a lab-internal report document

0. Use lrlab-report-template.tex to create a report
1. Write your report as a normal (paper-like) document
2. Present it as slides with the `slide` option of `\documentlcass` (if appropriate)

### Template to create your survey/bibliography résumé

0. Use related-work-template.tex to create your résumé of the related work
1. Follow the instructions in the template

### How to link this repository to any existing local latex project folder (a memorandum for administration)
```
$ cd any-latex-or-overleaf-project-folder
$ git init
$ git remote add origin git@github.com:fnkslab/lrlabreport.git
$ git pull origin main
```

If you need to push back the changes to the GitHub remote from the local, do this first:
```
$ git branch -m master main
```

Then, commit and push:
```
$ git commit -a
$ git push --set-upstream origin main
```
