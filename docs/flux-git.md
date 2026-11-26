# Flux de lucru Git și GitHub

## Repository
https://github.com/gurghiscosmin249-svg/Gestiune-Biblioteca-Desktop

## Inițializare locală
Într-un terminal, în folderul în care vrei să lucrezi:

```bash
git clone https://github.com/gurghiscosmin249-svg/Gestiune-Biblioteca-Desktop.git
cd Gestiune-Biblioteca-Desktop
git status
```

## Ramura pentru prototip și UML
Ramura `feature/prototip-uml` include documentația și diagramele. Modificările se integrează în `main` prin Pull Request.

Pentru a lucra local pe o ramură nouă (dacă nu există):
```bash
git switch -c feature/prototip-uml
```

Pentru a folosi ramura deja creată pe GitHub:
```bash
git fetch origin
git switch --track origin/feature/prototip-uml
```

Exportă interfețele în PNG/PDF din Figma în `prototype/`, apoi:
```bash
git add prototype/
git commit -m "Adauga exporturile PNG ale prototipului"
git push origin feature/prototip-uml
```

## Pull Request
Comparați ramura `feature/prototip-uml` cu `main`, verificați fișierele și integrați schimbările prin Pull Request.

## Sincronizarea copiei locale
```bash
git switch main
git pull origin main
```

## Dovezi pentru profesor
Capturi cu structura repository-ului, ramura, Pull Request-ul integrat, README și prototipul Figma.
