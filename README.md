# lrlabreport
Template to create a lab-internal report document

### How to link this repository to any existing local latex project folder (a memorandum)
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
