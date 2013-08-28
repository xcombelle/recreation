recreation.py
=============

Ce bot permet de lister la liste des pages recrées sur la fr.wikpedia.org

usage typique (depuis un répertoire recreation contenant recreation.py et `__init__.py`)

```
python -m recreation.recreation --prefix 'Utilisateur:Xavier Combelle Bot/Journal des recréations'
```

ou

```
python -m recreation.recreation --prefix 'Utilisateur:Xavier Combelle Bot/Journal des recréations' --verbose
```
avec recreation.timestamp.txt un fichier contenant une seule ligne au format

```
2013-08-10
```
qui est la dernière date à laquelle le bot a été lancée

