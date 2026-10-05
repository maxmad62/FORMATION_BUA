# Formations BUA

Site des supports de formation, en ligne et sur clé USB.

## Modifier le contenu

- Une page = un fichier Markdown dans `docs/`
- Le menu se règle dans la section `nav` de `mkdocs.yml`
- Chaque modification sur `main` republie le site tout seul

## Clé USB (hors ligne)

1. Onglet Actions, dernier passage vert, artefact `site-cle-usb`
2. Dézippe sur la clé et ouvre `index.html`

## En local

```
pip install -r requirements.txt
mkdocs serve
```
