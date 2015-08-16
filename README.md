# sarau-15-Ago-2015
Sarau Cordas e Cordas, ocorrido em 15 de Agosto de 2015.

### Sync gh-pages:

```
git push --force origin master:gh-pages
git reset --hard origin/gh-pages
```


### Create gh-pages:

```
git checkout --orphan gh-pages
git add .
git commit -m "Initial commit."
git push origin gh-pages
git checkout master
```
