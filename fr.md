# Politique de Confidentialité

[🇬🇧 English Version](README.md)

| Métadonnées | Valeur |
| :--- | :--- |
| **Application** | LudIQ |
| **Dernière mise à jour** | 13 juin 2026 |
| **Version** | 1.0 |

---

## 1. Présentation

**LudIQ** est une application mobile gratuite destinée aux passionnés de jeux de société. Elle a été intégralement conçue pour respecter la vie privée de ses utilisateurs et fonctionne principalement hors ligne.

* **Stockage local exclusif :** Vos données personnelles restent exclusivement sur votre appareil. Votre collection de jeux, l'historique de vos parties, vos scores, vos profils de joueurs (noms et photos) ainsi que vos préférences sont enregistrés localement dans l'espace sécurisé de votre téléphone. Aucun serveur tiers n'en conserve de copie.
* **Sans compte ni publicité :** L'utilisation de l'application ne nécessite aucune création de compte ni adresse e-mail. L'application est totalement exempte de publicité, ne contient aucun traceur publicitaire et ne procède à aucune revente de données.
* **Flux réseau minimaux :** Les seules informations qui quittent votre appareil sont les requêtes techniques adressées à l'API de BoardGameGeek pour afficher les fiches de jeux, ainsi que le texte des descriptions de jeux transmis à un service de traduction lorsque vous utilisez l'application en français. Aucune de ces requêtes ne permet de vous identifier personnellement.

La présente politique détaille l'ensemble de ces traitements avec une transparence totale.

---

## 2. Responsable du traitement

L'éditeur de l'application LudIQ est responsable du traitement de vos données au sens du Règlement Général sur la Protection des Données (RGPD).

> 📋 **Informations sur l'éditeur :**
> * **Éditeur :** GODINEAU Savinien
> * **Statut :** Développeur individuel
> * **Numéro d'identification :** Non applicable
> * **Adresse de contact :** Ludiq.support@gmail.com
> * **Contact dédié à la protection des données :** savi.godineau@gmail.com

Pour toute question relative à la présente politique ou à la gestion de vos données, vous pouvez nous écrire directement aux adresses e-mail indiquées ci-dessus.

---

## 3. Données concernées

LudIQ agit comme un compagnon de jeu de table. Pour fonctionner, l'application traite des catégories de données bien précises, dont la quasi-totalité ne quitte jamais votre terminal.

### 3.1. Données stockées localement sur votre appareil
Les données suivantes sont enregistrées dans l'espace de stockage privé et cloisonné de l'application. Elles ne sont ni transmises à l'éditeur, ni accessibles par ce dernier ou par un tiers :
* **Votre collection :** Jeux possédés, extensions, listes d'envies, favoris et filtres personnalisés.
* **Vos parties :** Sessions de jeu enregistrées, dates, durées, configurations de jeu et joueurs présents.
* **Vos scores et statistiques :** Résultats détaillés par joueur, historique des scores et bilans graphiques.
* **Profils des joueurs :** Noms ou pseudonymes saisis manuellement, ainsi que les photos ou avatars locaux associés.
* **Vos préférences :** Langue de l'interface, paramètres d'affichage et mémoire locale de recherche de l'onglet Explorer.

✏️ **Contrôle utilisateur :** Vous conservez le contrôle absolu de ces données. Vous pouvez les modifier ou les supprimer à tout moment directement depuis l'application, ou les exporter vous-même au format **JSON**. La désinstallation de l'application entraîne la suppression définitive et irréversible de toutes ces données de votre appareil.

### 3.2. Données échangées avec des services tiers
Certaines fonctionnalités connectées requièrent des appels réseau à des bases de données en ligne. Le détail rigoureux de ces échanges figure à l'**Article 5**.

---

## 4. Permissions de l'appareil

L'application peut solliciter l'accès à certaines fonctionnalités de votre système. Cet accès est systématiquement déclenché par une action explicite de votre part et reste strictement cantonné à sa finalité.

| Permission | Usage dans LudIQ | Transmission des données |
| :--- | :--- | :--- |
| **Photos & Appareil photo** | Permet de sélectionner un avatar pour un profil joueur ou pour vous-même. | L'image choisie est copiée localement dans l'espace privé de l'application. **Aucune photo n'est envoyée sur un serveur.** |
| **Enregistrement Galerie / Stockage** | Permet de sauvegarder dans votre galerie une image de bilan de fin de partie ou de statistiques à partager. | L'image est générée localement sur l'appareil et enregistrée uniquement à votre demande expresse. |
| **Accès aux fichiers / Stockage** | Permet d'importer ou d'exporter votre fichier de sauvegarde au format JSON via le système de partage natif. | Vous sélectionnez vous-même le fichier cible. L'application n'explore pas le reste de vos documents. |

*Vous pouvez refuser ou révoquer ces permissions à tout moment dans les Réglages du système d'exploitation de votre téléphone. Le cas échéant, les fonctionnalités associées seront simplement indisponibles.*

---

## 5. Services tiers et destinataires des données

LudIQ s'appuie sur un écosystème d'infrastructure minimal pour enrichir l'expérience utilisateur. Ce tableau détaille la nature des flux, leur destinataire et leur finalité.

| Service | Données transmises | Finalité | Prestataire et Politique |
| :--- | :--- | :--- | :--- |
| **BoardGameGeek** | Termes de recherche et identifiants des jeux consultés. *(Aucun nom, profil ou statistique n'est envoyé)*. | Récupération en temps réel des fiches de jeux publiques (noms, images, notes, descriptions, classements). | BoardGameGeek<br>🔗 [Politique de confidentialité](https://boardgamegeek.com/privacy) |
| **Catalogue de jeux** | Requêtes techniques de consultation de données publiques (classement BGG). | Alimenter de manière fluide le catalogue de suggestions de l'onglet "Explorer". | Supabase & Cloudflare Workers<br>*(Zéro donnée personnelle)* |
| **Service de traduction** | Texte brut des descriptions de jeux (en anglais). *(Actif uniquement si l'app est en français)*. | Traduction automatique instantanée des fiches de jeux en français pour le confort de lecture. | DeepL API<br>🔗 [Politique de confidentialité](https://www.deepl.com/privacy) |
| **Hébergement technique** | Métadonnées réseau standard (telles que l'adresse IP de connexion) indispensables au routage. | Routage sécurisé des requêtes de l'application et mise en cache des données publiques de jeux pour optimiser les performances. | Cloudflare Workers<br>🔗 [Politique de confidentialité](https://www.cloudflare.com/privacypolicy/) |

### 🔒 Garantie d'absence de pistage
Pour être parfaitement complet, LudIQ **n'utilise aucun** :
* Outil de mesure d'audience ou d'analyse comportementale.
* Outil ou régie publicitaire.
* Traceur ou outil tiers de rapport de plantage (ex: Firebase Crashlytics).
* Service de la suite Google Firebase.

La présente version est intégralement gratuite, sans publicité et ne propose aucun achat intégré.

### 5.5. Protection assurée par les tiers
Nous sélectionnons exclusivement des prestataires d'infrastructure réputés offrant de solides garanties en matière de sécurité des données. Lorsque des flux techniques transitent par ces intermédiaires, ces derniers sont contractuellement tenus d'assurer un niveau de protection rigoureux et conforme à la législation européenne.

---

## 6. Bases légales des traitements

Conformément à l'**Article 6 du RGPD**, les traitements mis en œuvre reposent sur les fondements juridiques suivants :
1. **Exécution d'un contrat / Fourniture du service :** Le stockage local de vos collections, scores et profils est strictement nécessaire pour vous délivrer les fonctionnalités de l'application que vous choisissez d'utiliser.
2. **Intérêt légitime :** L'interrogation du catalogue public de jeux et la traduction automatisée répondent à notre intérêt légitime de vous proposer une application riche, fonctionnelle et localisée en langue française.
3. **Consentement :** Les accès aux fonctionnalités matérielles (photos, appareil photo, stockage) reposent exclusivement sur votre consentement, que vous accordez ou retirez via les invites de permissions natives de votre système.

---

## 7. Transferts hors de l'Union européenne

En raison de la nature des prestataires d'infrastructure retenus, certaines métadonnées de routage technique (comme l'adresse IP) peuvent être traitées en dehors de l'Espace Économique Européen (EEE), notamment par la société **Cloudflare, Inc.** aux États-Unis.

Ces flux sont strictement encadrés par des garanties juridiques appropriées, incluant les **Clauses Contractuelles Types (CCT)** validées par la Commission européenne, garantissant un niveau de sécurité équivalent. Aucune donnée d'identité n'est concernée.

---

## 8. Durée de conservation

* **Données locales :** L'ensemble des données décrites à l'Article 3.1 demeure sur votre terminal tant que l'application reste installée ou que vous ne décidez pas de les purger manuellement. Elles sont effacées instantanément lors de la désinstallation de LudIQ.
* **Requêtes réseau :** Les flux techniques adressés aux serveurs intermédiaires et aux API sont éphémères, anonymes et dissociés de tout profil utilisateur. Les caches de fiches de jeux publiques sont temporaires.

---

## 9. Vos droits

En vertu du RGPD, vous disposez de droits d'accès, de rectification, d'effacement, de limitation, d'opposition et de portabilité sur vos données personnelles.

L'architecture locale ("local-first") de LudIQ vous permet d'**exercer l'immense majorité de ces droits de manière totalement autonome**, sans notre intervention :
* **Accès & Portability :** Vous pouvez visualiser l'intégralité de vos informations dans les écrans de l'application et générer un export complet au format JSON quand bon vous semble.
* **Rectification :** Vous pouvez modifier à la volée vos fiches de jeux, vos scores, l'historique des parties et les fiches des joueurs.
* **Effacement :** Vous pouvez supprimer un historique, réinitialiser l'onglet Explorer ou simplement désinstaller l'application pour effacer l'intégralité des données en un clic.

Pour retirer un consentement lié aux permissions, rendez-vous dans les réglages système de votre téléphone. Pour toute demande d'exercice de droit nécessitant une action de notre part, contactez-nous à **savi.godineau@gmail.com**. Nous vous répondrons dans le délai légal d'un mois.

Vous disposez également du droit d'introduire une réclamation auprès de l'autorité de contrôle compétente. En France, il s'agit de la **CNIL** (Commission Nationale de l'Informatique et des Libertés) sur son site [www.cnil.fr](https://www.cnil.fr).

---

## 10. Sécurité

Vos données locales bénéficient de la sécurité native du système d'exploitation de votre smartphone (cloisonnement des applications / bac à sable, et chiffrement matériel de l'appareil s'il est activé). Tous les flux réseau documentés à l'Article 5 font l'objet de connexions chiffrées de bout en bout (**HTTPS**).

*Conseil : Aucun système n'étant infaillible, nous vous recommandons vivement de sécuriser l'accès à votre terminal (code, schéma ou biométrie) et d'effectuer des exports JSON réguliers pour prémunir vos statistiques de toute perte matérielle.*

---

## 11. Protection des mineurs

LudIQ est une application tout public, mais elle ne s'adresse pas spécifiquement aux enfants et nous ne collectons sciemment aucune donnée de mineurs. Si vous suspectez qu'un mineur nous a transmis des informations par e-mail, contactez-nous pour que nous les supprimions.

Les profils de joueurs créés localement peuvent correspondre à des enfants (membres de la famille, amis). Ces profils **restent confinés à votre téléphone**. En les saisissant, vous certifiez disposer du droit ou de l'autorité parentale nécessaire pour renseigner ces pseudonymes locaux.

---

## 12. Modifications de la politique

Cette politique de confidentialité est susceptible d'évoluer pour refléter les futures mises à jour de l'application ou des obligations légales (par exemple, si une future version intègre des fonctionnalités premium ou des achats intégrés). Toute modification majeure sera signalée directement dans l'interface de l'application ou sur sa page d'hébergement web en amont de son application. La date de dernière mise à jour en tête de page fait foi.

---

## 13. Contact

Pour toute question ou demande relative à votre confidentialité :

* **E-mail :** Ludiq.support@gmail.com
* **Éditeur :** GODINEAU Savinien
* **URL du document :** https://ludiq-support.github.io/LudIQ-Privacy-Policy/
