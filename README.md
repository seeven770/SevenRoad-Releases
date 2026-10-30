# SEVEN ROAD - Releases

## Reconnexion 0.1.75 - V563

- Serveur V563 rallume ; nouvelle connexion GameLift et session Fusion `MMORPG-Diagnostic-Dungeon-V563`.
- Petit patch depuis 0.1.74 : seul `combat-diagnostic.json` change. Executables, textures, comptes et personnages conserves.
- Pas de recompilation du jeu ; 0.1.75 est la version du contenu distribue. Deux ZIP complets et launcher 1.3.7 conserves.
- Relancer le launcher habituel et appliquer la mise a jour pour rejoindre le serveur.

## Diagnostic donjon et sprint 0.1.74 - V563

- Session `MMORPG-Diagnostic-Dungeon-V563` sur le projet Sevenroad a Francfort ; mise a jour client obligatoire via le launcher habituel.
- Reentree dans l'instance du groupe, visibilite apres le donjon, synchronisation d'inventaire et nettoyage des cases apres abandon corriges.
- Sprint Maj + Z avec endurance, jauge blanche, animation calibree et explosion de depart ; double Z conserve la course normale.
- Reglages des capes et de la potion avec la coiffe du soigneur, contours du casier, optimisations de la prison et des montures lointaines.
- Placement verrouille quand pret ; deuxieme clic pour retirer le pret. Retour a l'entree des Orcs protege a la connexion.
- Ecran de maintenance avant les menus et achats ; launcher 1.3.7 relie au statut dynamique du nouveau projet Sevenroad.
- Deux ZIP verifies, patch depuis 0.1.73 et SHA-256. Comptes, personnages et qualite des textures conserves.
- Diagnostics conserves ; tests locaux automatises, validation multijoueur encore necessaire.

## Diagnostic donjon 0.1.73 - V562

- Session `MMORPG-Diagnostic-Dungeon-V562` sur le projet Sevenroad a Francfort ; mise a jour client obligatoire dans le launcher habituel.
- Correctifs des changements de groupe et entrees tardives, de l'abandon individuel et du retour apres defaite.
- Grilles et cases de sorts isolees, marqueur de tour restaure, noms fantomes et nettoyage de sortie corriges dans les sources.
- Dialogue du chat harmonise ; marqueurs de quete au style de Fernand et masques par les murs.
- Diagnostics donjon, collisions et performances conserves. Tests locaux passes ; piliers et saccades a confirmer en multijoueur.
- Installation complete en exactement deux ZIP verifies, patch depuis v0.1.72 et launcher 1.3.6. Qualite des textures, comptes et personnages conserves.

## Diagnostic donjon 0.1.72 - V561

- Serveur temporaire `MMORPG-Diagnostic-Dungeon-V561` sur Sevenroad a Francfort ; mise a jour client obligatoire via le launcher habituel.
- Traces comparatives donjon / monde ouvert : changements de groupe, arrivees tardives, monstres, grilles, cases de sorts et marqueurs au sol.
- Horloge corrigee apres les chargements de scenes ; logos HDV et banque sur la mini-carte ; membres du groupe sur la grande carte, y compris a distance.
- Panneaux HDV et herbe autour de l'entree d'Urantia. Comptes et personnages conserves.
- Version de diagnostic : les bugs du donjon restent a reproduire puis analyser en multijoueur. Ne pas presenter ces traces comme des corrections deja validees.
- Installation complete en exactement deux ZIP verifies ; patch depuis v0.1.71 et launcher 1.3.6 conserves, sans reduction de qualite des textures.

## Carte du monde et potions 0.1.71 - V560

- Session `MMORPG-DemoSession-V560` sur le serveur Sevenroad a Francfort ; client a jour requis.
- Grande carte M fantasy validee integree au jeu : zoom, details locaux, teleporteurs, bateaux, services, filtres et noms au survol.
- Collider du rocher signale aux Golems ajuste au maillage reel, cote serveur et client.
- Quantite libre de petites potions et prix total automatique a 30 or par potion ; service d'achat publie.
- Animation de boisson avec fiole, son, decompte et message des PV reellement recuperes.
- House Shuffle : Tavern Jig ; Knee Flex : Monster defeated!.
- Launcher habituel mis a jour automatiquement vers 1.3.6 : installation complete en deux ZIP verifies, patch depuis v0.1.70 conserve, manifeste et SHA-256. Aucune reduction de qualite. Relancer le launcher s'il etait deja ouvert.
- Comptes et personnages conserves.
- Tests locaux, transactions, installation complete en deux parties et patch reel depuis v0.1.70 valides ; verification multijoueur de cette version encore necessaire.

## Mini-carte fantasy 0.1.70 - V559

- Nouveau serveur Sevenroad a Francfort ; session `MMORPG-DemoSession-V559`.
- Mini-carte sur textures fantasy validees, sans camera de rendu dediee ; position, orientation et reperes conserves.
- Reglages normaux de deplacement retablis ; essais locaux temporaires exclus.
- Configuration privee de la prison et des recompenses du donjon conservee cote serveur uniquement.
- Mise a jour via le launcher habituel ; ZIP complet, patch depuis v0.1.69, manifeste et SHA-256.
- Comptes et personnages conserves. Verification multijoueur de cette version encore necessaire.

## Diagnostic donjon et collisions 0.1.69 - V558

- Nouveau serveur de diagnostic a Francfort, accessible avec le launcher habituel.
- Session `MMORPG-Diagnostic-Dungeon-V558-20261026` ; mise a jour client obligatoire.
- Traces serveur des collisions invisibles et traces client/serveur du donjon, du retour au monde et de la visibilite des armes.
- Version de test : les bugs intermittents restent a reproduire et analyser en multijoueur.
- ZIP complet, patch depuis v0.1.68, manifeste et SHA-256 ; comptes et personnages existants conserves.

## Correctif Sunraku 0.1.68 - Serveur V557 conserve

- Animations hors combat retablies lors de l'equipement de la tenue Sunraku.
- Raccordement des meshes a l'Animator a l'equipement et au retrait, avec conservation de l'optimisation d'origine.
- Bug reproduit puis corrige avec le chargement reel du personnage, sans forcer les poses ; 12 personnages et 48 controles de pose verifies.
- Apparence, short, prix et rarete inchanges. Session `MMORPG-DemoSession-V557` a Francfort conservee, sans redemarrage du serveur.
- Mise a jour dans le launcher habituel ; patch depuis v0.1.67, ZIP complet, manifeste et SHA-256.
- Verification multijoueur du correctif publie encore necessaire.

## V557 Fusion Release 0.1.67 - Francfort

- Session `MMORPG-DemoSession-V557` en eu-central-1 ; ancienne fleet V556 supprimee.
- Tenue Sunraku epique a 1 500 Sevex dans la boutique et le casier, avec la couleur et la morphologie du personnage.
- Ajustements valides du short et bandage feminin ; reglages de drago conserves uniquement pour les tests.
- Placement de combat sur le terrain accessible, centre compris ; correctifs de collision, retour de donjon, armes, nage et camera spectateur.
- Position du personnage synchronisee entre ordinateurs et affichage du chargement des equipements.
- Mise a jour via le launcher habituel ; comptes et personnages conserves. ZIP complet, patch depuis v0.1.66, manifeste et SHA-256.
- Verification multijoueur de cette nouvelle release encore necessaire.

## V556 Fusion Release 0.1.66 - Londres

- Correctif serveur de la forte latence hors combat pendant les combats simultanes : suppression des recherches globales inutiles du joueur local sur le serveur dedie.
- Test diagnostic a trois joueurs : ping median 72 ms sans combat, 76 ms avec deux combats et 72 ms apres ; charge plus elevee et nouvelle release a verifier en multijoueur.
- Clic droit pendant la course retabli ; Roulade reste a trois cases avec Tir Lointain.
- Seul Illfang est indeplacable ; icone reduite, uniquement dans le combat local, et etat integre aux effets actifs.
- Chat General limite a 50 metres par le serveur, sans diffusion entre combats distincts. Autres canaux conserves.
- Session `MMORPG-DemoSession-V556`, serveur r5.large, 16 Gio, deux vCPU, une instance et 20 places configurees.
- Mise a jour dans le launcher habituel, comptes et personnages conserves. ZIP complet, patch depuis v0.1.65, manifeste et SHA-256.

## V555 Fusion Release 0.1.65 - Londres

- Client Windows V555 et session `MMORPG-DemoSession-V555` en eu-west-2 ; mise a jour requise, ancienne flotte V554 retiree pour liberer le quota.
- Tenue du Beater : un exemplaire garanti pour un membre du premier groupe victorieux du boss ; ensuite 0,01 % par joueur eligible et par victoire.
- Objet echangeable jusqu'a confirmation du double-clic, puis lie au compte et disponible dans le casier.
- Costume partage entre jeu, casier et inventaire ; ajustement du tissu aux morphologies feminines, tete et coiffure natives conservees.
- Controles locaux sur 12 modeles, 48 controles d'animation/attachement et tests backend recompenses, banque, HDV et abonnements reussis. Validation multijoueur et tenue en charge encore necessaires.
- Serveur r5.large, 16 Gio de RAM, 2 vCPU et 20 places configurees ; premiere victoire de production preservee par les tests.
- ZIP complet, patch depuis v0.1.64, manifeste et SHA-256.

## V554 Fusion Release 0.1.64 - Londres

- Client Windows V554 et session `MMORPG-DemoSession-V554` en eu-west-2 ; mise a jour requise pour rejoindre la nouvelle flotte.
- Ajustements des huit panoplies sur les personnages standards et variantes de boutique : capes, epaules, pantalons, mollets et bottes.
- Les 24 equipements visuels sont relies aux objets d'inventaire et a leurs icones ; restauration de l'apparence de base au retrait.
- Elf Skin : raccords du pantalon et pieds Traqueur reduits ; couches d'epaules d'origine masquees avec les capes.
- Serveur r5.large, 16 Gio de RAM, 2 vCPU et 20 places configurees ; validation multijoueur et tenue en charge encore necessaires.
- ZIP complet, patch depuis v0.1.63, manifeste et SHA-256.

## V552 Fusion Release 0.1.63 - Londres

- Client Windows V552 et session `MMORPG-DemoSession-V552` en eu-west-2 ; mise a jour requise, ancienne flotte V551 supprimee.
- Serveur r5.large, 16 Gio de RAM, 2 vCPU et 20 places configurees ; tenue en charge a verifier.
- Coiffes et capes Ours/Sanglier equipees en 3D, capes animees, retrait propre et icones assorties.
- Reglages > Jeu > Apparence : masquer le casque et la cape independamment, sans retirer les bonus.
- Reglages > Commandes : modes de deplacement et raccourcis d'interfaces personnalisables.
- Ajustements du deplacement, de la marche, du rendu d'Urantia, des maitrises en cases et des soins.
- Controles Unity automatises ; validation multijoueur en conditions reelles encore necessaire.
- ZIP complet, patch depuis v0.1.62, manifeste et SHA-256.

## V550 Fusion Release 0.1.62 - Irlande

- Client Windows V550 et session `MMORPG-DemoSession-V550` en eu-west-1 ; mise a jour requise.
- Serveur r5.large : 16 Gio de RAM et 2 vCPU, une seule instance et 20 places configurees ; tenue en charge a tester.
- Nage dans le lac superieur d'Urantia, son deversoir et le palier de la cascade ; hauteur et contour conformes aux surfaces d'eau.
- Herbe plus fournie : largeur d'origine, hauteur a 50 %, vent horizontal limite ; relief et zones peintes conserves.
- Ancienne flotte V549 de Francfort supprimee ; controles Unity automatises, validation multijoueur en conditions reelles encore necessaire.
- ZIP complet, patch depuis v0.1.61, manifeste et SHA-256.

## V549 Fusion Release 0.1.61 - Francfort

- Client Windows V549 et session `MMORPG-DemoSession-V549` ; mise a jour requise pour rejoindre la nouvelle flotte.
- Capacite configuree a 20 joueurs cote Fusion et GameLift ; une seule instance, tenue en charge a verifier.
- Duree des combats synchronisee aussi pour les joueurs qui rejoignent.
- Armes retablies apres le donjon ; nettoyage tardif de l'ancien combat protege.
- Herbe reduite en hauteur et en largeur a 30 % des dimensions d'origine ; relief et emplacements conserves, vent inchange.
- Taux des panoplies niveau 50 inchanges et identiques entre les trois panoplies.
- Anciennes flottes V547 et V548 supprimees ; controles Unity automatises, validation multijoueur en conditions reelles encore necessaire.
- ZIP complet, patch depuis v0.1.60, manifeste et SHA-256.

## V547 Fusion Release 0.1.60 - Francfort

- Client Windows V547 et session `MMORPG-DemoSession-V547` ; mise a jour requise pour rejoindre la nouvelle flotte AWS.
- Chat prive : onglets verticaux, messages cibles via `@pseudo` ou `/pseudo`, et acces depuis les menus des joueurs et amis.
- Banque sans limite de 80 emplacements ; Tout transferer corrige et filtres du sac ajoutes.
- Retour du combat du Grimoire interdit sur la plateforme.
- Equipements a 5 % de base par objet ; capture des montures a 5 % fixes.
- Herbe raccourcie et densite restauree ; terrain raccorde sous les escaliers des Shamans.
- Nage autour de l'ile corrigee ; chute dans le vide vers le teleporteur d'Urantia.
- Controles Unity automatises ; verification multijoueur en conditions reelles encore necessaire.
- ZIP complet, patch depuis v0.1.59, manifeste et SHA-256.

## V546 Fusion Release 0.1.59 - Francfort

- Client Windows V546 et session `MMORPG-DemoSession-V546` sur la nouvelle flotte AWS.
- Ancienne flotte V545 supprimee ; mise a jour du client requise pour rejoindre V546.
- Chrono de prison a gauche de la mini-carte ; decompte seulement a partir de l'arrivee en cellule, sans consommer le combat.
- Banque et HDV : retour visuel immediat, transactions en attente securisees et reconciliation serveur.
- Notification dans le chat du vendeur lors d'une vente de maison.
- Grimoire interdit : lancement des six gardiens depuis la pierre et l'epee corrige.
- Donjons : validation des mouvements et poussees ; retour de defaite directement a l'entree.
- Controles automatises reussis ; verification multijoueur en conditions reelles encore necessaire.
- ZIP complet, patch depuis v0.1.58, manifeste et SHA-256.

## V545 Fusion Release 0.1.58 - Francfort

- Nouvelle version stable ; l'ancienne release v0.1.57 et sa session V544 restent disponibles.
- Client V545 pour la nouvelle flotte AWS eu-central-1 ; session `MMORPG-DemoSession-V545`.
- Mise a jour du launcher vers V545 une fois la release publiee ; aucune interruption des sessions V544 deja ouvertes.
- Inventaire isole par personnage, y compris apres suppression et recreation dans le meme emplacement.
- Chargement des inventaires vides corrige ; deconnexion avec attente, erreur visible et nouvelle tentative.
- Hauteur de nage adaptee a la pose du personnage et synchronisee en reseau.
- Quete Grimoire interdit : activation des six gardiens et clic sur la pierre ou l'epee corriges.
- Resultats de victoire : monstres vaincus et XP conserves apres la fermeture du combat.
- ZIP complet, patch depuis v0.1.57, manifeste et SHA-256 ; installation dans un dossier distinct recommandee.

## V544 Fusion Release 0.1.57

- Client Windows V544 et serveur AWS V544 ; session `MMORPG-DemoSession-V544`.
- Collisions geantes de LostCave corrigees ; static batching desactive.
- Teleportation des Shamans securisee ; defaite hors donjon vers le teleporteur favori ou le spawn initial.
- HDV uniquement sur les PNJ designes : equipements, ou consommables et ressources.
- Vente des piles avec quantite et prix du lot ; transactions Firebase securisees.
- Falaises raccordees au terrain et collisions corrigees.
- Chemin de ville vers le pont, ancien trace efface, cascade retravaillee et animee.
- Huit anciennes parcelles non achetables et panneaux masques.
- Installation complete, patch depuis v0.1.56, manifeste et SHA-256.

## V543 Fusion Release 0.1.56

- Client Windows V543 et serveur AWS V543 ; session `MMORPG-DemoSession-V543`.
- Retour de combat : position et visibilite des participants restaurees sur tous les clients.
- Retrait du masquage de decors defectueux ; cascade animee.
- Message des anneaux retire a la connexion ; annonce Lycaon desactivee.
- Duree des boosts corrigee ; drops d'equipements a 10 % de base.
- Recompenses sur plusieurs lignes ; incarceration differee apres le combat.
- Ajout en ami au clic droit ; proprietes et affichage des points de vie corriges.
- HDV : actualisation ciblee des offres et notification des ventes dans le chat du vendeur.
- Fuite des Drago plus longue et collisions avec les arbres affinees.
- Installation complete, patch depuis v0.1.55, manifeste et SHA-256.

## V542 Fusion Release 0.1.55

- Client Windows V542 et serveur AWS V542 ; session `MMORPG-DemoSession-V542`.
- Banque partagee entre les personnages du compte, choix de quantite et transferts d'objets et d'or.
- HDV : achat confirme, vente depuis l'inventaire et transactions securisees.
- Orcs niveau 35 ; Ravageur, Traqueur et Chaman niveau 50, drops au village des chamans.
- +1 PA sur les amulettes niveau 50, +1 PM sur les bottes ; deux anneaux identiques interdits.
- Resistance investie a 1 % par point ; panoplies Ours et Sanglier reequilibrees.
- Drops d'equipements beta a 35 % de base ; Fleur Azure a 20 %, sans achat.
- Fernand BoZo, echarpe et pieces des coffres de banque corriges.
- Installation complete, patch depuis v0.1.54, manifeste et SHA-256.

## Fusion Release 0.1.54

- Client Windows V540 et serveur GameLift V540 ; session `MMORPG-DemoSession-V540`.
- Drago sauvages : locomotion, placement au sol, couleurs sobres et capture en reseau.
- Interface de capture compacte ; monture capturee retiree du monde et remplacante ailleurs dans les Montagnes perdues.
- Prison : eclairage de proximite, corrections du gardien et des interactions de cellule.
- Maisons : interieur supplementaire, escaliers reduits et raccords des portes verifies.
- Optimisations des zones, lumieres, textures et interactions, sans reduction imposee de resolution.
- Installation complete, patch depuis v0.1.53, manifeste et SHA-256.

## Fusion Release 0.1.53

- Client Windows V539 et serveur GameLift V539 ; session `MMORPG-DemoSession-V539`.
- Prison : cellules partagees, peines en temps de connexion, moderation Discord et gardien anime.
- Liberation individuelle, porte ouverte 15 secondes et appel du gardien.
- Achat, acces et revente des maisons ; amenagements et terrain ajustes.
- Montures sauvages en reseau, cascade et quetes mises a jour.
- Installation complete, patch depuis v0.1.52, manifeste et SHA-256.

## Beta 0.1.52

- Client Windows V538, serveur GameLift V538, session `MMORPG-DemoSession-V538`.
- Onze maisons amenagees, etages et escaliers adaptes, portes et balcons animes avec F.
- Passages et collisions verifies ; portes synchronisees en reseau.
- Deux montures Jurassic animees, une par etable, avec parcours limites aux enclos.
- Banque amenagee, PNJ et gardes, eclairage et decorations.
- Bannieres des zones a pied et par teleporteur.
- Noms de personnage sans espace, limites a 12 lettres ; symbole feminin corrige.
- Emplacements supplementaires a 400 Sevex avec confirmation d'achat.
- Affichage harmonise des 500 Sevex inclus dans l'abonnement annuel.
- Correctifs de retour apres combat et de connexion Fusion.

Les fichiers du jeu complet, du patch, du manifeste et leurs SHA-256 sont disponibles dans les releases.
