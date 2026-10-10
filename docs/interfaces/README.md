# Interfaces graphiques / Graphical interfaces

Galerie des différentes interfaces de l'outil IMSI-catcher.
Ouvrez [`index.html`](index.html) dans un navigateur pour la version mise en page.

| Fichier | Interface | Type |
|---------|-----------|------|
| [`00-real-capture.png`](00-real-capture.png) | Vue d'ensemble (terminaux + `grgsm_livemon`) | **Capture réelle** fournie avec le projet |
| [`01-simple-imsi-catcher.svg`](01-simple-imsi-catcher.svg) | Tableau terminal de `simple_IMSI-catcher.py` | Reconstitution |
| [`02-grgsm-livemon.svg`](02-grgsm-livemon.svg) | Interface GNU Radio `grgsm_livemon` (spectre) | Reconstitution |
| [`03-grgsm-scanner.svg`](03-grgsm-scanner.svg) | Sortie de `grgsm_scanner` (détection de cellules) | Reconstitution |
| [`04-wireshark.svg`](04-wireshark.svg) | Analyse des trames GSMTAP dans Wireshark | Reconstitution |

## Note

Les fichiers SVG sont des **reconstitutions fidèles** du format de sortie réel de chaque outil :
l'environnement d'exécution ne dispose pas de matériel SDR, il n'est donc pas possible de produire
des captures en direct. Elles reproduisent exactement la structure des colonnes, les libellés et
la mise en page des interfaces d'origine. Aucune donnée personnelle réelle n'y figure (les
derniers chiffres des IMSI sont masqués par des `X`).

The SVG files are **faithful reconstructions** of each tool's real output format. The execution
environment has no SDR hardware, so live screenshots cannot be produced. They reproduce the exact
column structure, labels and layout of the original interfaces. No real personal data is shown
(the trailing IMSI digits are masked with `X`).
