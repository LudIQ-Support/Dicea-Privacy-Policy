<!DOCTYPE html>
<html lang="fr" id="html-doc">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Politique de Confidentialité - Dicea</title>
    <!-- Script léger pour transformer ton Markdown en beau HTML automatiquement -->
    <script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
    <style>
        body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif; padding: 2rem 1rem; background: #f8f9fa; color: #333; line-height: 1.6; }
        
        /* Conteneur principal (plus large que le QR code car c'est un document légal) */
        .container { position: relative; background: white; padding: 3rem 2.5rem; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.1); max-width: 800px; margin: 0 auto; text-align: left; }
        
        /* Bouton de langue (le même que sur ta page QR Code) */
        .lang-btn { position: absolute; top: 16px; right: 16px; background: white; border: 1px solid #ccc; border-radius: 20px; padding: 6px 14px; font-size: 0.9rem; color: #555; cursor: pointer; transition: all 0.2s; box-shadow: 0 2px 4px rgba(0,0,0,0.05); }
        .lang-btn:hover { background: #f0f0f0; border-color: #aaa; }
        
        /* Mise en forme du document généré (Tableaux, citations, etc.) */
        .markdown-content h1 { margin-top: 0; color: #111; font-size: 2rem; border-bottom: 2px solid #eee; padding-bottom: 0.5rem; }
        .markdown-content h2 { margin-top: 2rem; color: #222; border-bottom: 1px solid #eee; padding-bottom: 0.3rem; }
        .markdown-content h3 { margin-top: 1.5rem; color: #444; }
        .markdown-content table { border-collapse: collapse; width: 100%; margin: 1.5rem 0; font-size: 0.95rem; }
        .markdown-content th, .markdown-content td { border: 1px solid #ddd; padding: 10px 12px; text-align: left; }
        .markdown-content th { background-color: #f4f6f8; color: #333; }
        .markdown-content blockquote { border-left: 4px solid #01875f; margin: 1.5rem 0; padding: 10px 15px; color: #555; background: #eefaf6; border-radius: 0 6px 6px 0; }
        .markdown-content a { color: #007aff; text-decoration: none; }
        .markdown-content a:hover { text-decoration: underline; }
        .markdown-content code { background: #f4f4f4; padding: 2px 6px; border-radius: 4px; font-family: monospace; font-size: 0.9em; }
    </style>
</head>
<body>
    <div class="container">
        <!-- Bouton pour changer de langue -->
        <button id="lang-btn" class="lang-btn">🇬🇧 English</button>

        <!-- C'est ici que le texte apparaîtra -->
        <div id="content" class="markdown-content"></div>
    </div>

    <script>
        // --- VOS DOCUMENTS OFFICIELS MARKDOWN ---
        const policies = {
            fr: `
# Politique de Confidentialité — Dicea

| Métadonnées | Valeur |
| :--- | :--- |
| **Application** | Dicea |
| **Dernière mise à jour** | 27 octobre 2026 |

---

## 1. Présentation

**Dicea** est une application mobile gratuite destinée aux joueurs de jeux de société. Elle a été conçue pour respecter la vie privée de ses utilisateurs et fonctionne principalement hors ligne.

* **Stockage local par défaut :** Votre collection de jeux, vos parties (photos comprises) et vos scores, vos profils de joueurs (noms et photos) ainsi que vos préférences sont enregistrés dans la mémoire de votre téléphone. Aucun serveur Dicea ne reçoit ni ne conserve ces informations. Si vous activez volontairement les sauvegardes automatiques vers un espace externe, une copie est également écrite dans le seul fichier que vous choisissez.
* **Sans compte ni publicité :** L'utilisation de l'application ne nécessite ni création de compte, ni adresse e-mail. L'application ne contient aucune publicité, aucun traceur publicitaire et ne procède à aucune revente de données.
* **Flux réseau minimaux :** Les informations qui quittent votre appareil sont les requêtes techniques adressées à BoardGameGeek pour afficher les fiches de jeux, le téléchargement des images de jeux depuis le réseau de diffusion d'images de BoardGameGeek, les identifiants BoardGameGeek des jeux transmis à un comparateur de prix pour en estimer le prix, et le texte des descriptions de jeux transmis à un service de traduction lorsque vous utilisez l'application en français. Si vous choisissez un fournisseur de stockage externe, le système d'exploitation lui remet également votre fichier de sauvegarde afin qu'il puisse le conserver et, le cas échéant, le synchroniser.

🔒 **Nuance importante (Contenu vs Métadonnées) :** Les requêtes techniques relatives aux jeux ne comportent aucune des données que vous avez saisies dans l'application : ni votre nom, ni vos profils de joueurs, ni vos statistiques. Comme toute connexion à Internet, elles transmettent néanmoins des données techniques de connexion, telles que votre **adresse IP**. À l'inverse, une sauvegarde externe contient vos données Dicea : elle n'est transmise qu'au fournisseur de stockage que vous avez vous-même choisi, jamais à l'éditeur de Dicea.

---

## 2. Responsable du traitement

L'éditeur de l'application Dicea est responsable du traitement de vos données au sens du Règlement général sur la protection des données (RGPD).

> 📋 **Informations sur l'éditeur :**
> * **Éditeur :** GODINEAU Savinien
> * **Statut :** Développeur individuel
> * **Numéro d'identification :** Non applicable
> * **Adresse de contact :** Ludiq.support@gmail.com

Pour toute question relative à la présente politique ou à la gestion de vos données, vous pouvez nous écrire directement à l'adresse e-mail indiquée ci-dessus.

---

## 3. Données concernées

Dicea agit comme un compagnon de jeu de table. Pour fonctionner, l'application traite des catégories de données bien précises. Elles restent sur votre terminal, sauf si vous activez volontairement une sauvegarde vers un fichier externe ou utilisez une fonctionnalité connectée décrite ci-dessous.

### 3.1. Données stockées localement sur votre appareil
Les données suivantes sont d'abord enregistrées dans l'espace de stockage privé et cloisonné de l'application. Elles ne sont jamais transmises à l'éditeur. En l'absence de sauvegarde externe configurée, elles ne sont pas remises à un fournisseur de stockage tiers :
* **Votre collection de jeux :** Jeux possédés, autres jeux, liste d'envies, extensions et favoris, ainsi que les prix d'achat que vous saisissez et les prix estimés de vos jeux.
* **Vos parties :** Sessions de jeu enregistrées, dates, durées, formats et joueurs présents, ainsi que la note et la photo que vous pouvez y associer.
* **Vos scores et statistiques :** Résultats détaillés par joueur, historique et bilans graphiques.
* **Profils de joueurs :** Les noms ou pseudonymes que vous saisissez manuellement et les photos ou avatars locaux que vous choisissez pour vos profils.
* **Vos préférences :** Langue de l'interface, réglages d'affichage, filtres et mémoire de l'onglet Explorer.

🔒 **Sauvegarde automatique du système désactivée :** Android propose aux applications une sauvegarde automatique de leurs données vers le compte cloud de l'utilisateur. Dicea la **refuse explicitement** : ni la base de données, ni vos photos, ni vos préférences ne sont remises à ce mécanisme. Seul le **transfert direct** d'un ancien téléphone vers un nouveau, opéré localement par le système lors du changement d'appareil, reste autorisé : il ne transite par aucun serveur.

✏️ **Contrôle utilisateur :** Vous conservez le contrôle de ces données. Vous pouvez les modifier ou les supprimer à tout moment directement dans l'application, ou les exporter vous-même au format **JSON**. La désinstallation efface les données privées de l'application sur l'appareil, mais ne supprime pas les fichiers que vous avez placés dans un stockage externe.

### 3.2. Sauvegardes manuelles et automatiques
La sauvegarde automatique est facultative et doit être configurée par vos soins. Vous pouvez choisir le stockage privé de l'application ou créer/rattacher un document dans un emplacement proposé par le sélecteur natif d'Android ou d'iOS, par exemple Google Drive, iCloud Drive, un autre fournisseur compatible ou un stockage local.

Le fichier de sauvegarde **JSON** contient une copie complète des données Dicea décrites à l'Article 3.1, y compris les préférences exportables et les images personnelles nécessaires à une restauration. Après votre sélection, Dicea conserve localement une autorisation technique limitée à ce document afin de pouvoir le remplacer automatiquement après vos modifications. Dicea n'obtient ni l'identifiant, ni le mot de passe, ni le jeton de connexion de votre compte cloud, et n'explore pas les autres fichiers.

Pour résister à une indisponibilité temporaire du fournisseur, Dicea conserve aussi une rotation limitée de deux copies dans son stockage privé. Si le réseau est coupé, le fournisseur système peut différer la synchronisation distante ; Dicea réessaie ultérieurement. L'éditeur ne reçoit aucune copie, ne peut pas consulter le document et ne peut pas confirmer que le fournisseur a terminé son envoi vers ses serveurs.

### 3.3. Données échangées avec d'autres services tiers
Certaines fonctionnalités connectées nécessitent une communication avec des services en ligne. Le détail rigoureux de ces échanges figure à l'**Article 5**.

---

## 4. Permissions de l'appareil

L'application peut vous demander l'accès à certaines fonctions de votre système. Cet accès est systématiquement déclenché par une action explicite de votre part et reste strictement cantonné à sa finalité.

| Permission | Usage dans Dicea | Transmission des données |
| :--- | :--- | :--- |
| **Photos & Appareil photo** | Permet de choisir un avatar pour un joueur ou pour votre profil, une photo pour un jeu, une extension ou une partie, et de **scanner les QR codes** pour importer une partie partagée. | L'image sélectionnée ou le flux vidéo du scan est traité localement dans l'application. **Aucune image n'est transmise à un serveur.** |
| **Enregistrement Galerie** | Permet de sauvegarder dans votre stockage une image de bilan partageable que vous générez vous-même. | L'image est créée localement sur le téléphone et enregistrée uniquement à votre demande expresse. |
| **Accès à un document** | Permet d'exporter, d'importer ou de mettre à jour automatiquement une sauvegarde JSON par l'intermédiaire du sélecteur système. | Vous choisissez vous-même le document. L'accès durable est limité à celui-ci ; l'application n'explore pas le reste de vos fichiers et ne reçoit aucun accès à votre compte cloud. |

*Vous pouvez refuser ou révoquer ces accès à tout moment dans les réglages de votre système d'exploitation ou auprès du fournisseur concerné. Le cas échéant, les fonctionnalités correspondantes seront simplement indisponibles. La sélection d'un document de sauvegarde ne requiert pas une permission générale sur tout votre stockage.*

---

## 5. Services tiers et destinataires des données

L'application s'appuie sur un nombre limité d'infrastructures pour fonctionner. Elle peut aussi, uniquement à votre demande, remettre une sauvegarde au fournisseur de stockage que vous choisissez dans l'interface système.

| Service / Prestataire | Données transmises | Finalité des flux | Prestataire & Politique |
| :--- | :--- | :--- | :--- |
| **BoardGameGeek (API)** | Termes de recherche et identifiants des jeux consultés. *(Zéro donnée utilisateur)*. Requête via proxy Cloudflare. | Récupérer en temps réel les fiches techniques des jeux (nom, note, description, classements). | BoardGameGeek<br>🔗 [Politique de confidentialité](https://boardgamegeek.com/privacy) |
| **Réseau d'images BGG** | Requête HTTP directe vers le domaine \`geekdo-images.com\`. Expose votre **adresse IP** et les visuels consultés. | Télécharger en direct sur votre écran les couvertures et vignettes des jeux de société. | Geekdo, LLC (États-Unis)<br>*(Flux direct sans passer par le proxy de l'éditeur)* |
| **Catalogue de jeux** | Requêtes de lecture seule sur notre index de jeux de société, constitué à partir d'informations publiques. *(Zéro donnée utilisateur)*. | Alimenter la fonctionnalité de découverte et de suggestions au sein de l'onglet **Explorer**. | Opéré par l'éditeur<br>*(Index hébergé chez Supabase, requêtes via Cloudflare)* |
| **Service de traduction** | Texte brut de la description du jeu (en anglais), issue de BoardGameGeek. *(Zéro donnée utilisateur. Flux inactif si l'app est en anglais)*. Requête via proxy Cloudflare. | Traduction automatique des descriptions de fiches de jeux en français, par un modèle d'intelligence artificielle. | Google (API Gemini)<br>*(Le service ne reçoit que les requêtes du proxy de l'éditeur)*<br>🔗 [Politique de confidentialité](https://policies.google.com/privacy) |
| **Comparateur de prix** | Identifiants BoardGameGeek des jeux et extensions, et marché de prix (France, Royaume-Uni ou États-Unis, déduit de la langue de l'application et du pays de l'appareil). *(Zéro donnée utilisateur : ni prix d'achat, ni nom)*. Requête via proxy Cloudflare. | Estimer le prix de vos jeux à partir des offres des boutiques en ligne et proposer le lien vers leur page de prix. | Ludiprix.fr / BoardGamePrices, KP Software Consult ApS (Danemark)<br>*(Le site ne reçoit que les requêtes du proxy de l'éditeur)* |
| **Hébergement technique** | Métadonnées de connexion standard (adresse IP notamment) nécessaires à l'acheminement du trafic. | Routage sécurisé (HTTPS) des requêtes de l'application et mise en cache de performance des données publiques. | Cloudflare Workers<br>🔗 [Politique de confidentialité](https://www.cloudflare.com/privacypolicy/) |
| **Fournisseur de stockage choisi (facultatif)** | Fichier JSON complet de sauvegarde et métadonnées techniques traitées par le système ou le fournisseur. | Conserver et éventuellement synchroniser la sauvegarde à l'emplacement que vous avez choisi. Aucun transit par un serveur Dicea. | Fournisseur sélectionné dans Android/iOS, notamment [Google](https://policies.google.com/privacy) ou [Apple](https://www.apple.com/legal/privacy/), selon votre choix. |

Les liens vers BoardGameGeek et vers la page de prix d'un jeu s'ouvrent dans votre navigateur : la consultation de ces sites relève alors de leur propre politique de confidentialité.

### 🔒 Garantie d'absence de pistage
Pour être parfaitement complet, l'application Dicea n'utilise aucun outil de mesure d'audience, aucun outil de pistage comportemental, aucun outil tiers de rapport de plantage (comme Firebase Crashlytics), aucun service de la suite Google Firebase, et aucune publicité.

### 5.5. Protection assurée par les tiers
Les prestataires techniques intégrés par Dicea sont sélectionnés en tenant compte de garanties appropriées en matière de protection des données. Le fournisseur de stockage externe est, quant à lui, choisi librement par vous dans l'interface du système : son traitement du fichier dépend de votre relation avec lui, de la configuration de votre compte et de sa propre politique de confidentialité. L'éditeur de Dicea ne reçoit ni vos identifiants ni votre sauvegarde et ne contrôle pas les traitements réalisés par ce fournisseur.

---

## 6. Bases légales des traitements

Conformément à l'**Article 6 du RGPD**, les traitements mis en œuvre reposent sur les bases légales suivantes :
1. **Exécution du service / Contrat :** Le stockage local de votre collection, de vos parties, de vos profils de joueurs et de vos préférences, ainsi que la création ou la mise à jour d'une sauvegarde lorsque vous activez cette option, sont nécessaires pour vous fournir les fonctionnalités demandées.
2. **Intérêt légitime :** L'affichage des informations de jeux (incluant le téléchargement direct des images), l'interrogation du catalogue Explorer, l'estimation du prix des jeux et la traduction automatisée répondent à notre intérêt légitime à vous offrir un confort de lecture et une expérience fluide, enrichie et localisée.
3. **Consentement :** L'accès aux fonctionnalités matérielles de l'appareil (photos, appareil photo, galerie) repose exclusivement sur votre consentement, donné via la demande de permission native du système lors de l'action que vous initiez.

---

## 7. Transferts hors de l'Union européenne

Selon les prestataires d'infrastructure utilisés, certaines des données de connexion techniques décrites à l'Article 5 (notamment l'adresse IP et les requêtes techniques de routage) sont traitées en dehors de l'Espace économique européen, en particulier aux États-Unis par les sociétés **Cloudflare, Inc.** et **Geekdo, LLC**.

Pour les services techniques intégrés par Dicea, ces transferts portent sur les métadonnées indispensables à l'acheminement des flux, à l'exclusion des données saisies par l'utilisateur. Ils sont encadrés par les garanties applicables, notamment les **Clauses Contractuelles Types (CCT)** adoptées par la Commission européenne ainsi que les mécanismes de conformité propres à ces prestataires.

Le service de traduction (API Gemini de Google) ne reçoit que le texte public des descriptions de jeux, par l'intermédiaire du proxy de l'éditeur : il ne reçoit ni votre adresse IP, ni aucune donnée vous concernant. Ce texte peut être traité hors de l'Espace économique européen.

Si vous choisissez un stockage cloud, le fichier complet peut être conservé ou traité hors de l'Espace économique européen selon le fournisseur, votre compte et l'emplacement sélectionné. Ces opérations relèvent des conditions et de la politique du fournisseur que vous avez choisi ; Dicea ne détermine pas la localisation de ses serveurs et ne reçoit pas le fichier.

---

## 8. Durée de conservation

* **Données locales :** Les données décrites à l'Article 3.1 restent stockées sur votre appareil tant que vous ne les supprimez pas manuellement et que l'application reste installée. Elles sont définitivement effacées lors de la désinstallation de Dicea.
* **Fichiers de sauvegarde externes :** Ils restent dans l'emplacement choisi jusqu'à ce que vous les supprimiez vous-même. Désactiver la sauvegarde automatique, réinitialiser ou désinstaller Dicea ne supprime pas ces fichiers. Leur éventuelle conservation côté cloud dépend du fournisseur sélectionné.
* **Requêtes réseau :** Les requêtes techniques adressées à BoardGameGeek, au réseau d'images, au catalogue, au comparateur de prix, au service de traduction et aux proxies intermédiaires sont éphémères et ne sont rattachées à aucun profil utilisateur. Les caches de données publiques relatives aux jeux sont temporaires.

---

## 9. Vos droits

Conformément au RGPD, vous disposez d'un droit d'accès, de rectification, d'effacement, de limitation, d'opposition et de portabilité concernant vos données.

En raison de l'architecture décentralisée ("local-first") de Dicea, **vous pouvez exercer l'immense majorité de ces droits de manière totalement autonome**, sans notre intervention :
* **Accès & Portabilité :** Vous pouvez consulter toutes vos données directement dans les écrans de l'application et les exporter au format JSON à tout moment.
* **Rectification :** Vous pouvez modifier manuellement vos jeux, vos sessions de parties, vos scores et vos profils de joueurs directement dans les réglages.
* **Effacement :** Vous pouvez supprimer un élément un par un, réinitialiser la mémoire locale de l'onglet Explorer, utiliser « Réinitialiser toute l'app » (Paramètres → Données → Suppression → Supprimer mes données), qui efface la base, l'intégralité des préférences, vos photos et les copies de sauvegarde conservées dans le stockage privé de l'application, ou désinstaller l'application pour purger les enregistrements locaux. Une sauvegarde externe doit être supprimée séparément depuis le gestionnaire de fichiers ou le fournisseur choisi.

Vous pouvez à tout moment **retirer un consentement** que vous avez précédemment accordé, par exemple en révoquant une permission dans les réglages système de votre appareil, ce qui rendra simplement les fonctionnalités associées indisponibles. Pour toute demande d'exercice de droit nécessitant une action de notre part, vous pouvez nous contacter à l'adresse **Ludiq.support@gmail.com**. Nous vous répondrons dans le délai légal d'un mois.

Vous disposez également du droit d'introduire une réclamation auprès de l'autorité de contrôle compétente. En France, il s'agit de la **CNIL** (Commission nationale de l'informatique et des libertés) via son site [www.cnil.fr](https://www.cnil.fr).

---

## 10. Sécurité

Vos données locales bénéficient des mécanismes de sécurité natifs du système d'exploitation de votre appareil, notamment le cloisonnement des applications (sandbox) et, si vous l'avez activé, le chiffrement matériel de l'appareil. Les échanges réseau intégrés à Dicea décrits à l'Article 5 utilisent des connexions chiffrées (**HTTPS**).

Le fichier JSON n'est pas chiffré séparément par Dicea : sa protection dépend de la sécurité de votre appareil, de l'emplacement choisi et, pour un stockage cloud, de votre compte chez le fournisseur. Nous vous recommandons de protéger votre téléphone et votre compte cloud par un verrouillage robuste et, lorsque cela est proposé, une authentification à deux facteurs.

---

## 11. Protection des mineurs

Dicea est une application tout public. Elle n'est pas destinée spécifiquement aux enfants et ne collectera jamais sciemment de données personnelles les concernant. Si vous estimez qu'un enfant nous a communiqué des données par e-mail, nous vous invitons à nous contacter pour que nous procédions à leur suppression.

Les noms et avatars de joueurs que vous saisissez peuvent concerner des tiers (famille, amis, y compris des enfants). Ces informations restent sur votre appareil et, uniquement si vous activez une sauvegarde externe, dans le fichier placé chez le fournisseur choisi. En les saisissant et en choisissant éventuellement de les sauvegarder, vous vous engagez à ne traiter que des informations que vous êtes légalement en droit de renseigner.

---

## 12. Modifications de la politique

La présente politique de confidentialité peut être mise à jour afin de refléter une évolution de l'application ou des réglementations applicables. Toute évolution de cette nature fera l'objet d'une révision du présent document en amont de son entrée en vigueur. En cas de modification importante, nous l'indiquerons au sein de l'application ou sur la page d'hébergement web du document. La date de dernière mise à jour figurant en tête fait foi.

---

## 13. Contact

Pour toute question relative à la présente politique ou à vos données :

* **Adresse e-mail :** Ludiq.support@gmail.com
* **Éditeur :** GODINEAU Savinien
* **URL du document :** https://dicea-app.com/privacy/
`,
            en: `
# Privacy Policy — Dicea

| Metadata | Value |
| :--- | :--- |
| **Application** | Dicea |
| **Last update** | October 27, 2026 |

---

## 1. Overview

**Dicea** is a free mobile application for board game players. It has been designed to respect the privacy of its users and operates primarily offline.

* **Local storage by default:** Your game collection, plays (photos included) and scores, player profiles (names and photos), and preferences are stored in your phone's memory. No Dicea server receives or stores this information. If you voluntarily enable automatic backups to external storage, a copy is also written to the single file you choose.
* **No account, no ads:** Using the application does not require an account creation or an email address. The app contains no advertising, no ad trackers, and does not sell any data.
* **Minimal network flows:** The information that leaves your device consists of technical requests sent to BoardGameGeek to display game details, downloading game images from BoardGameGeek's image delivery network, the BoardGameGeek IDs of games sent to a price comparison service to estimate their price, and the text of game descriptions sent to a translation service when you use the application in French. If you choose an external storage provider, the operating system also hands your backup file to that provider so it can store and, where applicable, synchronize it.

🔒 **Important nuance (Content vs Metadata):** Technical game-related requests do not include any data you entered in the application: neither your name, player profiles, nor statistics. Like any Internet connection, they nevertheless transmit technical connection data such as your **IP address**. By contrast, an external backup contains your Dicea data: it is transmitted only to the storage provider you selected, never to Dicea's publisher.

---

## 2. Data Controller

The publisher of the Dicea application is responsible for processing your data within the meaning of the General Data Protection Regulation (GDPR).

> 📋 **Publisher Information:**
> * **Publisher:** GODINEAU Savinien
> * **Status:** Individual developer
> * **Contact address:** Ludiq.support@gmail.com

For any questions regarding this policy or the management of your data, you can write to us directly at the email address provided above.

---

## 3. Data Concerned

Dicea acts as a tabletop companion. To operate, the app processes specific categories of data. They remain on your device unless you voluntarily enable a backup to an external file or use a connected feature described below.

### 3.1. Data stored locally on your device
The following data is first stored in the application's private, sandboxed storage. It is never transmitted to the publisher. If no external backup is configured, it is not handed to a third-party storage provider:
* **Your game collection:** Owned games, other games, wishlist, expansions, and favorites, as well as the purchase prices you enter and the estimated prices of your games.
* **Your plays:** Logged game sessions, dates, durations, formats, and present players, as well as the note and photo you can attach to them.
* **Your scores and statistics:** Detailed results per player, history, and graphic summaries.
* **Player profiles:** The names or pseudonyms you enter manually and the local photos or avatars you choose for your profiles.
* **Your preferences:** Interface language, display settings, filters, and Explore tab memory.

🔒 **System automatic backup disabled:** Android offers applications an automatic backup of their data to the user's cloud account. Dicea **explicitly opts out** of it: neither the database, nor your photos, nor your preferences are handed to that mechanism. Only the **direct transfer** from an old phone to a new one, performed locally by the system when you change device, remains allowed: it goes through no server.

✏️ **User control:** You retain control over this data. You can modify or delete it at any time directly in the application, or export it yourself in **JSON** format. Uninstalling erases the application's private data from the device, but does not delete files you placed in external storage.

### 3.2. Manual and automatic backups
Automatic backup is optional and must be configured by you. You may choose the application's private storage or create/attach a document in a location offered by Android's or iOS's native picker, such as Google Drive, iCloud Drive, another compatible provider, or local storage.

The **JSON** backup file contains a complete copy of the Dicea data described in Article 3.1, including exportable preferences and personal images needed for a restore. After your selection, Dicea stores a technical authorization locally, limited to that document, so it can replace the file automatically after your changes. Dicea receives neither the username, password, nor sign-in token for your cloud account, and does not browse your other files.

To withstand a temporary provider outage, Dicea also keeps a limited rotation of two copies in its private storage. If the network is unavailable, the system provider may defer remote synchronization and Dicea will try again later. The publisher receives no copy, cannot view the document, and cannot confirm when the provider has completed uploading it to its servers.

### 3.3. Data exchanged with other third-party services
Certain connected features require communication with online services. The rigorous detail of these exchanges is set out in **Article 5**.

---

## 4. Device Permissions

The application may request access to certain functions of your system. This access is systematically triggered by an explicit action on your part and remains strictly confined to its purpose.

| Permission | Usage in Dicea | Data Transmission |
| :--- | :--- | :--- |
| **Photos & Camera** | Allows you to choose an avatar for a player or for your profile, a photo for a game, an expansion or a play, and to **scan QR codes** to import a shared game. | The selected image or the scanning video feed is processed locally in the app. **No image is transmitted to a server.** |
| **Save to Gallery** | Allows you to save a shareable summary image that you generate yourself to your storage. | The image is created locally on the phone and saved only upon your express request. |
| **Document access** | Allows you to export, import, or automatically update a JSON backup through the system picker. | You choose the document yourself. Persistent access is limited to that document; the application does not browse your other files and receives no access to your cloud account. |

*You can refuse or revoke these permissions at any time in your operating system settings or with the relevant provider. The corresponding features will then simply be unavailable. Selecting a backup document does not require general permission to access all your storage.*

---

## 5. Third-Party Services and Data Recipients

The application relies on a limited number of infrastructures to function. It may also, only at your request, hand a backup to the storage provider you select in the system interface.

| Service / Provider | Transmitted Data | Purpose of flows | Provider & Policy |
| :--- | :--- | :--- | :--- |
| **BoardGameGeek (API)** | Search terms and IDs of viewed games. *(Zero user data)*. Request via Cloudflare proxy. | Retrieve technical game sheets in real-time (name, rating, description, rankings). | BoardGameGeek<br>🔗 [Privacy Policy](https://boardgamegeek.com/privacy) |
| **BGG Image Network** | Direct HTTP request to the domain \`geekdo-images.com\`. Exposes your **IP address** and viewed visuals. | Download board game covers and thumbnails directly to your screen. | Geekdo, LLC (USA)<br>*(Direct flow without going through the publisher's proxy)* |
| **Game Catalog** | Read-only requests on our board game index, built from publicly available information. *(Zero user data)*. | Power the discovery and suggestions feature within the **Explore** tab. | Operated by the publisher<br>*(Index hosted at Supabase, requests via Cloudflare)* |
| **Translation Service** | Raw text of the game description (in English), from BoardGameGeek. *(Zero user data. Flow inactive if app is in English)*. Request via Cloudflare proxy. | Automatic translation of game sheet descriptions into French, by an artificial intelligence model. | Google (Gemini API)<br>*(The service only receives requests from the publisher's proxy)*<br>🔗 [Privacy Policy](https://policies.google.com/privacy) |
| **Price Comparison** | BoardGameGeek IDs of games and expansions, and the price market (France, United Kingdom or United States, derived from the app language and the device country). *(Zero user data: no purchase price, no name)*. Request via Cloudflare proxy. | Estimate the price of your games from online shop offers and link to their price page. | Ludiprix.fr / BoardGamePrices, KP Software Consult ApS (Denmark)<br>*(The site only receives requests from the publisher's proxy)* |
| **Technical Hosting** | Standard connection metadata (IP address in particular) required for traffic routing. | Secure routing (HTTPS) of app requests and performance caching of public data. | Cloudflare Workers<br>🔗 [Privacy Policy](https://www.cloudflare.com/privacypolicy/) |
| **Selected storage provider (optional)** | Complete JSON backup file and technical metadata processed by the system or provider. | Store and potentially synchronize the backup in the location you selected. No transit through a Dicea server. | Provider selected in Android/iOS, including [Google](https://policies.google.com/privacy) or [Apple](https://www.apple.com/legal/privacy/), depending on your choice. |

Links to BoardGameGeek and to a game's price page open in your browser: browsing those sites is then governed by their own privacy policy.

### 🔒 Guarantee of no tracking
To be perfectly complete, the Dicea application does not use any audience measurement tools, any behavioral tracking tools, any third-party crash reporting tools (like Firebase Crashlytics), any services from the Google Firebase suite, and no advertising.

### 5.5. Protection provided by third parties
Technical providers integrated by Dicea are selected with appropriate data-protection safeguards in mind. The external storage provider, however, is freely selected by you in the system interface: its processing of the file depends on your relationship with it, your account configuration, and its own privacy policy. Dicea's publisher receives neither your credentials nor your backup and does not control the processing performed by that provider.

---

## 6. Legal Bases for Processing

In accordance with **Article 6 of the GDPR**, the processing implemented is based on the following legal bases:
1. **Performance of the service / Contract:** Local storage of your collection, plays, player profiles, and preferences, as well as creating or updating a backup when you enable that option, is necessary to provide the features you request.
2. **Legitimate interest:** Displaying game information (including direct download of images), querying the Explore catalog, estimating game prices, and automated translation respond to our legitimate interest in offering you reading comfort and a smooth, enriched, and localized experience.
3. **Consent:** Access to device hardware features (photos, camera, gallery) relies exclusively on your consent, given via the native system permission request during the action you initiate.

---

## 7. Transfers outside the European Union

Depending on the infrastructure providers used, some of the technical connection data described in Article 5 (notably the IP address and technical routing requests) are processed outside the European Economic Area, in particular in the United States by **Cloudflare, Inc.** and **Geekdo, LLC**.

For technical services integrated by Dicea, these transfers concern metadata required to route traffic and exclude data entered by the user. They are governed by the applicable safeguards, including the **Standard Contractual Clauses (SCCs)** adopted by the European Commission and the providers' compliance mechanisms.

The translation service (Google's Gemini API) only receives the public text of game descriptions, through the publisher's proxy: it receives neither your IP address nor any data about you. This text may be processed outside the European Economic Area.

If you select cloud storage, the complete backup file may be stored or processed outside the European Economic Area depending on the provider, your account, and the selected location. Such operations are governed by the terms and policy of the provider you selected; Dicea does not determine the location of its servers and does not receive the file.

---

## 8. Retention Period

* **Local data:** The data described in Article 3.1 remains stored on your device as long as you do not delete it manually and the app remains installed. It is permanently erased when uninstalling Dicea.
* **External backup files:** They remain in the selected location until you delete them yourself. Turning off automatic backup, resetting, or uninstalling Dicea does not delete those files. Any cloud retention depends on the selected provider.
* **Network requests:** Technical requests sent to BoardGameGeek, the image network, the catalog, the price comparison service, the translation service, and intermediate proxies are ephemeral and are not attached to any user profile. Caches of public data related to games are temporary.

---

## 9. Your Rights

In accordance with the GDPR, you have a right of access, rectification, erasure, limitation, opposition, and portability regarding your data.

Due to the decentralized ("local-first") architecture of Dicea, **you can exercise the vast majority of these rights completely autonomously**, without our intervention:
* **Access & Portability:** You can view all your data directly in the app screens and export them in JSON format at any time.
* **Rectification:** You can manually modify your games, your play sessions, your scores, and your player profiles directly in the settings.
* **Erasure:** You can delete items individually, reset the Explore tab's local memory, use “Reset the whole app” (Settings → Data → Delete → Delete my data), which erases the database, every preference, your photos and the backup copies kept in the app's private storage, or uninstall the app to purge local records. An external backup must be deleted separately through the file manager or selected provider.

You can at any time **withdraw consent** that you have previously granted, for example by revoking a permission in your device's system settings, which will simply make the associated features unavailable. For any request to exercise a right requiring action on our part, you can contact us at the address **Ludiq.support@gmail.com**. We will respond to you within the legal period of one month.

You also have the right to lodge a complaint with the competent supervisory authority. In France, this is the **CNIL** (Commission nationale de l'informatique et des libertés) via its website [www.cnil.fr](https://www.cnil.fr).

---

## 10. Security

Your local data benefits from the native security mechanisms of your device's operating system, including application sandboxing and, if enabled, hardware encryption. Network exchanges integrated into Dicea and described in Article 5 use encrypted connections (**HTTPS**).

The JSON file is not separately encrypted by Dicea: its protection depends on the security of your device, the selected location and, for cloud storage, your provider account. We recommend protecting your phone and cloud account with a strong lock and, where available, two-factor authentication.

---

## 11. Protection of Minors

Dicea is an application for all audiences. It is not specifically aimed at children and will never knowingly collect personal data concerning them. If you believe a child has communicated data to us by email, we invite you to contact us so that we can proceed with its deletion.

The player names and avatars you enter may concern third parties (family, friends, including children). This information remains on your device and, only if you enable an external backup, in the file placed with the selected provider. By entering and potentially backing up this information, you undertake to process only information that you are legally entitled to record.

---

## 12. Changes to the Policy

This privacy policy may be updated to reflect a change in the application or applicable regulations. Any evolution of this nature will be subject to a revision of this document prior to its entry into force. In the event of a significant change, we will indicate it within the application or on the document's web hosting page. The date of last update appearing at the top is authentic.

---

## 13. Contact

For any questions regarding this policy or your data:

* **Email address:** Ludiq.support@gmail.com
* **Publisher:** GODINEAU Savinien
* **Document URL:** https://dicea-app.com/privacy/
`
        };

        let currentLang = 'en';

        function renderPolicy(lang) {
            currentLang = lang;
            
            // On utilise la librairie "marked" pour transformer le markdown en HTML 
            document.getElementById('content').innerHTML = marked.parse(policies[lang]);
            
            // Mise à jour de l'interface et du bouton selon la langue
            if(lang === 'fr') {
                document.title = "Politique de Confidentialité - Dicea";
                document.getElementById('html-doc').lang = "fr";
                document.getElementById('lang-btn').innerHTML = "🇬🇧 English";
            } else {
                document.title = "Privacy Policy - Dicea";
                document.getElementById('html-doc').lang = "en";
                document.getElementById('lang-btn').innerHTML = "🇫🇷 Français";
            }
        }

        document.addEventListener("DOMContentLoaded", () => {
            // Détection automatique de la langue au premier chargement
            const userLang = navigator.language || navigator.userLanguage; 
            renderPolicy(userLang.toLowerCase().startsWith('fr') ? 'fr' : 'en');

            // Action du bouton
            document.getElementById("lang-btn").addEventListener("click", () => {
                renderPolicy(currentLang === 'en' ? 'fr' : 'en');
            });
        });
    </script>
</body>
</html>
