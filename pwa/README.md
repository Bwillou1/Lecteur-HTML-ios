# Lecteur HTML PWA

PWA minimaliste pour iPhone, iPad et navigateur desktop qui permet de charger un fichier `.html` local et de l'afficher dans un lecteur embarque.

## Fichiers

- `index.html` : interface, logique JavaScript, mode agrandi, partage et export
- `manifest.json` : configuration PWA
- `sw.js` : cache offline
- `icon.svg` : icone de l'application
- `netlify.toml` : configuration de deploiement Netlify

## Mise en ligne sur GitHub

1. Cree un depot GitHub
2. Envoie ce dossier tel quel
3. Le site statique peut etre servi directement depuis la racine

## Mise en ligne sur Netlify

1. Importe le depot GitHub dans Netlify
2. Laisse le champ `Publish directory` vide ou mets `.`
3. Aucun build command n'est necessaire

## Notes

- Pour le mode offline complet, ouvre la PWA via `http` ou `https`, pas via `file://`
- Sur iOS, l'ouverture directe forcee dans Safari ou Chrome depuis une PWA est limitee par le systeme
