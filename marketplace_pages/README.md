# Pages Marketplace — Export PDF

Pages statiques bilingues FR/EN, sans dépendance, JavaScript, formulaire ni outil de suivi.

- `index.html` : accueil
- `privacy.html` : confidentialité
- `terms.html` : conditions d’utilisation
- `support.html` : assistance via les tickets GitHub

## Publication GitHub Pages

Ces fichiers ne sont pas encore publiés par leur seule création locale.
Après commit et push, dans Settings → Pages, choisir Deploy from a branch, la branche `main` et le dossier `/ (root)`.
Le dossier `marketplace_pages` est servi comme sous-répertoire. GitHub ne propose pas ce dossier directement comme racine dans le déploiement par branche.

Si aucun domaine personnalisé n’est configuré, les adresses attendues après publication sont :

- https://jmoutsinga.github.io/google-drive-export-gdoc-to-pdf/marketplace_pages/
- https://jmoutsinga.github.io/google-drive-export-gdoc-to-pdf/marketplace_pages/privacy.html
- https://jmoutsinga.github.io/google-drive-export-gdoc-to-pdf/marketplace_pages/terms.html
- https://jmoutsinga.github.io/google-drive-export-gdoc-to-pdf/marketplace_pages/support.html

Vérifier les liens en navigation privée avant de les renseigner dans Marketplace. Activer Issues dans Settings → General → Features si nécessaire.

Les textes décrivent le code Apps Script fourni dans la conversation (export à la demande via DriveApp, sans serveur externe ni base de données). Vérifier leur concordance avec la version réellement publiée, notamment si la journalisation ou les traitements évoluent. Le README du dépôt utilise un libellé de menu différent : l’assistance utilise une formulation générique pour rester exacte.

La mise en ligne de ces pages ne vaut pas validation OAuth ou Marketplace. La vérification éventuelle du domaine pour OAuth reste une étape distincte.
