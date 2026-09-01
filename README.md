# unhaze-privacy

La politique de confidentialité d'**Unhaze**, hébergée sur Vercel. Un seul
fichier statique, aucun build.

- `index.html` — allemand puis anglais sur la même page. L'app est allemande,
  l'examinateur d'Apple lit l'anglais : les deux doivent y être.

## Les conditions d'utilisation ne sont pas ici

Unhaze pointe sur le **CLUF standard d'Apple**, celui qu'App Store Connect
applique par défaut. Tant que l'app n'impose aucune condition propre — pas de
compte, pas de contenu publié, pas de service en ligne — en écrire un
n'ajouterait rien et ferait un document de plus à tenir à jour. L'URL est dans
`lib/legal.ts` du dépôt Unhaze.

## ⚠️ Cette page affirme qu'il n'y a aucune analyse

« Kein Tracking, keine Werbung, keine Analyse ». C'est vrai aujourd'hui et ça
cessera de l'être le jour où PostHog sera branché — le paquet est déjà installé
dans l'app, mais importé nulle part. **Modifier cette page AVANT ce
changement**, pas après : une politique qui dément le comportement réel de
l'app est plus grave qu'une politique absente.

Même chose pour l'ATT (`expo-tracking-transparency`, déclaré mais sans code) le
jour où des Apple Search Ads tourneront.

## Après tout changement

1. Pousser ici — Vercel redéploie tout seul.
2. Vérifier que l'URL répond, et que la date en haut de page a bougé.
3. L'URL doit rester identique dans `lib/legal.ts` **et** dans le champ
   *Privacy Policy URL* d'App Store Connect.
