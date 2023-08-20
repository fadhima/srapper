Le projet
2.1. Initialize

Commence par créer une structure de dossier propre avec le dossier lib, le dossier spec, etc. Créé un Gemfile, un README et fais ton $ git init. Maintenant on peut commencer à travailler
2.2. Dark Trader

Lehman Brothers, impressionnés par ton algorithme d'optimisation d'achat / vente, veut encore faire appel à toi. Leur Chief Digital Officer, très hype, a entendu parler au JT de TF1 d'un "truc révolutionnaire qui s'appelle le bloque-chienne". Il veut en acheter plein. Pour le conseiller, tu vas devoir récupérer le cours de toutes les cryptomonnaies du marché.

En prenant pour source le site CoinMarketCap, fait un programme qui récupère le cours de toutes les cryptomonnaies et les enregistre bien proprement dans un array de hashs. Ton array devra avoir le format suivant :

  a = [

     { "BTC" => 5245.12 },

     { "ETH" => 217.34 },

     etc

  ]

Pour les tests, inspire-toi de la ressource plus haut. Il n'y a pas besoin de faire 36 000 tests, il faut juste arriver à tester 1) le fonctionnement de base de ton programme (pas d'erreur ni de retour vide) et 2) que ton programme sort bien un array cohérent (vérifier la présence de 2-3 cryptomonnaies, vérifier que l’array est de taille cohérente, etc.).

Quelques petites aides pour ce premier exercice :

    Il est possible de faire le programme en n'allant que sur une seule URL. C'est un bon moyen pour faire un programme rapide car ne chargeant pas 2000 pages HTML.
    Tout se jouera sur la rédaction d'un XPath pertinent et précis qui extrait juste ce qu'il faut d'éléments HTML. Puis un bon traitement de ces éléments pour en extraire les 2 infos dont tu as besoin : le nom des crypto et leur cours.
