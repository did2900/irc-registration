# irc-registration

Page d'inscription simple pour IRC.

## Utilisation

1. Ouvrez `index.html` dans un navigateur.
2. Remplissez le formulaire avec votre pseudo, âge, ville et l'adresse IP du serveur.
3. Cliquez sur "Se connecter" pour afficher la confirmation.

## Mise en ligne

Après avoir poussé sur la branche `main`, GitHub Actions publiera automatiquement le site sur GitHub Pages.

Le domaine personnalisé est configuré dans le fichier `CNAME` :

` tchaat.org `

Pour que cela fonctionne, ajoutez ces enregistrements DNS chez votre fournisseur de domaine :

- type `A` vers `185.199.108.153`
- type `A` vers `185.199.109.153`
- type `A` vers `185.199.110.153`
- type `A` vers `185.199.111.153`

Ensuite, GitHub Pages servira votre site depuis `https://tchaat.org`.
