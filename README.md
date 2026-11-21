# Portfolio de Samuel Bepouka

Site personnel de **Samuel Bepouka** : Expert BI et Data Analytics, Senior Database Engineer, formateur en IA (RDC).

- Site : <https://bepouka.cloud>
- Contact : samuel@bepouka.cloud
- GitHub : <https://github.com/bepoukas>

## Contenu

Une seule page statique, `index.html` : HTML, CSS et JavaScript, sans dépendance ni étape de compilation. La photo est intégrée dans le fichier. Seules les polices (Google Fonts) sont chargées depuis l'extérieur.

## Hébergement : GitHub Pages

1. Dépôt → **Settings → Pages**.
2. **Source** : *Deploy from a branch*, branche `main`, dossier `/ (root)`.
3. **Custom domain** : `bepouka.cloud` (le fichier `CNAME` le déclare déjà), puis cocher **Enforce HTTPS** une fois le certificat émis.

### DNS chez le registrar de `bepouka.cloud`

Domaine principal (`bepouka.cloud`) :

| Type | Nom | Valeur |
|------|-----|--------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| AAAA | @ | 2606:50c0:8000::153 |
| AAAA | @ | 2606:50c0:8001::153 |
| AAAA | @ | 2606:50c0:8002::153 |
| AAAA | @ | 2606:50c0:8003::153 |
| CNAME | www | bepoukas.github.io |

Ne pas toucher aux enregistrements MX et TXT existants : ils servent à la messagerie `samuel@bepouka.cloud`. La propagation DNS peut prendre de quelques minutes à quelques heures.

## Mise à jour

Modifier `index.html`, puis `git commit` et `git push` sur `main` : GitHub Pages republie automatiquement.
