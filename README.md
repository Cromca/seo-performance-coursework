# Quêtes SEO et performance web

Travaux de Quentin Fuentes réalisés pour le module Accessibilité Web & SEO à Ynov.

Ce dépôt regroupe des réponses aux quêtes et des exemples de pages web : recherche de mots-clés, SEO on-page, redirections, URL canoniques, performance et référencement d’une application React.

## Contenu

| Emplacement | Sujet |
| --- | --- |
| `quete2.md` | Mots-clés et intention de recherche |
| `quete3/` | Pages HTML et URL réécrites avec Apache |
| `Quete4.md` et `quete4/` | SEO technique, redirections et canonical |
| `Quete5.md` | Core Web Vitals et performance |
| `quete6/` | Application React avec génération de pages HTML |
| `tests/verifier_exercices.py` | Vérifications des exercices Apache |

## Pages HTML et redirections

Les fichiers HTML peuvent être ouverts dans un navigateur pour consulter leur contenu. Pour tester les redirections et les règles `.htaccess`, utiliser Apache avec `mod_rewrite` et la configuration indiquée dans [Lancer-les-exercices.txt](Lancer-les-exercices.txt).

Le domaine `monsite.fr` est un exemple d’exercice. GitHub Pages n’exécute pas les règles Apache.

## Application React — quête 6

Installer Node.js et npm, puis lancer :

```bash
cd quete6
npm ci
npm run dev
```

Le serveur de développement utilise `http://127.0.0.1:5176`.

```bash
npm test
npm run build
npm start
```

La compilation génère les versions client et serveur, puis les pages pré-rendues. Les commandes sont celles du projet ; elles n’ont pas été relancées lors de cette mise à jour documentaire.
