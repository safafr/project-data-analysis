# project-data-analysis

# mini_projet
# Dr. Semmelweis and the discovery of handwashing
## La description
En 1847, le médecin hongrois Ignaz Semmelweis fait une découverte révolutionnaire : il découvre le lavage des mains. Les mains contaminées étaient une cause majeure de fièvre infantile et en imposant le lavage des mains dans son hôpital, il a sauvé des centaines de vies.

Ici, j'ai réanalysé les données médicales recueillies par Semmelweis.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/safafr/project-data-analysis/main?filepath=notebook.ipynb)
# Présentation
ceci est un prototype de projet en analyse de donnée on a utilisé la bibliothèque pandas,matplotlib,numpy et tabulate

# :file_folder: Base de donnée
**La base de donnée "Yearly" contient de donnée:
|   year |   births |   deaths | clinic   |
|-------:|---------:|---------:|:---------|
|   1841 |     3036 |      237 | clinic 1 |
|   1842 |     3287 |      518 | clinic 1 |
|   1843 |     3060 |      274 | clinic 1 |
|   1844 |     3157 |      260 | clinic 1 |
|   1845 |     3492 |      241 | clinic 1 |

**La base de donnée "Monthly" contient de donnée:
|    | date                |   births |   deaths |
|---:|:--------------------|---------:|---------:|
|  0 | 1841-01-01 00:00:00 |      254 |       37 |
|  1 | 1841-02-01 00:00:00 |      239 |       18 |
|  2 | 1841-03-01 00:00:00 |      277 |       12 |
|  3 | 1841-04-01 00:00:00 |      255 |        4 |
|  4 | 1841-05-01 00:00:00 |      255 |        2 |

## conclusion

Ainsi, le lavage des mains a réduit la proportion de décès de 6,7 à 10 points de pourcentage, selon un intervalle de confiance de 95 %. Dans l'ensemble, il semblerait que Semmelweis disposait de preuves solides que le lavage des mains était une procédure simple mais très efficace qui pouvait sauver de nombreuses vies.
La tragédie est que, malgré les preuves, la théorie de Semmelweis - selon laquelle la fièvre du lit de l'enfant était causée par une "substance" (ce que nous appelons aujourd'hui des bactéries) provenant de cadavres de salles d'autopsie - a été ridiculisée par les contemporains. scientifiques. La communauté médicale a largement rejeté sa découverte et en 1849, il a été contraint de quitter définitivement l'hôpital général de Vienne.
L'une des raisons à cela était que les statistiques et les arguments statistiques étaient rares dans la science médicale au XIXe siècle. Semmelweis n'a publié ses données que sous forme de longs tableaux de données brutes, mais il n'a montré aucun graphique ni intervalle de confiance. S'il avait eu accès à l'analyse que nous venons de faire, il aurait peut-être mieux réussi à convaincre les médecins viennois de se laver les mains.


