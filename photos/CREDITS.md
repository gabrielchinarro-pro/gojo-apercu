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
