# Crédits photos

Les photos proviennent d'Unsplash, sauf celle de la Halle Biltoki (photo Gojo, ci-dessous) et deux photos
de Pexels (types de lieux, plus bas), et sont servies en local depuis `public/photos/`. Le site n'appelle
aucune ressource distante.

| Fichier | Auteur | Profil Unsplash | Source |
|---|---|---|---|
| `hero-salle.jpg` | Christian Agbede | https://unsplash.com/@chriscreations__ | https://images.unsplash.com/photo-1775642675553-643b1367278c |
| `match-ambiance.jpg` | Caroline Roose | https://unsplash.com/@carolineclementine | https://images.unsplash.com/photo-1663841366392-1517cc0bf9e1 |
| `quiz-musical.jpg` | Laszlo Barta | https://unsplash.com/@slie_design | https://images.unsplash.com/photo-1755428642736-951036a304ea |
| `football.jpg` | Josh Olalde | https://unsplash.com/@josholalde | https://images.unsplash.com/photo-1573159625584-56169888c23d |
| `rugby.jpg` | Max Leveridge | https://unsplash.com/@maxleveridge | https://images.unsplash.com/photo-1574618500275-a5d3458db385 |

Téléchargées le 20/09/2026 depuis les URL pointées par les maquettes
`~/Downloads/identit-web-gojo/project/Gojo Home.dc.html`.

## Photo Gojo

| Fichier | Auteur | Sujet | Source |
|---|---|---|---|
| `halle-biltoki-rueil.webp` | Gojo (photo de l'équipe) | Devant la Halle Biltoki de Rueil-Malmaison, le soir du premier match des Bleus, coup d'envoi de la Coupe du Monde (juin 2026) | `docs/retours-gabriel/2026-09-23-assistant-recette/J4-photo-halle-biltoki-rueil.png`, remise par Gabriel le 23/09/2026 |

Réencodée en WebP (qualité 82, 1086 × 1448, 222 Ko, sans métadonnées) depuis le PNG d'origine de 2,4 Mo.
Utilisée dans le cas client (§5), légendée comme telle, sans aucun nom de personne.


## Portraits des contacts du hero (`contacts/`)

Dix portraits de personnes souriantes pour la carte « Vos contacts » de la scène du hero (retour de Gabriel du 24/09/2026 : « de vraies têtes humaines dans le CRM de l'animation »). Tous sous **licence Unsplash** (usage commercial permis, attribution non obligatoire, créditée ici quand même), vérifiée photo par photo sur sa page le 24/09/2026 : aucune n'est une photo Unsplash+. Les cinq premiers ont été choisis par le cockpit (planche `docs/retours-gabriel/2026-09-24-hero-anime/K2-planche-portraits-unsplash.jpg`) ; les cinq suivants ont été ajoutés, même source, même licence, pour que les cinq contacts cochés n'aient pas les visages des cinq qu'on voit avant le défilé.

Rapatriés une fois, recadrés sur le visage par Unsplash (`?w=256&h=256&fit=crop&crop=faces&q=80`), réencodés en WebP (qualité 80, 256 × 256, 3 à 8 Ko), servis en local par `next/image`. **Les noms affichés sont inventés** et ne sont pas ceux des personnes photographiées ; le nom du fichier est celui du contact fictif.

| Fichier | Contact fictif | Auteur | Profil Unsplash | Page | Source |
|---|---|---|---|---|---|
| `contacts/camille.webp` | Camille Roux | Brooke Balentine | https://unsplash.com/@brookebalentine | https://unsplash.com/photos/xSEFkIAopxA | https://images.unsplash.com/photo-1745434159123-4908d0b9df94 |
| `contacts/yanis.webp` | Yanis Perrot | Josias Garibay | https://unsplash.com/@josiasegl | https://unsplash.com/photos/rifCUO-4X8k | https://images.unsplash.com/photo-1757744705465-ea08b0ddc38a |
| `contacts/lea.webp` | Léa Fontaine | Nolan Manning | https://unsplash.com/@nolanrmanning | https://unsplash.com/photos/Ll9YOG20UFI | https://images.unsplash.com/photo-1662850886700-4ec19bd30d11 |
| `contacts/mathis.webp` | Mathis Carré | Andrew Kayani | https://unsplash.com/@the_gallery | https://unsplash.com/photos/0YyO9TlvJKo | https://images.unsplash.com/photo-1638897212550-b0f4c5d8eb3d |
| `contacts/nadia.webp` | Nadia Lemaire | Jake Nackos | https://unsplash.com/@jakenackos | https://unsplash.com/photos/IF9TK5Uy-KI | https://images.unsplash.com/photo-1580489944761-15a19d654956 |
| `contacts/awa.webp` | Awa Diarra | Igor Rodrigues | https://unsplash.com/@igorrodrigues | https://unsplash.com/photos/6IGd3-F3Cao | https://images.unsplash.com/photo-1623717217554-72ca676de535 |
| `contacts/julien.webp` | Julien Mercier | Nathan Dumlao | https://unsplash.com/@nate_dumlao | https://unsplash.com/photos/26rK1-bH9Ls | https://images.unsplash.com/photo-1583264277168-58ceba4b84e7 |
| `contacts/clara.webp` | Clara Nguyen | Andrey K | https://unsplash.com/@anamnesis33 | https://unsplash.com/photos/_sQm2pK1_eQ | https://images.unsplash.com/photo-1672462478040-a5920e2c23d8 |
| `contacts/karim.webp` | Karim Haddad | Nicolas Horn | https://unsplash.com/@sysengineer | https://unsplash.com/photos/ARBQCe2GrjQ | https://images.unsplash.com/photo-1625241152315-4a698f74ceb7 |
| `contacts/manon.webp` | Manon Petit | Joel Naren | https://unsplash.com/@joeljnaren | https://unsplash.com/photos/wKkbyH-_40A | https://images.unsplash.com/photo-1544806722-0bf6ffad1844 |

Chaque fichier a été rapproché de sa source créditée, image contre image (réduction à 32 × 32, écart moyen de 0,3 à 0,4 sur 255 pour chacun ; relecture Némésis du 24/09, qui avait trouvé Clara et Manon croisées dans une première version de ce tableau). Empreintes SHA-256 des fichiers servis :

- `contacts/camille.webp` : `452673ff8a4772c609863a4df3e07afbaf0115a2c40ec9ea0fbe7817497d6df6`
- `contacts/yanis.webp` : `40fb25565e25b96cc1ae494bef47b9ceeff6e373f0b8d150e67b45a95bf310be`
- `contacts/lea.webp` : `cc0b934f3a57eaf7ad6ea73a941b7534aacb0222656fdab73b1016219b183414`
- `contacts/mathis.webp` : `335012025bb0bb460eff1c4adf115bb3075fd97e644a1c3510ffe092cc98b7c5`
- `contacts/nadia.webp` : `cdb1f01ca1fd8ed1d03fba17743862d8c2b8a3a223b9365e9f697711beda8e87`
- `contacts/awa.webp` : `24a913adb30f1462d656c529942b814e69ff6e302ba95ab971693ee5b80cee08`
- `contacts/julien.webp` : `c09a2ccdfe43103d2332f3712e7dc784b74323fa62ef053689fae14761af3ab2`
- `contacts/clara.webp` : `e0804e6447094bd4301f674a9de3cdc990d9372bb645c15ae4afd3146adf0b27`
- `contacts/karim.webp` : `ab21084c9e493d860290d4ffcb869e9e89a1b7329c4a0da41a3f6cf23bf0e7a3`
- `contacts/manon.webp` : `b0ccf1fd6407c9e4b3232a63a4e39467c0596c18457c3473f8023a22896ce0a0`

Les dix contacts qui ne font que passer pendant le défilé reprennent ces portraits (une femme pour un prénom de femme, un homme pour un prénom d'homme ; `src/data/hero.ts`). Les votes du jeu reprennent ces mêmes portraits depuis le 24/09 au soir (les visages dessinés ont quitté le site) : les cinq contacts que Gojo coche sont des votants.

## Les types de lieux (§8, 24/09/2026 au soir)

Trois photos de vrais lieux, le soir, habités, pour la section refaite (« Entièrement revoir ça. Utilise de vraies images ») : un pub pendant un match, une halle gourmande pleine, une place où plusieurs terrasses se répondent. Licence vérifiée sur la page de chaque photo le 24/09/2026 : **licence Unsplash** pour la première (et le lien de téléchargement public d'Unsplash la sert bien depuis `images.unsplash.com`, jamais depuis Unsplash+), **licence Pexels** pour les deux autres. Aucune image générée : trois prises de vue situées par leur auteur, et datées par leur page (prise de vue, ou à défaut publication). Aucune photo déjà présente sur la page.

Nommées d'après leur lieu. Rapatriées une fois, **recadrées** pour écarter ce qui ne devait pas se lire ou se voir (une ardoise qui affichait une marque de bière, l'enseigne d'une boutique voisine et deux voitures pour le pub ; l'enseigne d'un stand et un dôme de vidéosurveillance au premier plan pour la halle — relecture Némésis du 24/09 au soir ; le haut du ciel noir pour la place), réencodées en WebP (qualité 76 à 78), servies en local par `next/image` en chargement différé.

| Fichier | Lieu | Auteur | Profil | Page | Source | Licence |
|---|---|---|---|---|---|---|
| `lieux-bar-sofia.webp` | Un pub de Sofia (Bulgarie), un soir de match — publiée le 15/06/2019 | Yasin Alsbey | https://unsplash.com/@yasinalsbey | https://unsplash.com/photos/PE6A-Iytkks | https://images.unsplash.com/photo-1560609429-3e8703c59c67 | Unsplash |
| `lieux-halle-madrid.webp` | Une halle gourmande de Madrid (Espagne) — prise le 23/04/2026 | Zak Mogel | https://www.pexels.com/@zak-mogel-2158251013/ | https://www.pexels.com/photo/bustling-indoor-market-scene-with-shoppers-37746225/ | https://images.pexels.com/photos/37746225/pexels-photo-37746225.jpeg | Pexels |
| `lieux-place-dijon.webp` | Une place de Dijon (France), la nuit — prise le 19/09/2024 | Ad Thiry | https://www.pexels.com/@adthiry/ | https://www.pexels.com/photo/charming-night-scene-at-dijon-street-cafe-30714045/ | https://images.pexels.com/photos/30714045/pexels-photo-30714045.jpeg | Pexels |

Empreintes SHA-256 des fichiers servis :

- `lieux-bar-sofia.webp` : `878137a05da114c6301bbad0d14ac0cc09f0e347a191977032f55a140e0dca4a`
- `lieux-halle-madrid.webp` : `365942437e6fb041eed09728ffd4909539e318660ae08810167f55de7af66c1e`
- `lieux-place-dijon.webp` : `81f8f0abf865319515fcb565fd4cf0b484de97c72b951a362425b3c63375d0f0`

Elles remplacent `bars-restaurants.jpg` (Drew Beamer, un gros plan de verres qui trinquent) et `halles.jpg` (Daniel, un food court américain), retirées du dépôt avec leurs lignes de crédit : plus rien ne les servait.

## La page football — la page modèle (27/09/2026)

Neuf photos nouvelles pour la page `/football` refaite au niveau de la home (« Y a rien dedans », verdict de Gabriel du 27/09/2026 sur les pages de la veille) : un bar pendant un match pour la scène du hero, trois tribunes pour les affiches des prochains matchs, un client à son téléphone, des habitués qui trinquent, et trois grands soirs de football, dont une pelouse de nuit. Le quatrième, « La Ligue 1 », reprend le pub de Sofia de la home (`lieux-bar-sofia.webp`, crédité plus haut). **Aucune image générée** : neuf prises de vue situées et datées par leur page. Licence vérifiée sur la page de chaque photo le 27/09/2026 : **licence Unsplash** pour huit d'entre elles (aucune n'est une photo Unsplash+ : le lien de téléchargement public les sert toutes depuis `images.unsplash.com`, et refuse les photos Unsplash+), **licence Pexels** pour la neuvième. Aucune des neuf n'était déjà présente sur le site.

Rapatriées une fois, recadrées quand il le fallait pour qu'**aucun nom de club, de stade ou de sponsor ne se lise** (une enseigne murale, le nom d'un stade, des panneaux de sponsors, le nom d'un club tissé sur des écharpes, un nom de joueur sur un maillot), réencodées en WebP (qualité 78 à 80, 1 800 px de large au plus ; 2 400 pour la tribune de l'affiche à la une, que le téléphone dessine sur plus de 1 000 px), servies en local par `next/image`. Les équipes des affiches sont des **villes**, comme partout sur le site : aucune photo n'est présentée comme celle du match qu'elle illustre.

Relecture Némésis du 27/09/2026 (constat N2) : la photo de Rennes prévue pour « La Ligue 1 » laissait lire le club, le stade et des sponsors sur un écran Retina ; elle est retirée du dépôt, remplacée par le pub de Sofia. Celle de Brighton gardait un écusson et un slogan de sponsor : elle est recadrée sous les tribunes, il n'en reste que la pelouse, les joueurs et les têtes du public ; trop basse alors pour l'affiche « Marseille - Milan » (692 px de haut), elle passe aux soirées, et l'affiche prend les supporters qui filment le match.

| Fichier | Où | Ce qu'on voit | Auteur | Profil | Page | Source | Licence |
|---|---|---|---|---|---|---|---|
| `football-bar-ecran.webp` | scène du hero | Des clients de dos regardent un match sur un grand écran, dans un bar de Salvador (Brésil) — publiée le 26/09/2024 ; recadrée à droite (une enseigne murale) | Luciano Oliveira | https://unsplash.com/@lucianooliveira | https://unsplash.com/photos/86zZ7oZI1y0 | https://images.unsplash.com/photo-1727334291228-188f30b43f1f | Unsplash |
| `football-tribune-lyon.webp` | affiche « Paris - Marseille » | Des supporters de dos, du haut d'une tribune, à Lyon — publiée le 16/02/2023 (photo argentique) ; 2 400 px de large | Steven Collomb-Clerc | https://unsplash.com/@stevencclerc | https://unsplash.com/photos/URMjG3N9C6w | https://images.unsplash.com/photo-1676558571547-33a188628dd4 | Unsplash |
| `football-stade-nuit.webp` | les soirées : la Coupe d'Europe | La pelouse d'un stade la nuit sous les projecteurs, à Brighton (Royaume-Uni) — publiée le 31/01/2024 ; recadrée sous les tribunes, à gauche et à droite (le nom du stade, un écusson, des panneaux de sponsors, un drapeau de coin aux couleurs du club) | Alex Simpson | https://unsplash.com/@m_simpsan | https://unsplash.com/photos/DOicNPBVSHs | https://images.unsplash.com/photo-1706675780107-7c43cc487928 | Unsplash |
| `football-echarpes.webp` | affiche « Lille - Lens » | Une tribune en rouge, écharpes tendues — publiée le 30/12/2024 ; recadrée en haut et à droite (le nom d'un club sur les écharpes) | Ahmet Kurt | https://unsplash.com/@ahmetkurt | https://unsplash.com/photos/_SYaBhnoBPY | https://images.unsplash.com/photo-1735587804695-11f2e2615ffd | Unsplash |
| `football-client-telephone.webp` | ce que voit un client | Un homme sourit à son téléphone, attablé dans un bar, une bière à côté de lui — publiée le 26/06/2024 (autoportrait de l'auteur) | Hoite Prins | https://unsplash.com/@hoite | https://unsplash.com/photos/6t36nT0H-eY | https://images.unsplash.com/photo-1719413251389-57afd5a43a9f | Unsplash |
| `football-habitues.webp` | ce que vous gardez | Des amis trinquent, chopes levées, dans un bar — prise le 13/10/2020 | Pavel Danilyuk | https://www.pexels.com/@pavel-danilyuk/ | https://www.pexels.com/photo/a-group-of-friends-drinking-beer-5858069/ | https://images.pexels.com/photos/5858069/pexels-photo-5858069.jpeg | Pexels |
| `football-coupe-europe.webp` | affiche « Marseille - Milan » | Des supporters filment le match avec leur téléphone, à Munich — publiée le 23/12/2018 | Tobias | https://unsplash.com/@herrzett | https://unsplash.com/photos/WAmXufrAV_M | https://images.unsplash.com/photo-1545558490-d4ca82897db4 | Unsplash |
| `football-derby.webp` | les soirées : le derby | Des bras levés en tribune au moment d'une action, à Liverpool — publiée le 09/03/2024 ; recadrée en haut (des panneaux de sponsors) et en bas (un nom de joueur) | 하준 윤 (haJun Yoon) | https://unsplash.com/@offtoseetheworld | https://unsplash.com/photos/QOUxCvbuci0 | https://images.unsplash.com/photo-1709994981222-71a403966361 | Unsplash |
| `football-bleus-montpellier.webp` | les soirées : les Bleus | La place de la Comédie à Montpellier, drapeaux tricolores et fumigènes, le soir de la deuxième étoile — publiée le 16/07/2018 | Pierre Herman | https://unsplash.com/@lepipotron | https://unsplash.com/photos/Fw_2kaQZc90 | https://images.unsplash.com/photo-1531752148124-118ba196fc7b | Unsplash |

Empreintes SHA-256 des fichiers servis :

- `football-bar-ecran.webp` : `03d9ffc84681adee4365e7546ecba2400de5afb9999c6a4c12c92f18b1ef52b2`
- `football-tribune-lyon.webp` : `674d44de4601baad89f37fa8153906df96b6994accdf3dc4212624eb10283e09`
- `football-stade-nuit.webp` : `e39b387ef25cd83f48df3f307238e98de1c21e1937cd62025e98716f2ae83eef`
- `football-echarpes.webp` : `54fa3b30082a8033de5d19f9b16e6919b511b75f7731e68a6bebbc64cc57ff2c`
- `football-client-telephone.webp` : `d1bdde894006cb63d2832df068226976fb5181f53191869158beff5f33caa900`
- `football-habitues.webp` : `98db46017fc880cef19435edfdd9a208cab88fd1e578b5de87a07edfda310ecc`
- `football-coupe-europe.webp` : `7aa212cf50c5b5d66159b119f3311b4dd9b3f26296ba6b8704f0b8e62f29a676`
- `football-derby.webp` : `06a685fcc003e69d370902e3e368d306e09686fbf95b34f33f574518f491a4d8`
- `football-bleus-montpellier.webp` : `3d76f4f71db257d28f333e646de24769e59a12811134bd4849a4dca40d60db96`


## La page rugby (28/09/2026)

Six photos nouvelles pour la page `/rugby`, la sœur de la page modèle : un bar pendant un match pour la scène du hero, une touche de nuit sous l’écran de la salle, trois affiches (une mêlée, un stade, une touche devant sa tribune) et des supporters aux drapeaux tricolores pour le tournoi. **Aucune image générée.** Licence vérifiée sur la page de chaque photo le 28/09/2026 : **licence Pexels** pour quatre d’entre elles, **licence Unsplash** pour deux (aucune n’est une photo Unsplash+ : le lien de téléchargement public les sert depuis `images.unsplash.com`). Aucune des six n’était déjà présente sur le site.

Une vraie photo d’un bar **pendant un match de rugby** n’a pas été trouvée sous ces deux licences (recherches du 28/09/2026 sur Unsplash et Pexels : bars de football, salons, stades) ; la scène du hero prend donc un bar pendant un match dont on ne voit pas l’écran, sans le présenter comme un soir de rugby.

Rapatriées une fois, recadrées ou floutées là où il le fallait pour qu’**aucun nom de club, de stade, de sponsor ou de joueur ne se lise**, réencodées en WebP (qualité 78, 1 800 px de large au plus ; 2 400 pour la mêlée de l’affiche à la une), servies en local par `next/image`. Les équipes des affiches sont des **villes** ou des **nations** : aucune photo n’est présentée comme celle du match qu’elle illustre.

| Fichier | Où | Ce qu’on voit | Auteur | Profil | Page | Source | Licence |
|---|---|---|---|---|---|---|---|
| `rugby-bar-supporters.webp` | scène du hero | Deux amis lèvent leur bière devant un match, attablés dans un bar — prise le 07/02/2017 ; le sport regardé n’est pas à l’image | Pressmaster | https://www.pexels.com/@pressmaster/ | https://www.pexels.com/photo/men-celebrating-at-a-bar-3851581/ | https://images.pexels.com/photos/3851581/pexels-photo-3851581.jpeg | Pexels |
| `rugby-touche-nuit.webp` | l’écran de la salle (fond) | Un sauteur s’élève en touche vers le ballon, de nuit, sous les projecteurs, en Angleterre — prise le 04/12/2024 ; floutés : la marque d’un ballon, un logo de short et un logo de maillot | Ollie Craig | https://www.pexels.com/@olliecraig1/ | https://www.pexels.com/photo/intense-night-rugby-match-in-england-29715709/ | https://images.pexels.com/photos/29715709/pexels-photo-29715709.jpeg | Pexels |
| `rugby-melee-pluie.webp` | affiche « Toulouse - La Rochelle » | Une mêlée de nuit sous la pluie, à Manchester — prise le 31/01/2024 ; 2 400 px de large ; flouté : le sponsor d’un maillot | Ollie Craig | https://www.pexels.com/@olliecraig1/ | https://www.pexels.com/photo/rugby-players-in-scrum-formation-in-rain-20192758/ | https://images.pexels.com/photos/20192758/pexels-photo-20192758.jpeg | Pexels |
| `rugby-stade-poteaux.webp` | affiche « Bordeaux - Glasgow » | Les poteaux devant les tribunes pleines d’un grand stade, à Lyon — publiée le 22/06/2018 ; recadrée sur les poteaux, au-dessus des panneaux du bord de terrain et entre les banderoles de la compétition | Thomas Serer | https://unsplash.com/@jesusance | https://unsplash.com/photos/QUr0R1VZPNw | https://images.unsplash.com/photo-1529663297269-6d349ec39b57 | Unsplash |
| `rugby-supporters-tricolores.webp` | le tournoi | Une foule de supporters, bras et drapeaux tricolores levés dans une fumée bleue et rouge, à Strasbourg — publiée le 17/07/2018, deux jours après la finale de la Coupe du monde de **football** (une fête de football, et non de rugby : à trancher par Gabriel) | Dorian Hurst | https://unsplash.com/@dorianhurst | https://unsplash.com/photos/nrWb4BRBRLE | https://images.unsplash.com/photo-1531824488575-ad9462448062 | Unsplash |
| `rugby-tribune-touche.webp` | affiche « France - Irlande » | En touche, un sauteur s’élève devant une tribune pleine, à Montpellier — prise le 14/12/2024 ; recadrée au-dessus des panneaux publicitaires, sous lesquels se lisaient des sponsors et des noms de joueurs | Eric Saint-Martin | https://www.pexels.com/@eric-saint-martin-939233568/ | https://www.pexels.com/photo/rugby-match-crowds-cheering-in-montpellier-29836849/ | https://images.pexels.com/photos/29836849/pexels-photo-29836849.jpeg | Pexels |

Empreintes SHA-256 des fichiers servis :

- `rugby-bar-supporters.webp` : `39dba1f3d8fd4c8d5e04f5d057baa3a5ae1cbfe63eba7576d4341e8dd307adf0`
- `rugby-touche-nuit.webp` : `ce70f9141a37664e6e40b8935f7d2e4af017bdacae68ddd79da931026bcf5324`
- `rugby-melee-pluie.webp` : `990f4c1172f82072f9bb7bd7f06949fd5b3c70575d4b2965d5d13d9227226ce7`
- `rugby-stade-poteaux.webp` : `368e74dd3643a28f730239add7be1609bb9edc5ddc8dc15d17cf454c8674ba5e`
- `rugby-supporters-tricolores.webp` : `10a1ef4e55e025bdacef7ce19835bc9fe92a7784a21224ca26ff725215baf646`
- `rugby-tribune-touche.webp` : `9703b67b3495055ef05d47a42b6521d2f52bb7d0443e91b84e91fff456407567`

## La page quiz et blind tests (28/09/2026)

Deux photos nouvelles pour la page `/quiz-et-blind-tests` refaite au soin de `/football` : une table qui se tape dans la main sous l'affiche du hero, et des habitués qui trinquent sous le coupon de la section « Le coupon fait revenir ». **Aucune image générée.** Licence vérifiée sur la page de chaque photo le 28/09/2026 : **licence Pexels** pour la première, **licence Unsplash** pour la seconde (ce n'est pas une photo Unsplash+ : le lien public `images.unsplash.com` la sert). Aucune des deux n'était déjà présente sur le site. La photo `quiz-musical.jpg` de la home (plus haut) reste celle des affiches et de l'assistant IA.

Rapatriées une fois, réencodées en WebP (qualité 78, 1 800 px de large), servies en local par `next/image`. **Aucun nom de club, de marque ni de personne ne s'y lit** : la première n'en porte aucun ; la seconde est recadrée en bas (le reflet d'un texte à l'envers dans le marbre de la table). Les deux ont été choisies contre d'autres qui en portaient (une scène d'animateur de quiz pleine d'enseignes de boissons, un t-shirt de marque, des étiquettes de bouteilles lisibles derrière un comptoir).

| Fichier | Où | Ce qu'on voit | Auteur | Profil | Page | Source | Licence |
|---|---|---|---|---|---|---|---|
| `quiz-table-gagnante.webp` | affiche du hero | Deux amis se tapent dans la main autour d'une table ronde de bar, un troisième boit ; des verres de whisky, des carnets et des feuilles devant eux — prise le 04/08/2020, publiée le 21/08/2020 | Gustavo Fring | https://www.pexels.com/@gustavo-fring/ | https://www.pexels.com/photo/men-doing-high-five-while-drinking-5163378/ | https://images.pexels.com/photos/5163378/pexels-photo-5163378.jpeg | Pexels |
| `quiz-habitues.webp` | le coupon fait revenir | Des amis trinquent et rient autour d'une table, dans un bar aux murs de bois — publiée le 16/04/2023 (bibliothèque « Modern Face of Whisky » de la fondation) ; recadrée en bas (un reflet de texte dans le marbre) | Jo Hanley (OurWhisky Foundation) | https://unsplash.com/@ourwhiskyfoundation | https://unsplash.com/photos/K3AzpN5S6VU | https://images.unsplash.com/photo-1681641090195-5adb0c54eeb0 | Unsplash |

Empreintes SHA-256 des fichiers servis :

- `quiz-table-gagnante.webp` : `f29e58f32b26789c8d51b0ac916139aaf0be953a704d0f7e0df287a0d7e8f5c7`
- `quiz-habitues.webp` : `f24b79d2413ca400fce5c4b232e7ff45e902216c4a0d5643aa3d7d1470f6901e`

<!-- calendrier:debut -->
## La page calendrier (28/09/2026)

Trois photos nouvelles pour la page `/calendrier` : un comptoir vide avant l'ouverture pour l'affiche du hero, une mêlée pour la carte de rugby de l'agenda, et une table de bar un soir calme pour les soirées sans match. **Aucune image générée.** Licence vérifiée sur la page de chaque photo le 28/09/2026 : **licence Unsplash** pour les trois (aucune n'est une photo Unsplash+ : le lien public `images.unsplash.com` les sert). Rapatriées une fois, recadrées quand il le fallait pour qu'**aucune marque ne se lise**, réencodées en WebP (qualité 78), servies en local par `next/image`. La carte du quiz reprend `quiz-musical.jpg`, celle que montre la fenêtre de l'assistant IA ; la carte de football reprend `football-bar-ecran.webp` de la page modèle. `football.jpg` et `rugby.jpg`, que la fenêtre de l'assistant IA montre aussi, ne sont pas repris : on y lit l'enseigne d'une bière sur des verres, des sponsors sur des maillots et la marque d'un ballon.

| Fichier | Où | Ce qu'on voit | Auteur | Profil | Page | Source | Licence |
|---|---|---|---|---|---|---|---|
| `calendrier-bar-avant-ouverture.webp` | affiche du hero | Un comptoir de bar vide avant l'ouverture, ses tabourets et sa tireuse sous des suspensions allumées — publiée le 15/01/2026 ; recadrée à gauche et en haut (des bouteilles de sirop et de soda étiquetées), 1 560 × 2 080 | Sobolev Maksim | https://unsplash.com/@maks_sobo | https://unsplash.com/photos/rNB3YCaeO-o | https://images.unsplash.com/photo-1768464706081-9ab0997a2e90 | Unsplash |
| `calendrier-melee.webp` | carte de rugby de l'agenda | Une mêlée dans la poussière d'un terrain en herbe, à Moscou — publiée le 25/11/2016 ; recadrée à gauche (un nom imprimé au dos d'un maillot, un logo de marque sur un short), 1 070 × 1 156 | Olga Guryanova | https://unsplash.com/@designer4u | https://unsplash.com/photos/ft7vJxwl2RY | https://images.unsplash.com/photo-1480099225005-2513c8947aec | Unsplash |
| `calendrier-table-du-soir.webp` | les soirées sans match | Trois cocktails sur une table en damier, dans la lumière chaude d'un bar, des clients attablés autour — publiée le 15/07/2024 ; recadrée en paysage (la photo est en portrait), 1 800 × 1 440 | Dina Makhmutova | https://unsplash.com/@dinamakhmutova | https://unsplash.com/photos/WU1_cmBbnI8 | https://images.unsplash.com/photo-1721073954161-5aa2ca4fff0b | Unsplash |

Empreintes SHA-256 des fichiers servis :

- `calendrier-bar-avant-ouverture.webp` : `f9c2fe81802fc6370887acfb80271cee341088b17e6441c6506526d241a25da4`
- `calendrier-melee.webp` : `0dc3a11f4a81d88f4dfa81e812b8999f5b4dc88a787b33e6529cff2ed40e0415`
- `calendrier-table-du-soir.webp` : `afeb9e9039f868849d6c56c7f47fba4e1fd39a18a7c8cfdac3a0adba615395ab`
<!-- calendrier:fin -->
