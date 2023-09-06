---
layout: post
title:  "Ajouter un accès à la plateforme Binance sur Crypty"
categories:
- plateforme 
- binance
---

Afin qu'un Trader Bot ou un Ghost Bot puisse fonctionner, ils doivent utiliser un jeton d'API (ou API Token) que vous devez ajouter sur Crypty.

Nous vous proposons de découvrir :
- comment générer des jeton d'API depuis votre compte Binance
- ajouter le jeton sur Crypty en fonction des Bots utilisé.

# Binance - Ghost Bot

Un Ghost Bot n'effectue pas d'opération d'achat ou de vente en votre nom sur Binance, un jeton en lecture seule est donc suffisant à son fonctionnement.

1. Connectez-vous à votre compte Binance
2. Allez sur votre profil -> Gestion API
3. Cliquer sur le bouton `Créer une API`
4. Choisissez `Générée par le système`
5. Nommez la clé, par exemple `Token Crypty Ghost Bots`
6. Cliquez sur `Modifier les restrictions`
7. Selectionnez `Restreindre l’accès aux adresses IP de confiance uniquement (recommandé)`
8. Ajouter l'adresse IP `x.x.x.x` (il s'agit de l'adresse IP utilisée par les Bots)
9. Cliquez sur `Sauvegarder`
11. Enregistrez `API Key` et `Secret Key`


# Binance - Trader Bot

Un Trader Bots va effectuer des opérations d'achat ou de vente en votre nom sur Binance, il a donc besoin de permissions supplémentaires pour trader.

1. Connectez-vous à votre compte Binance
2. Allez sur votre profil -> Gestion API
3. Cliquer sur le bouton `Créer une API`
4. Choisissez `Générée par le système`
5. Nommez la clé, par exemple `Token Crypty Trader Bots`
6. Cliquez sur `Modifier les restrictions`
7. Selectionnez `Restreindre l’accès aux adresses IP de confiance uniquement (recommandé)`
8. Ajouter l'adresse IP `x.x.x.x` (il s'agit de l'adresse IP utilisée par les Bots)
9. Cliquez sur `Activer le trading Spot et sur marge`
10. Cliquez sur `Sauvegarder`
11. Enregistrez `API Key` et `Secret Key`

# Crypty - Ajouter une plateforme

1. Connectez-vous à Crypty.
2. Allez sur `Plateformes`
3. Cliquez sur `+ Ajouter`
4. Indiquez un nom, par exemple `Binance Ghost` ou `Binance Trader` en fonction du type de jeton
5. Insérer la précédente `API Key` dans le champ `Access Key`
5. Insérer la précédente `Secret Key` dans le champ `Secret Key`
6. Sélectionnez `binance` pour le type de plateforme

# Conclusion

Vous pouvez désormais créer votre premier Bot en utilisant le jeton approprié.

Les jetons d'API sont des données sensibles, veillez à bien les protéger.

Crypty met tout en oeuvre pour protéger les données sensibles que vous nous partagez.

Limiter les permissions et restreindre l'accès à l'API en utilisant une adresse IP permet d'éviter que quiconque puisse effectuer des opérations non désirées sur vos comptes.
