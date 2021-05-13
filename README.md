# commit

https://buzut.net/cours/versioning-avec-git/bien-nommer-ses-commits

```
<type>(<portée>): <sujet>
<description>
<footer>
```
## type
* build : changements qui affectent le système de build ou des dépendances externes (npm, make…)
* ci : changements concernant les fichiers et scripts d’intégration ou de configuration (Travis, Ansible, BrowserStack…)
* feat : ajout d’une nouvelle fonctionnalité
* fix : correction d’un bug
* perf : amélioration des performances
* refactor : modification qui n’apporte ni nouvelle fonctionalité ni d’amélioration de performances
* style : changement qui n’apporte aucune alteration fonctionnelle ou sémantique (indentation, mise en forme, ajout d’espace, renommante d’une variable…)
* docs : rédaction ou mise à jour de documentation
* test : ajout ou modification de tests
* revert: Revert commit

## portée
```
La partie affectée (scope)

C’est la deuxième élément de la première ligne. 
Il nous permet immédiatement de savoir quelle partie du projet est affectée. 
Par exemple pour un site de e-commerce, on pourrait avoir:
  * product, cart ou checkout.
```

