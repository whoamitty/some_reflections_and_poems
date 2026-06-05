# Présentation de Nix et Nixos


## Introduction 

Bonjour
Tout d'abord
Je vais aborder mon sujet
D’une manière abordable
Par ses bord
Ses limites 
Votre imagination
C’est ça voici sa seul limite
Autrement dit, nixos est sans limite
Libérez votre esprit
Et vous accorderez à nix la reconnaissance qu’il mérite  

Je m'appelle [T'auras pas mon nom],  
je suis en 1ere année de Licence spi et  
J’aimerais vous présenter aujourd'hui nix et nixos  



### 1. Je vais commencer par Nix
- Un packet est un logiciel ou ensemble de logiciels

Nix est :
- Un Gestionnaire de packet et de configuration et
- Un Language
Il fait bien plus, mais ce sont ces points que nous traiterons

Il rend votre système
- 1erement Atomique
S'il y a une erreur lors d'une installation, ou mise à jour
l'opération est annullé.
Et tout est comme si rien ne s'était passé.
Soit aucune erreur au cours du procéssus, soit rien par annulation

Il rend votre système
- 2emement Reproductible 
Si votre ordinateur explose, ou quoi que ce soit de dramatique ...  
Alors vous pouvez récupérer votre configuration écrite en language nix  
Et la mettre sur un nouvelle ordi.  
Laissez nix faire le travaille, tout ce reproduiras à l'identique  


- Et 3emement, nix isole vos packets  
Les packet logiciels sont installés dans leur propre environnement isolé, avec leurs propres dépendances et configurations.  
Les logiciels ne peuvent pas modifier les configurations ou les dépendances d'autres logiciels.  
Cela garantit la stabilité et la sécurité du système en évitant les problèmes de dépendances et de configurations.  

nix est Disponible sur mac et les systèmes gnu/linux


### 2. Maintenant, passons à Nixos

gnu/linux est un systeme d'exploitation  
disons, comme windows ou macos  
il a [1105](https://distrowatch.com/search.php?ostype=Linux&category=All&origin=All&basedon=All&notbasedon=None&desktop=All&architecture=All&package=All&rolling=All&isosize=All&netinstall=All&language=All&defaultinit=All&status=All#simpleresults) dérivés enregistrés sur distrowatch
et [416](https://distrowatch.com/search.php?ostype=Linux&category=All&origin=All&basedon=All&notbasedon=None&desktop=All&architecture=All&package=All&rolling=All&isosize=All&netinstall=All&language=All&defaultinit=All&status=Active#simpleresults) avec un dévellopement actif  
comme fedora, debian, ubuntu(dérivé de debian) ou encore Nixos !  

Voici ce qui le distingue des autres distributions:
- Nixos utilise nix pour gérer ses mises à jours, et configurations.
- Et il est Immuable, c'est à dire que :
Les configurations et les données déffinissants l'intégrité du système sont stockées de manière à ce qu'elles ne puissent pas être modifiées accidentellement ou intentionnellement.

Les changements sont effectués par la création d'une nouvelle versions du systeme, plutôt qu'en le modifiant.


3. Création de Distribution facilité
Puisque vous pouvez faire une nouvelle version de votre systeme
assez simplement par nix
Par définition, vous pouvez faire votre distribution
Et donc, la création de Distribution est facilité pour tous
C’est la meilleure chose qui ai pu arrivé à la communauté gnu/linux depuis ses débuts jusqu’à maintenant(à mon avis)



# Conclusion



## Poème à tous la distrib création
```
Immuable
Atomique
Reproductible

Si le présent ne plaît pas 

Un faux pas ?

Soit tranquille

T’as le Rollback facile  !



Unique cible, l’intégrité 
Ta sécurité 

Un système 

Qui t'aime

Que t’aime 

Sans faille 

Sans fuite  

Pas de Gaz part

Pas de bombe



Mais si, les barrières tombent

Grâce à un language

Qu’importe ton age

Ou combien t’es sage

Verdict du sondage

Crée ta variation

Linuxiens, rassemblement !!!

En NIXOS, À tous la distrib création ...
```

ven. 11 avril 2025 17:07:53 -03
CC-BY @whoamitty
