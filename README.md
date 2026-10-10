# EasyDevis — documents légaux (GitHub Pages)

Site statique public servi par GitHub Pages : <https://easydevis.github.io/legal/>

| Page | URL | Déclarée où |
|---|---|---|
| Information des utilisateurs sur les traitements de données (politique de confidentialité) | <https://easydevis.github.io/legal/politique-de-confidentialite.html> | Chrome Web Store, onglet « Confidentialité » de chaque extension EasyDevis (Veasy, Desmos, WeClever, Copilot) |

## Mettre à jour

1. Modifier le HTML (texte en français, pas de script, pas de dépendance externe :
   la page doit rester lisible sans connexion et sans JavaScript, c'est ce que
   vérifie le relecteur du store).
2. Mettre à jour la ligne « Version : JJ/MM/AAAA » en en-tête de la page.
3. `git commit` puis `git push` sur `main` : GitHub Pages republie en une à deux
   minutes. L'URL ne change pas, rien à redéclarer côté store.

Le même texte est tenu à jour en Markdown et en Word dans le dépôt
`weclever-chrome-ext` (`docs/PRIVACY-POLICY.md`, `docs/PRIVACY-POLICY.docx`).
