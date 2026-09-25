# Logos tiers — provenance et licence

Les logos de `public/logos/` sont ceux que la maquette
`~/Downloads/identit-web-gojo/project/Gojo Home.dc.html` appelle. Ils sont
**rapatriés en local** le 22/09/2026 : le site n'appelle aucune ressource
distante à l'exécution (retour R1 de Gabriel, 22/09/2026 — « où sont les
logos »).

## Simple Icons — `cdn.simpleicons.org`

Collection [Simple Icons](https://simpleicons.org/), dépôt
<https://github.com/simple-icons/simple-icons>. Les fichiers SVG sont publiés
sous **CC0 1.0 Universal** ; les marques et logos eux-mêmes restent la
propriété de leurs détenteurs respectifs et sont utilisés ici à titre
d'identification des intégrations prévues.

| Fichier | Marque | Source appelée par la maquette |
|---|---|---|
| `airtable.svg` | Airtable | `https://cdn.simpleicons.org/airtable` |
| `brevo.svg` | Brevo | `https://cdn.simpleicons.org/brevo` |
| `calendly.svg` | Calendly | `https://cdn.simpleicons.org/calendly` |
| `claude.svg` | Claude (Anthropic) | `https://cdn.simpleicons.org/claude/D97757` |
| `coda.svg` | Coda | `https://cdn.simpleicons.org/coda` |
| `gmail.svg` | Gmail | `https://cdn.simpleicons.org/gmail` |
| `googlecalendar.svg` | Google Agenda | `https://cdn.simpleicons.org/googlecalendar` |
| `googlesheets.svg` | Google Sheets | `https://cdn.simpleicons.org/googlesheets` |
| `hubspot.svg` | HubSpot | `https://cdn.simpleicons.org/hubspot` |
| `mailchimp.svg` | Mailchimp | `https://cdn.simpleicons.org/mailchimp` |
| `make.svg` | Make | `https://cdn.simpleicons.org/make` |
| `n8n.svg` | n8n | `https://cdn.simpleicons.org/n8n` |
| `notion.svg` | Notion | `https://cdn.simpleicons.org/notion` |
| `telegram.svg` | Telegram | `https://cdn.simpleicons.org/telegram` |
| `typeform.svg` | Typeform | `https://cdn.simpleicons.org/typeform` |
| `whatsapp.svg` | WhatsApp | `https://cdn.simpleicons.org/whatsapp` |
| `zapier.svg` | Zapier | `https://cdn.simpleicons.org/zapier` |
| `zoho.svg` | Zoho | `https://cdn.simpleicons.org/zoho` |

`claude.svg` est servi par la maquette avec la couleur `#D97757` explicitement
demandée dans l'URL ; le fichier local porte donc ce `fill`. Les autres portent
la couleur de marque que Simple Icons sert par défaut.

## jsDelivr — paquet `simple-icons@10.4.0`

| Fichier | Marque | Source appelée par la maquette |
|---|---|---|
| `openai.svg` | OpenAI / ChatGPT | `https://cdn.jsdelivr.net/npm/simple-icons@10.4.0/icons/openai.svg` |

Ce fichier ne porte pas d'attribut `fill` (le SVG se peint donc en noir), comme
dans la maquette.

Téléchargés le 22/09/2026 par `curl`, sans retouche.

## Sites officiels des éditeurs — logiciels de caisse (retour F1, 22/09/2026)

Trois logiciels de caisse très répandus dans les bars et restaurants en France,
ajoutés **en tête** du nuage d'intégrations à la demande de Gabriel. Ils ne
figurent ni dans la maquette ni dans Simple Icons (`lightspeed`, `zelty`,
`laddition` et `sumup` y répondent tous les quatre 404, vérifié le 22/09/2026) :
chaque fichier vient donc du **site officiel de l'éditeur**, sans retouche.

| Fichier | Marque | Source officielle | Format |
|---|---|---|---|
| `lightspeed.svg` | Lightspeed | `https://www.lightspeedhq.fr/favicon.svg` | SVG, `fill="#E81C1C"` |
| `zelty.png` | Zelty | `https://cdn.prod.website-files.com/60a36e8b1bb8de262d076ecf/62825acd4a9ac963c4861f65_ZELTY%20-%20FAV%20ICON%20256x256.png` (favicon déclaré par `www.zelty.fr`) | PNG 256 × 256 |
| `laddition.png` | L'Addition | `https://www.laddition.com/themes/custom/laddition/src/favicon/apple-touch-icon.png` | PNG 180 × 180 |

**Pourquoi deux PNG là où la consigne préfère du SVG.** Les deux éditeurs
français ne publient pas leur marque carrée en SVG : le seul SVG public de
Zelty est le **mot-symbole** « ZELTY » (`ZELTY-LOGO-01.svg`, 818 × 352), dont
le « Z » n'est pas un chemin isolable ; ceux de L'Addition sont incomplets —
`safari-pinned-tab.svg` ne porte que le carré arrondi **sans les quatre
points**, et `logo_addition_whithout_text_white.svg` ne porte que les **quatre
points blancs sans le carré**. Un PNG officiel vaut mieux qu'un SVG
reconstitué à la main. Aux tailles servies (41 px de côté au plus grand
palier), un PNG de 180 à 256 px reste net, y compris en densité double.

Ces logos sont la propriété de leurs détenteurs respectifs et sont utilisés ici
à titre d'identification des intégrations prévues, comme les dix-neuf autres.

Téléchargés le 22/09/2026 par `curl`, sans retouche.
