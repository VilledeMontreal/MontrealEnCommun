([Français](#french-version))

<a id='english-version' class='anchor' aria-hidden='true'/>

# Soukaoutils
Soukaoutils is a tools sharing space where users can let out any of their belongings for a stated daily fee. A registered member can reserve a tool for any period of time when the tool is available.


______________________  
([English](#english-version))

<a id='french-version' class='anchor' aria-hidden='true'/>

# Soukaoutils
## Sommaire
Soukaoutils est une application de partage d’outils. Un utilisateur peut afficher ses outils pour location et préciser le montant à payer par jour.

## Besoin
Rendre disponible une plateforme de location des objets et outils. Un utiliateur peut ajouter ces objets et determine une somme de location par jour. Les gens intéressés pouraient consulter les objets disponibles et faire leurs réservations selon leurs besoins.
## Solution
### Cas d'usages
#### Cas d'usage I : Authentification
<Détails>
#### Cas d'usage II : Publier un objets pour location
<Détails>
#### Cas d'usage III : Faire une réservation
<Détails>
### Détails techniques
#### Architecture  
Le service de partage est assuré par trois composants :
-	Un serveur d’autorisation
-	Un serveur de ressources disponibles comme service API
-	Un portail client pour gérer les locations 

![Image of OAuth 2.0](https://github.com/VilledeMontreal/soukaoutils/raw/master/OAuth20-MeC.GIF)

Le serveur d’autorisation reconnait les identités de plusieurs fournisseurs. Il est aussi extensible pour accepter n’importe quel autre fournisseur qui implémente le protocole OIDC. Il permet aussi de définir les rôles des utilisateurs et les scopes des applications clientes. Les identités des fournisseurs externes sont associées à une identité locale construite avec l’identité ASP.Net Core.
#### Modules
- <a class='anchor' href='../../R%C3%A9f%C3%A9rentiel/ASP.NET%20Core/Readme.md'>ASP.Net Core</a>  
- <a class='anchor' href='../../R%C3%A9f%C3%A9rentiel/OpenIddict'>OpenIddict</a>  
#### APIs
Faire référence à l'inventaire des APIs au besoin  
#### Dépendendance
<Ajouter les dépendences>
### Guides d'opération
Démarrer les 3 composants:
```
https://localhost:5001/   -- Serveur d'identité unique
https://localhost:5002/   -- Application cliente
https://localhost:6001/   -- Serveur de ressources (Open Data)
```
Commencer par la création d'un nouveau compte utilisateur. Il est possible d'utiliser un compte d'un autre fournisseur OIDC (Google, Azure sont déjà configurés).
Les 3 utilisateurs suivants sont préconfigurés:

`admin@soukaoutils.com`       Rôle *Admin*

`manager@soukaoutils.com`     Rôle *Manager*

`joe@soukaoutils.com`        Pas de rôle en particulier

Utiliser le mot de passe `P@ssw0rd`

### Plan de migration
<Ajouter le(s) plan(s) de migration>
