# File d'attente de publication

Branche `file-attente` : contenus rédigés, non publiés (jamais fusionnée telle quelle dans `main`).
Chaque vendredi, la publication copie 1 à 2 fichiers vers `blog/` ou `guide-pratique/`, remplace
`{{DATE_ISO}}` (AAAA-MM-JJ), `{{DATE_FR}}` (ex. « 27 novembre 2026 ») et `{{VERIF_FR}}` (date de re-vérification des faits),
puis met à jour sitemap, _redirects, llms.txt, cartes du blog / du guide, liens « À lire aussi ».
`manifest_blog.json` : titre, tag, extrait, points à re-vérifier avant mise en ligne.
