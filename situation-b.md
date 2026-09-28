# Remplacement de l'alimentation d'un poste du bureau d'études

[← Retour au portfolio](tp-camille.html)

*PME de métallurgie, 45 postes, site principal — mars 2026 — option SISR*

## Contexte

Le bureau d'études utilise des postes pour consulter et modifier les plans de fabrication. Le poste concerné est un PC assemblé dans un boîtier Cooler Master N200, équipé d'une alimentation be quiet! System Power 7 de 350 W.

## Problématique

Depuis une quinzaine de jours, le poste redémarrait sans prévenir, trois à quatre fois par jour. L'utilisateur perdait les modifications non enregistrées et devait reprendre son travail après chaque redémarrage.

## Démarche

J'ai d'abord consulté l'Observateur d'événements de Windows. Plusieurs événements Kernel-Power 41 confirmaient des arrêts inattendus, sans en préciser la cause. J'ai commencé par la piste logicielle en installant les mises à jour Windows, mais les redémarrages ont continué.

J'ai ensuite suspecté la mémoire vive. J'ai laissé tourner MemTest86 pendant une nuit : aucune erreur détectée. Ce résultat m'a conduit à chercher du côté des autres composants.

À l'ouverture du poste, j'ai constaté que les grilles de l'alimentation étaient très poussiéreuses. Son ventilateur produisait aussi un bruit inhabituel lorsque le PC fonctionnait. Une mesure avec une prise wattmétrique a relevé une consommation de 310 W en pointe à la prise. Cette valeur ne correspond pas directement à la puissance fournie par l'alimentation, mais, avec la poussière et le bruit du ventilateur, elle m'a incité à vérifier cette piste.

J'ai remplacé l'alimentation de 350 W par une Cooler Master MWE Bronze 550 V2 de 550 W et dépoussiéré l'intérieur du boîtier. J'ai ensuite remis le poste en service pour vérifier sa stabilité dans les conditions habituelles d'utilisation.

## Outils mobilisés

- Observateur d'événements Windows pour consulter les événements Kernel-Power 41
- Windows Update pour vérifier la piste logicielle
- MemTest86 pour tester la mémoire vive
- Prise wattmétrique pour mesurer la consommation du poste
- Tournevis cruciforme et bombe à air sec pour le remplacement et le nettoyage
- Alimentation Cooler Master MWE Bronze 550 V2 de 550 W

## Précautions prises

Avant d'ouvrir le boîtier, j'ai arrêté le poste, débranché le câble secteur et maintenu le bouton de démarrage enfoncé quelques secondes. J'ai pris une photo des branchements pour faciliter le remontage. J'ai remplacé le bloc d'alimentation complet sans ouvrir son capot et maintenu les ventilateurs immobiles pendant le dépoussiérage.

## Résultats

Aucun redémarrage intempestif n'a été signalé pendant le mois qui a suivi l'intervention, contre trois à quatre par jour auparavant. L'utilisateur a pu reprendre son travail sans perdre ses modifications à cause de ces coupures. Le remplacement de l'alimentation et le nettoyage ont donc résolu le problème observé.

## Bilan personnel

C'était la première panne matérielle que je diagnostiquais seul. J'étais satisfait d'avoir trouvé une solution, même si j'ai passé du temps sur Windows puis sur la mémoire avant de vérifier l'alimentation. La prochaine fois, je contrôlerai plus tôt l'état des composants et les bruits inhabituels pour mieux orienter mes tests.

---

**Compétences mobilisées** : gérer le patrimoine informatique ; répondre aux incidents et aux demandes d'assistance.
