# Politique de confidentialité — JacArrow

**Dernière mise à jour :** 2026-08-22
**Responsable du traitement :** Morten Jacobsen, Norvège
**Contact :** galge.vender.0a@icloud.com

---

## Version courte

JacArrow stocke **toutes vos données localement sur votre appareil**. Nous n'avons aucun
serveur qui reçoit vos tirs, vos séances ou vos objectifs. Lorsque vous désinstallez
l'application, toutes les données disparaissent.

Les seuls tiers qui reçoivent des informations sont :
- **Apple** (si vous utilisez l'app sur iPhone) — gère les achats App Store
- **Google** (si vous utilisez l'app sur Android) — gère les achats Google Play
- **RevenueCat** (après votre achat Pro) — vérifie votre achat
- **Sentry** (uniquement si vous activez les rapports de plantage) — reçoit des données de plantage anonymes pour nous aider à corriger les bugs

Lequel d'Apple ou de Google est concerné dépend de la boutique depuis laquelle
vous avez téléchargé l'app. Aucun des deux n'intervient sur vos données de tir
elles-mêmes.

Vous disposez de l'intégralité des droits RGPD : accès, effacement et portabilité des données.

---

## Ce que nous stockons

### Sur votre appareil (en local, ne quitte jamais le téléphone)
- **Données de tir :** séances, manches, placements de flèches, scores, étiquettes, objectifs, arcs et jeux de flèches
- **Préférences :** langue sélectionnée, thème, main de tir, catégorie de compétition, options de notification
- **Historique de l'app :** statut des coach-marks (les astuces que vous avez vues), indicateurs de tutoriels complétés

Toutes ces données sont stockées dans une base de données SQLite et dans
AsyncStorage sur votre téléphone. Ni JacArrow, ni aucun tiers, n'a accès à ces
données. Il n'y a aucun compte utilisateur, aucun stockage dans le cloud et
aucune synchronisation entre appareils — vos données restent sur l'appareil sur
lequel vous les avez enregistrées.

### Notifications (planifiées localement sur l'appareil)
JacArrow peut vous envoyer des notifications : que vous avez établi un record
personnel, que votre période d'essai approche de sa fin, ou des rappels
concernant vos objectifs.

Toutes sont **planifiées localement sur votre appareil** et calculées à partir
de données qui ne le quittent jamais. Nous n'avons aucun serveur qui envoie des
notifications, et nous ne recevons jamais de jeton de notification, d'accusé de
réception, ni aucune information sur ce que vous avez fait d'une notification.
La livraison elle-même est assurée par le système d'exploitation de votre
téléphone (iOS ou Android), exactement comme une alarme que vous auriez réglée
vous-même.

Vous pouvez désactiver les notifications à tout moment — dans JacArrow via
**Réglages → Notifications**, et dans les réglages de votre téléphone.

---

## Tiers

### Apple App Store (sur iPhone)
Si vous avez téléchargé JacArrow depuis l'App Store, tous les achats intégrés
sont gérés par Apple. Nous ne recevons jamais d'informations bancaires,
d'adresses ou d'autres détails de paiement. La
[politique de confidentialité d'Apple](https://www.apple.com/fr/legal/privacy/) s'applique au
processus d'achat.

### Google Play (sur Android)
Si vous avez téléchargé JacArrow depuis Google Play, tous les achats intégrés
sont gérés par Google via Google Play Billing. Nous ne recevons jamais
d'informations bancaires, d'adresses ou d'autres détails de paiement — on nous
indique seulement qu'un achat est effectué et valide. La
[politique de confidentialité de Google](https://policies.google.com/privacy?hl=fr)
s'applique au processus d'achat.

Notez que Google Play, contrairement à l'App Store, ne partage **pas** un achat
intégré avec un groupe familial. C'est une différence entre les boutiques, et
non quelque chose que nous contrôlons.

### RevenueCat (uniquement après achat Pro)
Lorsque vous achetez JacArrow Pro, RevenueCat enregistre votre reçu et un
`appUserId` anonyme (UUID généré sur votre appareil). Cela est nécessaire
pour que l'app puisse vérifier votre achat lors d'utilisations ultérieures et lors de la
« restauration des achats ». Le reçu provient de l'App Store ou de Google Play,
selon l'endroit où vous avez acheté. La
[politique de confidentialité de RevenueCat](https://www.revenuecat.com/privacy) s'applique. Nous n'envoyons jamais
votre nom, votre e-mail ou d'autres données personnelles.

### Analyses et données de plantage du système d'exploitation
Apple et Google peuvent tous deux envoyer aux développeurs des chiffres
anonymes et agrégés sur l'utilisation et les plantages — mais uniquement si
**vous** l'avez activé dans les réglages de votre téléphone. C'est une
fonctionnalité de la boutique, pas la nôtre : nous ne voyons que des totaux,
jamais quoi que ce soit qui puisse remonter jusqu'à vous. Nous l'utilisons pour
la correction de bugs et l'optimisation des performances.

- **iPhone :** contrôlé par « Partager l'analyse de l'app ». Désactivez via
  **Réglages → Confidentialité et sécurité → Analyse et améliorations**.
- **Android :** contrôlé par « Utilisation et diagnostics ». Désactivez via
  **Paramètres → Google → Utilisation et diagnostics** (le nom exact varie
  légèrement selon les fabricants).

### Sentry (uniquement si vous avez activé les rapports de plantage)
Sentry est un service de surveillance d'erreurs qui nous aide à identifier et corriger
les bugs dans JacArrow. Sentry ne reçoit des données que si vous y avez
**explicitement consenti** via **Réglages → Confidentialité → Rapports de plantage**
(l'interrupteur est désactivé par défaut).

Une fois activé, les éléments suivants sont envoyés aux serveurs européens de Sentry (Allemagne) :
- Traces de pile de plantage (noms de fichiers, numéros de ligne, types d'exception)
- Modèle d'appareil et version du système d'exploitation (iOS ou Android)
- Version de l'app et numéro de build

Nous n'envoyons **pas** :
- Informations personnelles (pas de nom, pas d'e-mail, pas d'identifiant utilisateur lié à l'identité)
- Traces de performance ou transactions (`tracesSampleRate: 0`)
- Adresses IP (`sendDefaultPii: false`)

Vous pouvez désactiver les rapports de plantage à tout moment via le même interrupteur. Une fois
désactivé, Sentry n'est **pas initialisé** et aucune requête réseau n'est effectuée.
La [politique de confidentialité de Sentry](https://sentry.io/privacy/) s'applique aux données reçues.

---

## Ce que nous NE collectons PAS

- Aucun compte utilisateur, adresse e-mail ou mot de passe
- Aucun stockage dans le cloud, aucune sauvegarde sur nos serveurs, aucune synchronisation entre appareils
- Aucune donnée GPS ou de localisation
- Aucun accès aux contacts, au calendrier, à l'appareil photo ou au microphone
- Aucun traqueur tiers (Firebase Analytics, Google Analytics, Facebook Pixel, etc.)
- Aucun identifiant publicitaire (IDFA sur iOS, identifiant publicitaire sur Android)
- Aucun suivi vidéo ni empreinte d'appareil

---

## Vos droits (RGPD)

Vous disposez des droits suivants au titre du Règlement général sur la protection des données :

**Droit d'accès (Art. 15) :** Toutes vos données sont stockées localement sur votre appareil.
Vous avez une visibilité totale via :
- Réglages → Mes séances (toutes les manches historiques)
- Réglages → Mes objectifs (tous les objectifs actifs et archivés)
- Réglages → Arcs / Jeux de flèches / Terrains (gestion du matériel)

**Droit à la portabilité des données (Art. 20) :** Utilisez
**Réglages → Exporter mes données** pour télécharger toutes vos données sous forme de fichier
JSON. Le fichier peut être partagé via le menu de partage de votre téléphone vers
e-mail, AirDrop, Fichiers, Google Drive, etc. C'est l'intégralité de votre
historique de tir dans un format standard.

**Droit à l'effacement (Art. 17) :**
- *Supprimer une séance individuelle :* balayez la séance sur l'écran d'accueil → Supprimer
- *Supprimer toutes les données :* désinstallez JacArrow — iOS comme Android
  suppriment automatiquement toute la base de données SQLite et AsyncStorage. Le
  reçu d'un achat Pro est conservé par la boutique où vous avez acheté (Apple ou
  Google) et par RevenueCat pour les besoins de remboursement et de support.

**Droit à la limitation et d'opposition (Art. 18–21) :** JacArrow ne prend
aucune décision automatisée à votre sujet. Le moteur Smart Insights analyse uniquement
vos propres données d'entraînement localement sur votre appareil et présente
des observations — il ne prend aucune décision en votre nom.

**Droit de retirer son consentement (Art. 7) :** Le consentement aux analyses
d'Apple et de Google se contrôle dans les réglages de votre téléphone (voir
« Analyses et données de plantage du système d'exploitation » ci-dessus). Les
rapports de plantage vers Sentry se désactivent dans JacArrow via
**Réglages → Confidentialité**. Les données RevenueCat sont supprimées lorsque
vous supprimez l'identifiant Apple ou le compte Google utilisé pour l'achat.

---

## Modifications

Nous mettrons à jour cette politique lorsque des changements significatifs surviendront dans la manière dont nous
traitons les données. Les modifications sont communiquées via :
1. La date « Dernière mise à jour » en haut de cette page
2. Une bannière in-app au premier lancement suivant la mise à jour si le changement est substantiel
   (ex. nouveaux tiers, nouvelle collecte de données)

---

## Réclamations

Si vous estimez que nous traitons vos données personnelles en violation du RGPD,
vous avez le droit de déposer une réclamation auprès de votre autorité nationale de protection des données :

- **France :** [Commission nationale de l'informatique et des libertés (CNIL)](https://www.cnil.fr/)
- **UE/EEE :** trouvez votre autorité sur
  [edpb.europa.eu](https://www.edpb.europa.eu/about-edpb/about-edpb/members_en)

Nous vous encourageons à nous contacter en premier à galge.vender.0a@icloud.com — nous prenons
toutes les demandes de confidentialité au sérieux.
