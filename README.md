# Edubull Studio

Static studio for edubull.com. `index.html` is the entry: pick a class, then a subject, then open a simulation.

## Folder layout
```
index.html                      studio home (class -> subject -> simulation)
assets/logo.png
class3/ct/ct-ai-quest.html
class6/science/ecosystem-3d-lab.html
class6/science/holo-solar-system.html
class7/science/acid-base-solutions.html
class7/science/electric-circuit-lab.html
class7/science/science-activities.html
class8/science/cell-explorer-360.html
class8/science/science-activities.html
```
Add a new simulation by dropping its HTML into `class<N>/<subject>/` and adding one entry to the `GAMES` array near the top of the script in `index.html`.
