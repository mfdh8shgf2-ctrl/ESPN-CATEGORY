# Catégorie ESPN — Guide ASN n°8

Application web mobile (iPhone, Android, ordinateur) qui détermine la **catégorie de risque d'un équipement sous pression nucléaire (ESPN)** selon l'annexe 1 du guide ASN n°8, version révisée du 04/09/2012. Elle affiche l'abaque utilisé avec le point calculé (croix rouge) et produit une fiche PDF d'une page.

**Utiliser l'appli :** ouvrir l'adresse du site, puis l'ajouter à l'écran d'accueil (iPhone : Safari › Partager › « Sur l'écran d'accueil » ; Android : Chrome › ⋮ › « Installer l'application »). Elle fonctionne ensuite hors connexion.

## Ce que fait l'appli
- Récipients, tuyauteries, accessoires sous pression (selon V, DN ou les deux : catégorie la plus élevée) et accessoires de sécurité.
- Niveaux N1, N2, N3 ; fluides gaz ou liquides, groupes 1 et 2 ; exceptions « gaz instable » et « TS > 350 °C ».
- Hors périmètre : les ensembles, les générateurs de vapeur (tableau 5 de la directive) et l'exception du tableau 2 (extincteurs, bouteilles respiratoires).

## Sources
- Guide de l'ASN n°8 « Évaluation de la conformité des équipements sous pression nucléaires », version révisée du 04/09/2012, annexe 1 (tableau 6.1, figures 1 à 8).
- Directive 2014/68/UE du 15 mai 2014, annexe II (tableaux 1 à 4 et 6 à 9), JO L 189 du 27/06/2014.

Les abaques sont redessinés à partir de ces règles ; ils ne reproduisent pas les pages du guide.

## Vérification
Les règles ont été transcrites puis contrôlées par 97 cas de test (calcul et interface), par un contrôle croisé de 5 376 points et par un contrôle automatique des 8 abaques (limites, zones, position de la croix). Aucune requête réseau, aucune donnée enregistrée.

## Avertissement
- Outil d'aide à la décision, réalisé à titre personnel. Il ne remplace pas l'analyse réglementaire de l'équipement.
- La qualité d'ESPN, le niveau (N1, N2, N3), l'état et le groupe du fluide sont saisis par l'utilisateur : l'appli ne les détermine pas et ne les vérifie pas.
- L'utilisateur vérifie l'applicabilité de ce référentiel à la date d'utilisation.
- Projet indépendant : il n'est ni réalisé, ni validé, ni soutenu par l'Autorité de sûreté nucléaire, par la Commission européenne ou par un exploitant nucléaire.

## Licence
Licence MIT — voir le fichier `LICENSE`. L'appli est fournie « en l'état », sans garantie.
