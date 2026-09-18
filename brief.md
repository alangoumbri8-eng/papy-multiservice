# Brief — Papy Multi Service

## Activité
Boutique de retrait / dépôt pour plateformes de paris sportifs (1xBet, et autres types Winamax/consorts).
Point de service physique tenu par "Papy" (oncle du client).

## Services
Activité unique et précise : dépôts et retraits pour plateformes de paris sportifs.
- Plateformes prises en charge : 1xBet, Winner Bet, Melbet
- 100% gratuit / sans frais pour le client

## Logo (reçu et confirmé)
- Sigle **"PMS"** en grosses lettres : P rouge, M bleu (dégradé), S rouge
- Trait/flèche courbée bleue soulignant le sigle
- Texte du dessous : **"PAPI MULTI SERVICE"** (orthographe réelle sur le logo = PAPI, pas PAPY)
- Fond blanc/crème, texte du bas en bleu marine encadré de tirets
- Fichier image original à récupérer physiquement (photo prise sur une enseigne/vitrine) — à déposer dans `design/assets/` dès que possible (le collage direct dans le chat n'est pas récupérable en fichier ici ; renvoyer par un canal qui écrit sur le disque, ex. WhatsApp Desktop, transfert Bluetooth vers le PC, ou clé USB)

## Nom officiel retenu pour le projet
**Papi Multi Service** (PMS) — à utiliser avec cette orthographe sur le site, conforme à l'enseigne réelle.

## Ambiance / Style recherché
- Festive, joviale
- Univers foot / basket / paris sportifs
- Visuels éclatants, excitants, dynamiques

## Couleurs
- Bleu dominant
- Tons festifs / jovials en complément

## Visuels
- Logo : à venir (photo à envoyer par le client)
- Photos de la boutique : à venir

## Contenu confirmé via flyer réel

### Accroches / slogans
- "Dépôt Retrait" (titre principal)
- "100% GRATUIT" (bandeau rouge)
- "RAPIDE, FIABLE" (bandeau rouge)

### Plateformes prises en charge
- 1XBET
- BETWINNER
- MELBET

### Identifiant agent
- **PAPINO44** — pseudo/code agent affiché en jaune doré sur le flyer, probablement l'identifiant que les clients utilisent pour être rattachés à Papy sur les plateformes. À CONFIRMER son usage exact avec le client, mais à afficher clairement sur le site (élément de confiance/identification).

### Contacts réels
- WhatsApp : +226 77 34 43 42
- Téléphone : +226 51 65 29 90
- Pays : Burkina Faso (indicatif +226)

### Palette couleurs réelle (à respecter, extraite du flyer)
- Fond bleu marine/nuit (dominante)
- Bandeaux rouge vif (accroches fortes)
- Jaune doré (pseudo PAPINO44, effet premium)
- Blanc (titres)
- Logo PMS : P rouge, M bleu (dégradé), S rouge, flèche bleue

### Univers visuel
- Photos de footballeurs stars en arrière-plan (Messi/Barça maillot bleu-grenat, Ronaldo maillot jaune) — ambiance foot/paris sportifs assumée
- Le client (Papy) a aussi envoyé une photo de lui-même (t-shirt noir, bijoux dorés, style décontracté) — utilisable pour une touche humaine/de confiance si besoin (section "à propos" ou contact), à confirmer avec lui.

## Confirmé par le client (réponses)
- **Quartier** : Belle Ville
- **PAPINO44** : à afficher comme identifiant à donner aux clients
- **Horaires** : 24h/24
- **Logo** : garder un esprit similaire au flyer (PMS, mêmes couleurs) mais retravaillé de façon plus soignée, avec de belles typographies, un rendu impactant/spectaculaire ("qui tape à l'œil")
- Photos de joueurs (Messi/Ronaldo) : à remplacer par des visuels génériques foot/stade/ballon (pas de droits d'image) — décision proposée, pas encore explicitement validée mais aucune objection soulevée

## Fichiers image
Photos reçues par Bluetooth et récupérées avec succès dans `design/assets/` :
- `logo-original.jpg` — photo source du logo PMS (enseigne)
- `logo-pms-transparent-opt.png` — logo extrait, fond transparent, intégré dans le site (nav + footer, sur plaque claire pour rester lisible)
- `flyer-full.jpg` — flyer complet de la boutique
- `papy-photo.jpg` — photo du client (non utilisée sur le site pour l'instant)

## Site — état d'avancement (design/template.html)
Version de travail avancée, plusieurs allers-retours de feedback déjà intégrés :
- Logo réel intégré (nav + footer) sur plaque claire pour lisibilité
- Section Hero : scène de but animée en SVG (cage, filet, tir, impact, "BUUUT !") intégrée au Hero (remplace une première version en fond fixe qui ne convenait pas — figée au scroll, effet de grille bleue)
- Fond général du site assaini (grille et bleu dominant très atténués)
- Cartes Dépôt/Retrait/100% Gratuit : bordure animée, tilt 3D au survol, pièces qui tombent, billets qui montent, étincelles
- Cartes Rapide/Fiable/24h/Sans frais : verre transparent (glassmorphism), tilt 3D, icônes flottantes
- Bloc PAPINO44 : reflet holographique, badge flottant, bordure animée, bouton copier le code
- Localisation/horaires : ping radar sur le pin, aiguille d'horloge animée
- Boutons de contact (WhatsApp/Appel) : effet d'ondes façon appel entrant
- Bouton WhatsApp flottant permanent

### Retour du client en attente
Dernier retour envoyé par Claude après la refonte de la scène de but (SVG dans le Hero + fond assaini + nouvelles animations sur agent/localisation/contact) — **pas encore vu/validé par le client**. À rouvrir et valider en priorité à la reprise.

### Point ouvert
Claude a signalé une limite honnête : en CSS/HTML pur, la scène de but reste "stylisée/graphique pro", pas un rendu vidéo réaliste. Si le client veut un rendu type vidéo réelle, il faudra soit fournir une vraie séquence vidéo courte en boucle, soit des images réelles de ballon/cage — décision à prendre avec lui.

## Statut
**En stand-by, à reprendre demain matin en PRIORITÉ avant Stora Photographie** (demande explicite du client : "nous allons le commencer avant le projet Stora"). Premier point à traiter à la reprise : montrer le rendu actuel du Hero (scène de but SVG) et récolter le feedback.
