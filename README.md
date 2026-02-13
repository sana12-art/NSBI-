# NSBI - Site vitrine

Ce projet est un site statique (HTML/CSS) : il n'y a pas de build à faire.

## Prérequis
- Python 3 installé
- Un navigateur web

## Lancer le site en local
Depuis la racine du projet :

```bash
python3 -m http.server 8000 --bind 0.0.0.0
```

Puis ouvrir dans le navigateur :
- `http://127.0.0.1:8000/index.html`

## Arrêter le serveur
Dans le terminal où le serveur tourne, faire :
- `Ctrl + C`

## Structure
- `index.html` : structure de la page
- `styles.css` : styles visuels et responsive
- `assets/nsbi-logo.svg` : logo NSBI intégré au site
