# Politique de confidentialité

Dernière mise à jour : mai 2026

## 1. Introduction

Merci d’utiliser cette application (ci-après dénommée « l’Application »). Nous accordons une grande importance à la protection de votre vie privée. Cette politique de confidentialité a pour objet de vous expliquer comment nous collectons, utilisons, stockons et partageons vos informations personnelles lorsque vous utilisez l’Application.

## 2. Les informations que nous collectons

### 1) Données de performance du jeu

- Temps d’écart : la différence entre le moment où vous appuyez sur le bouton d’arrêt et le temps cible (9,9 secondes) pour chaque partie, mesurée au dix millième de seconde, avec des valeurs positives et négatives.
- Horodatage du jeu : l’heure de fin enregistrée pour chaque partie.
- Informations de notation : notation générée selon votre écart (Perfect / Master / Expert / Good / Miss) et selon que vous avez atteint l’écart parfait (Perfect Hit).

### 2) Informations sur l’appareil

- Modèle de l’appareil (par exemple iPhone 15 Pro) : utilisé pour analyser les performances sur différents appareils.
- Version du système d’exploitation (par exemple iOS 18.0) : utilisé pour l’analyse de compatibilité et les statistiques.
- Identifiant unique de l’appareil : un UUID généré automatiquement par le système et stocké localement, utilisé pour identifier le même appareil au fil des sessions de jeu. Il n’est pas téléversé sur le serveur, sauf si vous choisissez de soumettre un score au classement.

### 3) Informations fournies volontairement

- Pseudo : facultatif, vous pouvez le renseigner lorsque vous soumettez un score au classement. S’il est vide, le système affichera « Anonymous ». Votre pseudo est soumis avec les données du score au serveur du classement.

### 4) Préférences de l’application (stockées uniquement localement)

- État du son
- État des retours haptique
- Préférence de langue
- Date du premier lancement

Ces paramètres sont stockés uniquement sur votre appareil et ne sont pas téléversés sur des serveurs.

## 3. Comment nous utilisons vos informations

1. Fonction principale : calculer et afficher votre écart de temps et fournir un retour sur la notation du jeu.
2. Stockage local : enregistrer votre historique de jeu sur votre appareil via Core Data.
3. Service de classement : avec votre consentement, envoyer les résultats du jeu (écart, notation, pseudo, modèle de l’appareil, version du système) au serveur cloud du classement pour que vous et d’autres personnes puissiez les consulter.
4. Identification de l’appareil : utiliser l’UUID local comme identifiant afin de distinguer les résultats selon les appareils.
5. Amélioration du produit : analyser des statistiques anonymisées pour optimiser l’expérience utilisateur.

## 4. Déclaration sur la fonction audio

Cette application utilise les technologies audio suivantes :

| Technologie | Objet | Autorisation du microphone requise |
| --- | --- | --- |
| AVAudioSession | Configurer la session audio et permettre la coexistence avec d’autres applications audio (mode mixage) | Non |
| AVAudioEngine / AVAudioPlayerNode | Lire les effets sonores de l’application (compte à rebours, battements, arrêt, coup parfait, messages d’échec) | Non |
| CoreHaptics | Fournir des retours haptiques (vibration) | Non |

Important : cette application n’utilise pas le microphone et ne collecte aucune donnée audio entrante. Tout l’audio est lu à partir de fichiers sonores intégrés à l’application, sans aucune autorisation de microphone.

Dans la déclaration de permissions de l’App Store, la permission audio déclarée par cette application se limite à la gestion de la session audio système et ne concerne pas l’enregistrement du microphone. L’application ne joue que des effets sonores intégrés et n’accède ni n’enregistre l’entrée audio de l’utilisateur.

## 5. Partage et divulgation des informations

Nous ne vendons, ne louons et ne partageons pas vos informations personnelles avec des tiers.

La seule exception est le cas où vous choisissez de soumettre un score au classement : vos données de jeu seront alors transmises à notre serveur cloud (Supabase). Le fournisseur de services respecte les réglementations applicables en matière de protection des données et nous avons pris des mesures raisonnables pour sécuriser vos données.

## 6. Stockage et conservation des données

- Données locales : votre historique de jeu est stocké de manière permanente sur votre appareil. Vous pouvez réinitialiser l’historique dans les réglages de l’application.
- Données cloud : les scores du classement sont stockés sur le serveur Supabase et conservés selon une limite quotidienne de soumissions. Les scores dépassant la limite ne seront pas soumis, sans affecter vos enregistrements locaux.
- Nettoyage des données : lorsque le nombre d’enregistrements locaux dépasse 1 000, le système supprime automatiquement les plus anciens pour libérer de l’espace de stockage.

## 7. Vos droits

Conformément aux lois applicables en matière de protection des données, vous disposez des droits suivants :

1. Droit d’accès : consulter à tout moment les données personnelles générées dans l’Application.
2. Droit de rectification : corriger les informations inexactes (par exemple, le pseudo).
3. Droit à l’effacement : demander la suppression de vos enregistrements de score.
4. Droit de retirer votre consentement : vous pouvez choisir de ne pas soumettre de score au classement à tout moment. Cette décision n’affecte pas votre utilisation des fonctions principales de l’Application.
5. Droit d’opposition : si vous estimez que le traitement de vos informations personnelles est incorrect, vous pouvez formuler une objection.

Pour exercer ces droits, veuillez nous contacter à l’adresse yufei.cjn@outlook.com.

## 8. Sécurité des données

Nous mettons en œuvre des mesures techniques et organisationnelles raisonnables pour protéger vos informations personnelles, notamment :

- utilisation de HTTPS pour chiffrer toutes les transmissions réseau
- mise en place de règles de sécurité au niveau des lignes (RLS) côté serveur pour limiter l’accès aux données
- chiffrement du stockage local des données

Cependant, nous ne pouvons pas garantir une sécurité absolue lors des transmissions sur Internet. Veuillez conserver vos informations personnelles avec soin.

## 9. Protection des mineurs

Cette application s’adresse à des utilisateurs de tous âges. Pour les utilisateurs mineurs, nous recommandons qu’ils l’utilisent sous la supervision d’un parent ou tuteur. Nous ne collectons pas intentionnellement des informations personnelles concernant des mineurs. Si nous découvrons qu’une information concernant un mineur a été collectée sans le consentement parental, nous la supprimerons dès que possible.

## 10. Mises à jour de la politique

Nous pouvons mettre à jour cette politique de confidentialité de temps à autre. Les politiques mises à jour seront annoncées dans l’Application ou communiquées par d’autres moyens appropriés. Nous vous recommandons de consulter régulièrement cette politique pour savoir comment nous protégeons vos informations.

## 11. Nous contacter

Si vous avez des questions, commentaires ou suggestions concernant cette politique de confidentialité, ou si vous souhaitez exercer vos droits sur les données, veuillez nous contacter via :

- E-mail : yufei.cjn@outlook.com

Nous vous répondrons dès que possible après réception de votre demande.

---

Cette politique de confidentialité prend effet à compter de sa publication. Merci pour votre confiance et votre soutien.
