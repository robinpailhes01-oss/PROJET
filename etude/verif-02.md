# Vérification indépendante de « 02 — Benchmark concurrentiel »

*Date : 19 novembre 2026. Document vérifié : `etude/02-benchmark-concurrence.md` (non modifié).*

## 0. Méthode et limites (à lire avant tout)

- **Environ 95 recherches web indépendantes**, dont une vingtaine restreintes à un domaine précis (site officiel, TripAdvisor, Staycation, office de tourisme) pour faire remonter le contenu de la source primaire.
- **La lecture directe des pages est restée impossible**, comme pour l'auteur : `villaoccitana.com`, `staycation.co`, `bodacc.fr`, `lekrew.fr` sont refusés par le réseau de la session (WebFetch et curl). `midilibre.fr` refuse le moteur. **BODACC et Pappers n'ont donc pas été consultés directement** ; les procédures collectives sont recoupées via societe.com, annuaire-entreprises.data.gouv.fr, Doctrine et la presse, tels que restitués par le moteur.
- Conséquence : un « CONFIRMÉ » signifie « deux sources concordantes, ou contenu d'une source primaire restitué par le moteur ». Ce n'est pas une lecture de la page. Les prix et notes bougent ; ils sont datés de novembre 2026.
- Google Maps et Instagram ne sont pas accessibles. Or c'est là que vivent les petits acteurs (saunas mobiles, événements éphémères). **L'absence de concurrent ne peut pas être prouvée depuis cette session.**
- Verdicts : **CONFIRMÉ**, **PARTIEL** (valeur correcte donnée), **NON VÉRIFIABLE** (non retrouvé ou non recoupé), **FAUX** (bonne valeur donnée).

## 1. Synthèse

| Verdict | Nombre |
|---|---|
| CONFIRMÉ | 57 |
| PARTIEL | 31 |
| NON VÉRIFIABLE | 29 |
| FAUX | 9 |
| **Total d'affirmations classées** | **126** |

**Conclusion principale.** Le rapport est globalement honnête sur les établissements (31 sur 32 existent) et sur les chiffres sectoriels. **Sa conclusion commerciale est en revanche trop forte.** L'affirmation « l'hybride sport + sauna/bain froid n'existe pas à Montpellier » est fausse (Le KREW, Dopa House), et « les saunas sociaux n'existent en France qu'à Paris » est fausse aussi. Seul le format précis « sauna social collectif en extérieur, pass journée, avec bar » n'a pas été trouvé dans l'Hérault ni le Gard, sans que cela puisse être prouvé d'ici.

---

## 2. Existence des établissements cités

| # | Établissement (rapport) | Verdict | Nom exact, commune, statut 2026, correction | Sources |
|---|---|---|---|---|
| 1 | Villa Occitana, Calvisson | **CONFIRMÉ** | « Villa Occitana – Eco-resort », 108 route d'Aigues-Vives, 30420 Calvisson. Classé « village de vacances 5* » (pas hôtel 5*). Actif en 2026 (fiche TripAdvisor « Updated 2026 », offres Staycation en ligne). Aucun signe de procédure collective trouvé, BODACC non consulté. Aucun « Villa Occitania » trouvé | [Tourisme Occitanie](https://www.tourisme-occitanie.com/fr/fiche/hebergement-collectif/villa-occitana-eco-resort-calvisson_TFOSITRA2_HCO_6199612/), [TripAdvisor](https://www.tripadvisor.com/Hotel_Review-g1080041-d23958421-Reviews-Villa_Occitana-Calvisson_Gard_Occitanie.html), [Staycation](https://www.staycation.co/fr/hotels/villa-occitana-1798) |
| 2 | Domaine de Verchant, Castelnau-le-Lez | **CONFIRMÉ** | Relais & Châteaux 5*, spa de 2 000 m² dans 17 ha de vignes | [Hérault Tourisme](https://www.herault-tourisme.com/fr/fiche/equipements-de-loisirs/le-spa-verchant-castelnau-le-lez_TFOLOILAR034V51SJGK), [TripAdvisor](https://www.tripadvisor.com/Hotel_Review-g641864-d785910-Reviews-Domaine_De_Verchant-Castelnau_le_Lez_Montpellier_Herault_Occitanie.html) |
| 3 | Plage Palace, Palavas-les-Flots | **CONFIRMÉ** | « Hôtel Plage Palace & Spa », 5*, 72 chambres, entre Palavas et Carnon | [Hérault Tourisme](https://www.herault-tourisme.com/fr/fiche/hotellerie/hotel-plage-palace--spa-palavas-les-flots_TFOHOTLAR034V52T567/), [Michelin](https://guide.michelin.com/fr/fr/hotels-stays/palavas-les-flots/hotel-plage-palace-spa-10557) |
| 4 | Domaine Finca Lessya, Mauguio | **CONFIRMÉ** | « Domaine Finca Lessya – Lodge insolite & Spa », ouvert du 1er janvier au 31 décembre 2026 | [Tourisme Occitanie](https://www.tourisme-occitanie.com/fr/fiche/hebergement-locatif/domaine-finca-lessya-lodge-insolite--spa-lodge-prestige-de-l-oliveraie-mauguio_TFOHLOLAR034V52RNCH/) |
| 5 | Souleyourt, Cazilhac | **CONFIRMÉ** | Orthographe « Soulëyourt », 998 chemin d'Agonès, 34190 Cazilhac. Aussi référencé comme « centre de bien-être et ressourcement » | [Tourisme Occitanie](https://www.tourisme-occitanie.com/fr/fiche/hebergement-locatif/souleyourt-l-envol-du-phenix-cazilhac_TFOSITRA2_HLO_7678648/), [souleyourt.com](https://souleyourt.com/sauna-et-spa/) |
| 6 | Spa Le Nid'O (Club 7), Montpellier | **CONFIRMÉ** | 448 rue de la Roqueturière, 34090 Montpellier | [Hérault Tourisme](https://www.herault-tourisme.com/fr/fiche/equipements-de-loisirs/spa-le-nid-o-montpellier_TFOLOILAR034V51SK8K) |
| 7 | Le Spa de Fabrègues | **CONFIRMÉ** | 1 chemin de l'Aire, 34690 Fabrègues, au Domaine du Golf (aussi appelé Zenaia Spa) | [Planity](https://www.planity.com/le-spa-de-fabregues-34690-04g), [Guide-piscine](https://www.guide-piscine.fr/thermes-de-france/herault/le-zenaia-spa-a-fabregues-1512_T) |
| 8 | « Spa Lenido », Lattes Port Ariane | **FAUX** | Aucun établissement de ce nom. C'est très probablement un doublon du Nid'O (ligne 6). La description citée (bain à remous sous ciel étoilé, sauna, hammam, piscine extérieure) correspond à l'annonce Funbooker du spa du golf de Fabrègues (ligne 7). Le spa réel de Port Ariane s'appelle Easy Spa Concept (ex-Le Louxor) | [Guide-piscine Easy Spa](https://www.guide-piscine.fr/thermes-de-france/herault/easy-spa-concept-a-lattes-1917_T), [Funbooker](https://www.funbooker.com/fr/category/spa/montpellier) |
| 9 | Zéphyr Spa, Baillargues | **PARTIEL** | Existe, mais c'est le spa de 700 m² de l'hôtel Horizon Resort Massane (hammam, sauna, bassin sensoriel à jets, 4 cabines), ouvert 10 h-20 h. Vendu en journée sur Staycation (« spa 2 h et déjeuner »). Le rapport le décrit trop sommairement et ne voit pas l'offre journée | [Montpellier Tourisme](https://www.montpellier-france.com/stay/leisure-and-activities/all-leisure-and-activities/spa-zephyr-baillargues-en-5224317/), [Staycation](https://www.staycation.co/fr/hotels/spa-2h-et-dejeuner-horizon-resort-massane-5710) |
| 10 | Domaine Sainte-Cécile du Parc, Pézenas | **CONFIRMÉ** | Formule du mercredi : hatha yoga, balade, pique-nique, bain sonore, 18 €/pers. | [Visit Occitanie](https://visit-occitanie.com/en/fiche/activite/domaine-sainte-cecile-du-parc-pezenas_TFOASCLAR034V525RKG), [brochure](https://www.capdagde.com/app/uploads/wwp-sit/medias/ASCLAR034V525RKG/ASCLAR034V525RKG-saint-cecile-du-parc-NOS-ACTIVITES-2024-corrige--1-.pdf) |
| 11 | Château Sainte-Colombe, St-Geniès-des-Mourgues | **NON VÉRIFIABLE** | Non recoupé dans cette session | — |
| 12 | Club Pilates Montpellier Lattes | **CONFIRMÉ** | 130 avenue de Montpellier, Lattes. Ouverture officielle le 21 septembre 2026, 200 m², -20 % les 3 premiers mois | [Le Bonbon](https://lebonbon.fr/montpellier/good-news/nouveau-studio-pilates-reformer-lattes-montpellier/), [AC Franchise](https://ac-franchise.com/article/club-pilates-simplante-a-montpellier-lattes-le-21-septembre-2026) |
| 13 | Les Cabanes dans les Bois, Villalier | **CONFIRMÉ** | Logis Hôtel 3*, Domaine de Fourtou, 11600 Villalier, à 8 km de Carcassonne | [Tourisme Occitanie](https://www.tourisme-occitanie.com/fr/fiche/hotellerie/logis-hotel-les-cabanes-dans-les-bois-villalier_TFOHOTLAR011V506S1I/), [Logis](https://www.logishotels.com/en/hotel/logis-hotel-les-cabanes-dans-les-bois-203823) |
| 14 | Cabanes Trésors de campagne, Villarzel-du-Razès | **CONFIRMÉ** | 6 hébergements (2 chalets, 1 écolodge, 1 gîte, 2 cabanes sur pilotis) | [GreenGo](https://www.greengo.voyage/hote/cabanes-tresors-de-campagne-spa-privatif-piscine-restaurant-ferme-equestre-jardin-permaculture) |
| 15 | Les Cabanes d'Hestia, La Salvetat-sur-Agout | **NON VÉRIFIABLE** | Aucun résultat indépendant obtenu | — |
| 16 | Bulles avec spa (Tarn, Lot, Aude) | **NON VÉRIFIABLE** | Catégorie générique, pas un établissement ; non recoupée | — |
| 17 | Coucoo – Cabanes des Grands Cépages, Sorgues | **CONFIRMÉ** | Existe, saison du 6 mars au 22 novembre 2026 | [OT Provence-Alpes-Côte d'Azur](https://provence-alpes-cotedazur.com/sejourner/hebergements/tous-les-hebergements/hotels/cabanes-des-grands-cepages-sorgues-fr-2861664/), [TripAdvisor](https://www.tripadvisor.com/Hotel_Review-g1143392-d12495442-Reviews-Cabanes_Des_Grands_Cepages-Sorgues_Vaucluse_Provence_Alpes_Cote_d_Azur.html) |
| 18 | Domaine de Fontenille, Lauris | **CONFIRMÉ** | 25 chambres et suites (Michelin, Relais & Châteaux) | [Michelin](https://guide.michelin.com/ch/fr/hotels-stays/lauris/domaine-de-fontenille-8025), [Relais & Châteaux](https://www.relaischateaux.com/fr/france/domaine-de-fontenille-lauris) |
| 19 | Les Bains des Bois, Montclar | **CONFIRMÉ** | Station de Montclar (04) | [OT PACA](https://provence-alpes-cotedazur.com/que-faire/detente-et-loisirs/toutes-les-activites-detente-et-loisirs/les-bains-des-bois-montclar-fr-3225090/) |
| 20 | Domaine Cabanes & Spa Ardèche | **CONFIRMÉ** | Commune : Les Salelles (07) | [GreenGo](https://www.greengo.voyage/hote/domaine-cabanes-spa-ardeche) |
| 21 | Balnéa, Loudenvielle | **CONFIRMÉ** | Ouvert, mais **incendie de l'espace japonais le 1er juillet 2026** (15 % des plans d'eau), réouverture partielle le 3 juillet. Non mentionné dans le rapport | [Communiqué Balnéa](https://www.balnea.fr/wp-content/uploads/2026/07/communique-de-presse-Japonais-20260602.pdf), [info.fr](https://info.fr/hautes-pyrenees-apres-incendie-espace-japonais-centre-balnea-rouvre-tarifs-reduits/) |
| 22 | Bains de Saint-Thomas, Fontpédrouse | **CONFIRMÉ** | Ouvert en 2026 | [Tourisme Occitanie](https://www.tourisme-occitanie.com/bains-de-saint-thomas/fontpedrouse) |
| 23 | Les Sources de Caudalie, Martillac | **CONFIRMÉ** | — | [Brochure spa](https://www.sources-hotels.com/wp-content/uploads/2025/06/Brochure-Spa-Les-Sources-de-Caudalie.pdf) |
| 24 | Sauna et Bains Collectifs – Ground Control, Paris 12e | **CONFIRMÉ** | 87 rue du Charolais, 75012. Ouvert le 28 janvier 2026 | [Site officiel](https://saunas-collectifs.fr/saunagroundcontrol), [Le Bonbon](https://www.lebonbon.fr/paris/news/premiers-saunas-bains-collectifs-debarquent-paris/) |
| 25 | Dropp Social Sauna, Paris 12e | **CONFIRMÉ** | 7 boulevard Poniatowski, 75012 | [Le Bonbon](https://www.lebonbon.fr/paris/loisirs/plus-grand-sauna-plein-air-france-paris/), [ClassPass](https://classpass.com/studios/dropp-sauna-paris) |
| 26 | Sant Roch, Paris 1er | **CONFIRMÉ** | Rue Saint-Roch (n° 8 selon la plupart des sources, n° 4 selon une) | [Paris je t'aime](https://parisjetaime.com/culture/sauna-sant-roch-paris-p4812), [Time Out](https://www.timeout.fr/paris/actualites/le-plus-grand-spa-de-france-ouvre-a-paris-face-aux-tuileries-avec-une-nouvelle-vision-du-bien-etre-030526) |
| 27 | QC Terme Chamonix | **CONFIRMÉ** | Ouvert toute l'année 2026, sur réservation | [Chamonix.com](https://en.chamonix.com/activities/indoors/spa-wellness-and-fitness/qc-terme-spas-and-resorts) |
| 28 | EPISOD – retraite sportive, Sologne | **CONFIRMÉ** | 15-17 mai 2026, Domaine Momoamo. Événement ponctuel, déjà passé | [Time Out](https://www.timeout.fr/paris/actualites/episod-organise-sa-premiere-retraite-sportive-en-sologne-050526) |
| 29 | Löyly, Helsinki | **CONFIRMÉ** | Ouvert en 2016 | [Site officiel](https://www.loylyhelsinki.fi/en/public-sauna) |
| 30 | Strøm spa nordique, Québec | **CONFIRMÉ** | 5 sites (Saint-Sauveur, Île-des-Sœurs, Mont-Saint-Hilaire, Vieux-Québec, Sherbrooke) | [Narcity](https://www.narcity.com/tag/strom-spa-nordique) |
| 31 | Bathhouse (New York) / Othership (Toronto) | **CONFIRMÉ** | — | [Athletech](https://athletechnews.com/bathhouse-raises-35-million-plots-expansion-as-social-sauna-boom-scales/) |
| 32 | Soho Farmhouse – Lazy Lake, Oxfordshire | **CONFIRMÉ** | — | [Soho House](https://www.sohohouse.com/house-notes/issue-006/soho-health-club/soho-farmhouse-lazy-lake) |
| A4 | Lodge Saint-Gilles 290 €, bulle Nîmes 260 €, cabane « près de Montpellier » 185 €, Les Méditerranées | **NON VÉRIFIABLE** | Offres anonymes d'agrégateur, non identifiables. À retirer ou à nommer | — |

---

## 3. Prix, notes et chiffres des établissements principaux

### 3.1 Villa Occitana (Calvisson)

| Affirmation du rapport | Verdict | Valeur corrigée | Sources |
|---|---|---|---|
| Éco-resort d'inspiration balinaise, lodges, cabanes et villas, pinède de 2 ha, spa « Infinity », restaurants | **CONFIRMÉ** | — | [Tourisme Occitanie](https://www.tourisme-occitanie.com/fr/fiche/hebergement-collectif/villa-occitana-eco-resort-calvisson_TFOSITRA2_HCO_6199612/), [Expedia](https://www.expedia.com/Calvisson-Hotels-Villa-Occitana.h76556224.Hotel-Information) |
| Ouverture à l'été 2022 | **CONFIRMÉ** | Article Objectif Gard daté du 25 juin 2022 | [Objectif Gard](https://www.objectifgard.com/a-la-une/fait-du-jour-a-calvisson-la-villa-occitana-le-bali-de-la-vaunage-1398.php) |
| 46 hébergements dans 20 bâtiments | **PARTIEL** | 46 était le projet de 2022. Aujourd'hui : 17 chambres et 8 appartements (Tourisme Gard), 22 unités (Expedia). Retenir 22 à 25 unités | [Tourisme Gard](https://www.tourismegard.com/fr/fiche/hebergement-collectif/villa-occitana-eco-resort-calvisson_TFO6199612/), [Expedia](https://www.expedia.com/Calvisson-Hotels-Villa-Occitana.h76556224.Hotel-Information) |
| « Villas couple dès 165 €, XXL dès 220 € » [V, office de tourisme] | **FAUX** | L'office de tourisme du Gard affiche « 110 € la nuitée » (cabane dès 138 €). Les montants 165 et 220 € n'ont été retrouvés nulle part. Staycation affiche 383 € pour une formule nuit. À vérifier sur le site officiel | [Tourisme Gard](https://www.tourismegard.com/destination/villes-villages/encore-plus-de-villes-et-villages/calvisson/ou-dormir/), [Staycation](https://www.staycation.co/en/hotels/villa-occitana-1798) |
| Spa 1 h en alternance bain nordique, bain à remous, sauna ; formules journée sur Staycation | **CONFIRMÉ** | **Prix manquants dans le rapport : « Spa 1 h et déjeuner » 126 € pour 2 ; « Massage 1 h et spa » 210 € pour 2.** Créneau à réserver par téléphone. Une autre page Staycation décrit « 600 m² de spa, piscine intérieure chauffée, bain à remous, hammam » : descriptif incohérent d'une page à l'autre | [Staycation spa et déjeuner](https://www.staycation.co/fr/hotels/villa-occitana-1798/day/spa-et-dejeuner-675), [Staycation Gard](https://www.staycation.co/fr/spa-france/gard) |
| Environ 30 € pour 2 h de spa (Mapstr) | **NON VÉRIFIABLE** | Aucun tarif officiel d'accès spa seul trouvé. Le prix réel observable est d'environ 63 €/pers. avec déjeuner | — |
| Spa vendu aux non-résidents | **CONFIRMÉ** | Via Staycation. Vente directe « à l'heure » par l'établissement non confirmée | [Staycation](https://www.staycation.co/fr/hotels/villa-occitana-1798) |
| TripAdvisor 3,4/5 (153 avis) | **CONFIRMÉ** | Détail : 60 excellent, 18 très bon, 31 moyen, 18 médiocre, 26 horrible. Rapport qualité-prix 3,2 ; service 3,7 ; propreté 4,0 | [TripAdvisor](https://www.tripadvisor.com/Hotel_Review-g1080041-d23958421-Reviews-Villa_Occitana-Calvisson_Gard_Occitanie.html) |
| Booking 8,6/10 (315 avis) | **NON VÉRIFIABLE** | Non retrouvé. Tourisme Gard affiche 8,9 | [Tourisme Gard](https://www.tourismegard.com/calvisson/villa-occitana/tabid/2858/offreid/f3ee9fb5-c598-4c79-88fd-e9612ad39327) |
| Staycation 9,3 (242) ; Hotels.com 9,6 (16) | **CONFIRMÉ** | — | [Staycation](https://www.staycation.co/fr/hotels/villa-occitana-1798), [lastminute](https://www.fr.lastminute.com/hotel/france/calvisson/villa-occitana_hid-11010292) |
| Piscine du 1er avril au 30 septembre | **NON VÉRIFIABLE** | Piscine extérieure saisonnière confirmée (9 h-18 h), dates non retrouvées | [Expedia](https://www.expedia.com/Calvisson-Hotels-Villa-Occitana.h76556224.Hotel-Information) |
| Critiques d'entretien et de rapport qualité-prix | **CONFIRMÉ** | — | [TripAdvisor](https://www.tripadvisor.com/Hotel_Review-g1080041-d23958421-Reviews-Villa_Occitana-Calvisson_Gard_Occitanie.html) |
| Société exploitante non identifiée | **NON VÉRIFIABLE** | Toujours non identifiée (fondateur prénommé Arnaud selon Objectif Gard). À chercher dans les mentions légales | [Objectif Gard](https://www.objectifgard.com/a-la-une/fait-du-jour-a-calvisson-la-villa-occitana-le-bali-de-la-vaunage-1398.php) |

### 3.2 Domaine de Verchant

| Affirmation | Verdict | Valeur corrigée | Sources |
|---|---|---|---|
| Spa : bassin de nage intérieur à 32 °C, sauna, hammam, jacuzzi extérieur, bain froid nordique, fitness | **CONFIRMÉ** | — | [Brochure spa](https://www.domainedeverchant.com/download/brochurespaverchant.pdf) |
| Accès journée et abonnements ouverts aux extérieurs | **CONFIRMÉ** | Brochures « Le Club Privé » (2023) et « Wellness Club 2025 ». Staycation vend aussi « 3 h d'accès au spa du Domaine » en option de La Maison Verchant | [Club Privé](https://www.domainedeverchant.com/download/leclubpv.pdf), [Staycation](https://www.staycation.co/fr/hotels/la-maison-verchant-3700) |
| Chambre à partir de 315 € ; 385 € (Gault&Millau) | **PARTIEL** | 315 € est bien affiché par Relais & Châteaux, sans préciser la prestation. 385 € non recoupé. Tarif du pass journée toujours introuvable | [Relais & Châteaux](https://relaischateaux.com/gb/spa/le-spa-verchant) |
| TripAdvisor 4,4/5 (882 avis) | **CONFIRMÉ** | 4,4 sur 880 avis au relevé | [TripAdvisor](https://www.tripadvisor.com/Hotel_Review-g641864-d785910-Reviews-Domaine_De_Verchant-Castelnau_le_Lez_Montpellier_Herault_Occitanie.html) |
| Relais & Châteaux 4,5/5 (2 582 avis) | **NON VÉRIFIABLE** | Non retrouvé | — |
| Nouvelle aile et spa rénové (juillet 2025) | **NON VÉRIFIABLE** | Non recoupé | — |

### 3.3 Plage Palace

| Affirmation | Verdict | Valeur corrigée | Sources |
|---|---|---|---|
| Offre Staycation : bassin à remous extérieur à 35 °C, hammam privatif, salle de sport, 2 coupes de champagne | **CONFIRMÉ** | Nom exact : « Spa 3 h en bord de mer ». **Prix manquant dans le rapport : 180 € pour 2.** Massage 1 h + spa : 400 € pour 2 | [Staycation](https://www.staycation.co/en/hotels/plage-palace-1356/day/spa-au-calme-plage-palace-4116), [Staycation Hérault](https://www.staycation.co/fr/spa-france/herault) |
| Chambre double dès 300 € | **CONFIRMÉ** | — | [Hérault Tourisme](https://www.herault-tourisme.com/fr/fiche/hotellerie/hotel-plage-palace--spa-palavas-les-flots_TFOHOTLAR034V52T567/) |
| Environ 357 € en moyenne (Momondo) | **PARTIEL** | Au relevé : 883 € en moyenne, offres autour de 281 €. Chiffre très volatil, sans valeur | [Momondo](https://www.momondo.fr/hotel/palavas-les-flots/Hotel-Plage-Palace.mhd4202085.ksp) |
| Booking 9,4 | **PARTIEL** | Booking 9,3 sur 638 avis. Le 9,4 vient de Trip.com (79 avis) | [MyBoutiqueHotel](https://www.myboutiquehotel.com/fr/boutique-hotels-palavas-les-flots/hotel-plage-palace.html), [Trip.com](https://nz.trip.com/hotels/palavas-les-flots-hotel-detail-22154308/htel-plage-palace-spa) |
| TripAdvisor hôtel 4,3/5 (218 avis) | **CONFIRMÉ** | — | [TripAdvisor](https://www.tripadvisor.com/Hotel_Review-g644109-d17376961-Reviews-Plage_Palace-Palavas_les_Flots_Herault_Occitanie.html) |
| TripAdvisor restaurant 3,1/5 (158 avis) | **NON VÉRIFIABLE** | Chiffre non retrouvé. Le fond est confirmé : prix du restaurant et du bar jugés excessifs (salade à 24 €, glace à 10 €) | [TripAdvisor restaurant](https://www.tripadvisor.com/Restaurant_Review-g644109-d17370375-Reviews-Plage_Palace-Palavas_les_Flots_Herault_Occitanie.html) |
| Parking à 30 €/nuit | **NON VÉRIFIABLE** | Non retrouvé | — |

### 3.4 Saunas sociaux parisiens

| Affirmation | Verdict | Valeur corrigée | Sources |
|---|---|---|---|
| Ground Control : ouverture janvier-février 2026 | **CONFIRMÉ** | 28 janvier 2026 (une source donne le 4 février) | [Le Bonbon](https://www.lebonbon.fr/paris/news/premiers-saunas-bains-collectifs-debarquent-paris/), [L'Essentiel](https://www.lessentiel.fr/paris/idees-sorties/2026-01-28/des-saunas-et-bains-collectifs-en-exterieur-ouvrent-aujourdhui-paris) |
| 20 € les 90 minutes | **CONFIRMÉ** | Bains froids inclus | [FAQ officielle](https://saunas-collectifs.fr/faq) |
| 10 € en tarif réduit | **PARTIEL** | Le site décrit une adhésion à 20 €/mois donnant -50 % sur les sessions, plus des tarifs solidaires. Le « 10 € » n'est pas un tarif d'habitué gratuit | [FAQ officielle](https://saunas-collectifs.fr/faq) |
| Environ 15 personnes par session | **NON VÉRIFIABLE** | Non retrouvé. Espace de 100 m², 3 saunas | [artsixMic](https://www.artsixmic.fr/2026-02-04-ouverture-des-premiers-saunas-et-bains-collectifs-a-ground-control-169818-2/) |
| Mercredi au dimanche, 7 h-22 h | **CONFIRMÉ** | Site : 7 h-22 h 30, dernière session à 21 h | [Site officiel](https://saunas-collectifs.fr/saunagroundcontrol) |
| « Un autre site cite 45 € » pour Ground Control | **FAUX** | 45 € est le tarif de Sant Roch, attribué par erreur | [Bonjour Paris](https://bonjourparis.com/spa-services/the-best-saunas-in-paris/) |
| Dropp : 400 m², plein air, sessions de 90 min, jusqu'à 23 h le vendredi | **CONFIRMÉ** | Prix toujours non trouvé | [Le Bonbon](https://www.lebonbon.fr/paris/loisirs/plus-grand-sauna-plein-air-france-paris/) |
| Dropp : ouverture en 2025 | **NON VÉRIFIABLE** | Date non trouvée | — |
| Sant Roch : ouverture le 2 mars 2026, sauna de 60 m², 5 bains froids de 3 à 8 °C, 400 m², 8 h-22 h, 45 € la session | **CONFIRMÉ** | — | [Sortiraparis](https://www.sortiraparis.com/en/what-to-do-in-paris/sport-wellness/articles/341220-sant-roch-paris-s-new-400m-wellness-sanctuary-featuring-an-xxl-sauna-and-cold-plunge-pools), [Time Out](https://www.timeout.fr/paris/actualites/le-plus-grand-spa-de-france-ouvre-a-paris-face-aux-tuileries-avec-une-nouvelle-vision-du-bien-etre-030526) |
| Sant Roch : 4 500 visiteurs le premier mois, occupation supérieure à 85 % | **PARTIEL** | Le chiffre a bien été publié (« plus de 4 500 visiteurs », Spa Business, 17 avril 2026), mais **c'est une déclaration de l'exploitant, non auditée**, et l'article paraît six semaines après l'ouverture. Les reprises proviennent toutes du même communiqué. À ne pas utiliser comme hypothèse de fréquentation | [Spa Business](https://www.spabusiness.com/wellness-news/Parisian-contrast-therapy-destination-Sant-Roch-reveals-first-months-successes/362816), [Prism News](https://www.prismnews.com/hobbies/ice-baths/paris-ice-bath-club-draws-crowds-blending-sauna-and-cold) |

### 3.5 Glampings, insolites et autres comparables

| Affirmation | Verdict | Valeur corrigée | Sources |
|---|---|---|---|
| Finca Lessya : dès 168 €/nuit ; spa privatisable de 60 m² (sauna, massages) | **CONFIRMÉ** | — | [Tourisme Occitanie](https://www.tourisme-occitanie.com/fr/fiche/hebergement-locatif/domaine-finca-lessya-lodge-insolite--spa-lodge-prestige-de-l-oliveraie-mauguio_TFOHLOLAR034V52RNCH/) |
| Finca Lessya : spa à 24 €/60 min ; note 9,3 | **NON VÉRIFIABLE** | Supplément spa non retrouvé | — |
| Finca Lessya : 212 $ sur Travelocity (avril 2026) | **CONFIRMÉ** | — | [Travelocity](https://www.travelocity.com/Mauguio-Hotels-Domaine-FINCA-LESSYA-SPA.h125851046.Hotel-Reviews) |
| Soulëyourt : sauna et bain nordique, prix « n.t. » | **PARTIEL** | **Prix trouvé : 50 € l'heure en séance privative de sauna ou de bain nordique**, sur réservation (site officiel) | [souleyourt.com](https://souleyourt.com/sauna-et-spa/) |
| Soulëyourt : GreenGo 4,4 (30), Airbnb 4,2 (10) | **NON VÉRIFIABLE** | Non recoupé | — |
| Coucoo Grands Cépages : 27 cabanes | **PARTIEL** | 20 cabanes (16 duo, 4 familiales) selon les offices de tourisme ; 27 selon Le Fooding | [OT PACA](https://provence-alpes-cotedazur.com/en/plan-your-stay/accommodation/all-accommodation/hotels/cabanes-des-grands-cepages-sorgues-en-2861664), [Le Fooding](https://lefooding.com/hotels/hotel-coucoo-grands-cepages-sorgues) |
| Coucoo : 265-330 €/nuit | **PARTIEL** | TripAdvisor affiche 180-250 € pour une cabane standard ; des avis citent 360 €. Extras élevés (dîner 75 €, apéritif 20-25 €) | [TripAdvisor](https://www.tripadvisor.fr/Hotel_Review-g1143392-d12495442-Reviews-or5-Coucoo_Grands_Cepages-Sorgues_Vaucluse_Provence_Alpes_Cote_d_Azur.html) |
| Coucoo : TripAdvisor 4,5 (64) | **CONFIRMÉ** | — | [TripAdvisor](https://www.tripadvisor.com/Hotel_Review-g1143392-d12495442-Reviews-Cabanes_Des_Grands_Cepages-Sorgues_Vaucluse_Provence_Alpes_Cote_d_Azur.html) |
| Coucoo : fermé de fin novembre à fin février | **PARTIEL** | Saison 2026 : du 6 mars au 22 novembre, avec ouvertures exceptionnelles les week-ends de décembre | [Avignon Tourisme](https://avignon-tourisme.com/en/offres/cabanes-des-grands-cepages-sorgues-en-4151691/) |
| Groupe Coucoo : CA 3,7 M€ (2019) puis 8 M€ ; occupation 85 % | **PARTIEL** | 3,7 M€ en 2019 et « près de 8 M€ » ensuite : confirmés. **Occupation : 75 à 80 % sur mars-novembre, pas 85 %.** Coût moyen : 3 M€ pour un site de 25 cabanes | [L'Hôtellerie-Restauration](https://www.lhotellerie-restauration.fr/actualite/coucoo-ouvre-son-capital-pour-booster-son-developpement), [L'Écho touristique](https://www.lechotouristique.com/article/coucoo-leve-35-millions-deuros-aupres-de-bpi-et-bazarchic) |
| Cabanes dans les Bois : 30 à 33 cabanes, plus de 100 €/nuit | **PARTIEL** | 30 hébergements, à partir de 89 € | [Logis](https://www.logishotels.com/en/hotel/logis-hotel-les-cabanes-dans-les-bois-203823) |
| Cabanes dans les Bois : domaine bio de 110 ha, ouverture vers 2012 | **NON VÉRIFIABLE** | Non retrouvé | — |
| Trésors de campagne : dès 281 €, 6 hébergements | **CONFIRMÉ** | — | [GreenGo](https://www.greengo.voyage/hote/cabanes-tresors-de-campagne-spa-privatif-piscine-restaurant-ferme-equestre-jardin-permaculture) |
| Domaine Cabanes & Spa Ardèche : 16 hébergements, dès 300 €, cabanes à 7-9 m | **CONFIRMÉ** | — | [GreenGo](https://www.greengo.voyage/hote/domaine-cabanes-spa-ardeche) |
| Fontenille : suite dès 539 € ; retraite 1 160 €/pers. | **PARTIEL** | Chambre dès 467 €, suite Jardin dès 479 € (Relais & Châteaux). Le prix de 1 160 € n'a pas été retrouvé | [Relais & Châteaux](https://www.relaischateaux.com/fr/france/domaine-de-fontenille-lauris) |
| Bains des Bois : 30-35 €/adulte, minimum 2 personnes | **CONFIRMÉ** | 30 € + 5 € avec peignoir et sabots ; session de 1 h ou 1 h 30 selon la fiche | [OT PACA](https://provence-alpes-cotedazur.com/que-faire/detente-et-loisirs/toutes-les-activites-detente-et-loisirs/les-bains-des-bois-montclar-fr-3225090/) |
| Spa de Fabrègues : Planity 4,8 (179) | **CONFIRMÉ** | — | [Planity](https://www.planity.com/le-spa-de-fabregues-34690-04g) |
| Spa de Fabrègues : 20 € 1 h, 30 € 2 h, 40 € duo [V] | **PARTIEL** | Funbooker : 20 € l'heure en semaine, **36 € les 2 h**, tarifs doublés le dimanche. Grille officielle non lue | [Funbooker](https://www.funbooker.com/fr/category/spa/montpellier) |
| Nid'O : 15 €/30 min, 40 €/h en duo | **FAUX** | Ces prix sont ceux de **L'Esprit A** (Port Marianne, Montpellier) : 15 à 20 € les 30 min en solo, 40 € l'heure en duo. Les tarifs du Nid'O ne sont pas publiés ; Funbooker mélange les adresses | [Funbooker](https://www.funbooker.com/fr/category/spa/montpellier) |
| Balnéa : 21-23 €/adulte en 2026, formules dès 42 € | **PARTIEL** | 21-23 € figure bien sur une fiche 2026, mais la grille a été **abaissée après l'incendie** jusqu'au 12 novembre 2026. « 42 € » est un forfait entrée 2 h + déjeuner de 2022-2023 (45 € en 2024) | [Pyrénées31](https://www.pyrenees31.com/en/equipments/balnea-2), [info.fr](https://info.fr/hautes-pyrenees-apres-incendie-espace-japonais-centre-balnea-rouvre-tarifs-reduits/) |
| Balnéa : 190 000 entrées et 3 M€ (2012), 300 000 entrées, 6 M€, 46 ETP | **NON VÉRIFIABLE** | Non recoupé dans cette session | — |
| Saint-Thomas : 9 € bains, 18 € avec bien-être, abonnement annuel 120 € | **CONFIRMÉ** | Abonnement annuel avec bien-être : 195 € | [Tourisme Occitanie](https://www.tourisme-occitanie.com/fr/fiche/equipement/bains-de-saint-thomas-fontpedrouse_TFOLOILAR066FS000AT/) |
| Caudalie : accès au spa uniquement avec un soin | **CONFIRMÉ** | — | [Brochure spa](https://www.sources-hotels.com/wp-content/uploads/2025/06/Brochure-Spa-Les-Sources-de-Caudalie.pdf) |
| Caudalie : rituels demi-journée 275-330 € (2024) | **PARTIEL** | Grille 2025 : rituel Signature 340 € en semaine, 375 € le samedi | [Tarifs 2025](https://sources-caudalie.com/wp-content/uploads/2024/12/TARIFS_SPA_2025-FR.pdf) |
| QC Terme : 42-52 € le soir ; 70 € passé à 84 € | **NON VÉRIFIABLE** | Seule source : un avis non daté. Grille officielle non accessible | [Gowork](https://gowork.fr/qc-terme-chamonix-chamonix-mont-blanc) |
| QC Terme : « déjeuner bien-être 26 € » | **FAUX** | « Wellness Lunch » à 42 € selon l'office de tourisme | [Haute-Savoie Mont-Blanc](https://hautesavoiemontblanc-tourisme.com/offres/qc-spa-chamonix-chamonix-mont-blanc-fr-5896207/) |
| Löyly : 19 € pour 2 h | **FAUX** | **25 € pour 2 h** (site officiel, serviette incluse), 12 € l'heure supplémentaire | [Site officiel](https://www.loylyhelsinki.fi/en/public-sauna) |
| Löyly : plus de 400 000 visiteurs la première année [V] | **NON VÉRIFIABLE** | Non retrouvé | — |
| Strøm : 69-104 $ CA la journée, 59 $ le soir en semaine | **CONFIRMÉ** | Le tarif du soir date de 2024 | [Québec Cité](https://www.quebec-cite.com/fr/quoi-faire-quebec/strom-spa-soir) |
| Strøm : meilleur day spa du Canada 2024 et 2025 (World Spa Awards) | **PARTIEL** | « Canada's Best Day Spa 2025, deux années de suite » selon Narcity ; organisme non confirmé | [Narcity](https://www.narcity.com/fr/quebec/black-friday-meilleur-spa-canada-quebec-strom-2024) |
| Bathhouse vise environ 120 M$ de CA | **PARTIEL** | C'est un rythme annualisé attendu fin 2026, déclaré à CNBC, pas un CA réalisé. Levée de 35 M$ | [Athletech](https://athletechnews.com/bathhouse-raises-35-million-plots-expansion-as-social-sauna-boom-scales/) |
| Othership a levé 19,3 M$ | **CONFIRMÉ** | 4 tours, dernier de 11,3 M$ en juin 2025 | [CB Insights](https://www.cbinsights.com/company/inward-breathwork/financials) |
| Soho Farmhouse Lazy Lake : 70 £ pour 2 h, réservé aux membres | **CONFIRMÉ** | Prix d'août 2024 | [Soho House](https://www.sohohouse.com/house-notes/issue-006/soho-health-club/soho-farmhouse-lazy-lake) |

---

## 4. Cas d'échec (section D du rapport)

| Cas | Verdict | Ce qui est établi, correction | Sources |
|---|---|---|---|
| Groupe Millésime : redressement en 2024, conflit avec BMF, cession de Sacy et Porto | **PARTIEL** | Conflit avec BMF depuis juin 2023 et communiqué du 16 avril 2024 : confirmés. **La date du redressement est incertaine** : Copeps indique « 2025 : redressement judiciaire et cession à Reybier », avec un plan de cession de Sacy accepté début 2026. Aucune liquidation établie. À vérifier au BODACC | [TourMaG](https://www.tourmag.com/Millesime-la-chute-de-l-etoile-montante-du-luxe-version-emotion_a130689.html), [Copeps](https://copeps.fr/actualites/chateau-de-sacy-redressement-judiciaire/) |
| Alpha Camping : redressement puis liquidation (Paris, 2026), « franchises reprises par Maeva » | **PARTIEL** | Conversion du redressement en liquidation : confirmée (procédure ouverte en 2025, réf. P202504397). **Erreur sur Maeva** : Maeva a racheté 5C Développement, propriétaire des marques Camping Paradis et Ushuaïa Villages. Alpha Camping n'était qu'un gestionnaire de campings sous cette enseigne. La marque n'a pas fait faillite | [Doctrine](https://www.doctrine.fr/d/TCOM/Paris/2026/TCOMPC1F13CD7CE35413C4476), [Chambers](https://chambers.com/articles/de-pardieu-advises-maeva-on-the-acquisition-of-5c-developpement) |
| YUJ Yoga : liquidation le 13 août 2026 | **CONFIRMÉ** | Société YUJ-Yoga With Style, SIREN 799 900 576. Jugement du 13 août 2026 du tribunal des activités économiques de Paris, cessation des paiements fixée au 28 mai 2026, liquidateur Me Denis Gasnier (BTSG). Huit salles fermées à l'été 2026 | [societe.com](https://www.societe.com/societe/yuj-yoga-with-style-799900576.html), [Annuaire des entreprises](https://annuaire-entreprises.data.gouv.fr/entreprise/799900576), [Franceinfo](https://www.franceinfo.fr/replay-radio/l-il-de-constance/pilates-gonflette-et-gourous-dechus-pourquoi-les-studios-de-yoga-ferment-a-la-chaine_8217340.html) |
| YUJ : dépôt de bilan le 8 juillet 2026, loyer de 87 k€, arriéré supérieur à deux ans de loyer | **NON VÉRIFIABLE** | Source unique (cabinet d'avocat qui cherche des clients). Les causes (baisse de fréquentation, loyers) sont cohérentes avec la presse | [Simonnet Avocat](https://www.simonnetavocat.fr/liquidation-de-yuj-yoga-comment-se-faire-rembourser/) |
| Chambres d'hôtes, Châteauroux, 2025 | **NON VÉRIFIABLE** | Jugement anonymisé, non recoupé | — |
| Vert Marine : environ 30 piscines fermées en 2022, coût de l'énergie | **CONFIRMÉ** | 5 septembre 2022, facture d'énergie passée de 15 à 100 M€ selon l'entreprise. **Fermeture temporaire** : l'Aquapolis de Limoges a rouvert mi-septembre 2022. Ce n'est pas une faillite | [Euronews](https://www.euronews.com/2022/09/06/energy-crisis-france-closes-30-swimming-pools-amid-soaring-heating-bills), [Connaissance des énergies](https://www.connaissancedesenergies.org/afp/prix-de-lenergie-le-centre-aquatique-aquapolis-de-limoges-va-rouvrir-ses-portes-220913) |
| « Établissement alsacien créé en 1991 », activité non confirmée | **PARTIEL** | Identifié : **La Cour de Honau, La Wantzenau (67), centre de loisirs et de bien-être de 10 000 m² (hammam, piscine, sauna, fitness, brasserie, institut)**, CA 2020 d'environ 1,27 M€, une vingtaine de salariés, en redressement judiciaire. C'est le cas le plus proche du projet et le rapport le sous-exploite. La multiplication par quatre de l'énergie n'a pas été recoupée | [Journal des Entreprises](https://www.lejournaldesentreprises.com/breve/la-cour-de-honau-ferme-ses-portes-la-wantzenau-2073149) |
| Micro-entreprise de bien-être, Béziers, 2025 | **NON VÉRIFIABLE** | Jugement anonymisé, non recoupé. Peu utile | — |
| Reayrt Vradda (île de Man) | **CONFIRMÉ** | Liquidation mi-2025, fonds insuffisants pour finir les travaux, terrain de Port Erin Commissioners (10 acres), bail résilié | [IOM Today](https://www.iomtoday.co.im/news/luxury-camp-site-firm-set-to-go-under-as-director-says-there-was-no-alternative-795783), [Manx Radio](https://www.manxradio.com/news/isle-of-man-news/port-erin-commissioners-lease-to-reayrt-vradda-glamping-site-to-be-disclaimed) |
| Sauna de Swansea : fermé après plaintes de voisins | **PARTIEL** | Il s'agit de **Hälsa Sauna, Caswell Bay**. Refus d'un permis rétroactif (9 motifs, 43 objections : vis-à-vis, bruit, eaux usées, stationnement, impact paysager). Exploité sans autorisation depuis 2023. Il a rouvert en contestant la décision : « fermé » est inexact | [GB News](https://www.gbnews.com/news/swansea-news-sauna-ordered-close-neighbours-complained-naked-users-visible), [Nation.Cymru](https://nation.cymru/news/welsh-sauna-reopens-in-fight-against-planning-refusal) |
| SARL « La Cabane », Romans, juillet 2026 | **NON VÉRIFIABLE** | Activité inconnue. À retirer : n'apporte rien | — |

---

## 5. Chiffres clés et signaux de marché

| Affirmation | Verdict | Valeur corrigée | Sources |
|---|---|---|---|
| Insolite : 2 226 sites professionnels, +30 % depuis 2022 | **CONFIRMÉ** | 3e Observatoire (AbracadaRoom / Alliances, décembre 2024) | [Hospitality ON](https://hospitality-on.com/fr/insolite/les-hebergements-insolites-arrivent-lage-de-raison-selon-le-3e-observatoire-du-secteur), [L'Écho touristique](https://www.lechotouristique.com/article/hebergements-insolites-en-france-une-progression-de-30-par-rapport-a-2022) |
| Prix moyen de 301 €/nuit, +18 % depuis 2019 | **CONFIRMÉ** | **301 € vaut pour les cabanes seulement. Toutes typologies confondues : 265 €.** Ne pas présenter 301 € comme « moyenne nationale de l'insolite » | [Hospitality ON](https://hospitality-on.com/fr/insolite/les-hebergements-insolites-arrivent-lage-de-raison-selon-le-3e-observatoire-du-secteur) |
| Les cabanes dans les arbres reculent entre 2021 et 2023 | **CONFIRMÉ** | Après +370 % entre 2012 et 2023. La précision « pour la première fois depuis 2012 » n'est pas dans les extraits. Les cabanes sur pilotis progressent de 75 % | [L'Écho touristique](https://www.lechotouristique.com/article/hebergements-insolites-en-france-une-progression-de-30-par-rapport-a-2022) |
| Coucoo : environ 2 ans pour la modification du PLU et le permis d'aménager | **CONFIRMÉ** | — | [L'Hôtellerie-Restauration](https://www.lhotellerie-restauration.fr/actualite/coucoo-ouvre-son-capital-pour-booster-son-developpement) |
| Proposition de loi au Sénat (mars 2026), démolition par le préfet, jugement en 2 ans et demi | **CONFIRMÉ** | PPL n° 459 déposée le 23 mars 2026, **adoptée par le Sénat en première lecture le 6 mai 2026**, transmise à l'Assemblée. Pas encore définitive. L'article 4 fait courir la prescription à partir de la découverte des faits, dans la limite de 10 ans | [Sénat, synthèse](https://www.senat.fr/rap/l25-550/l25-550-syn.pdf), [Banque des Territoires](https://www.banquedesterritoires.fr/cabanisation-la-droite-senatoriale-impose-sa-ligne-la-gauche-denonce-un-texte-repressif) |
| Hébergement touristique en zone A ou N possible seulement en STECAL | **NON VÉRIFIABLE** | Non recoupé en ligne dans cette session. Conforme à ce que je connais du code de l'urbanisme (art. L.151-13), à faire valider par un urbaniste | — |
| Royaume-Uni : 45 saunas en 2023, 147 début 2025 | **CONFIRMÉ** | La carte de la British Sauna Society recense 844 saunas en 2026 (périmètre plus large) | [Euronews](https://fr.euronews.com/2025/03/13/royaume-uni-les-saunas-ont-le-vent-en-poupe), [British Sauna Society](https://www.britishsaunasociety.org.uk/the-british-sauna-bather-survey-2026) |
| GWI : « la moitié des répondants réalisent au moins 300 000 $ par mois » | **PARTIEL** | **44 %** des exploitants ayant communiqué leur chiffre (mise à jour du 6 octobre 2026). Échantillon de 47 répondants dont 35 aux États-Unis, déclaratif, « non représentatif » selon le GWI. 30 % ont investi au moins 5 M$ à l'ouverture. Sans rapport avec un projet à Montpellier | [GWI, 6 oct. 2026](https://globalwellnessinstitute.org/wp-content/uploads/2026/10/Bathhouse_Survey_Media_Key_Findings_Oct-6_26.pdf) |
| Montpellier 2025 : 50 % des professionnels en baisse, 25 % satisfaits | **CONFIRMÉ** | Les 50 % restants déclarent une saison équivalente à 2024. En 2024, 56 % étaient en baisse | [Montpellier Tourisme](https://www.montpellier-tourisme.fr/app/uploads/montpelliertourisme/2026/05/Note-de-conjoncture-septembre-et-bilan-saison-2025.pdf) |
| Nuitées hôtelières de l'Hérault : -1,8 % en 2024 | **NON VÉRIFIABLE** | Non recoupé | — |
| Hyrox : environ 124 € le dossard, étapes à Nice et Bordeaux | **CONFIRMÉ** | Bordeaux du 30 septembre au 4 octobre 2026, Nice du 29 octobre au 1er novembre 2026. Tarif dynamique | [Red Bull](https://www.redbull.com/fr-fr/hyrox-2026-2027-guide) |
| Gigafit déploie des bains froids dans son réseau | **PARTIEL** | Annonce d'août 2024 (« Cold Bath »). Déploiement effectif non confirmé | [Toute la Franchise](https://www.toute-la-franchise.com/news-gigafit-lance-un-nouveau-service-de-bains-glaces) |
| Airbnb et Booking captent plus de 50 % des réservations d'insolite | **NON VÉRIFIABLE** | Non recoupé (le rapport le classe déjà [E]) | — |

---

## 6. Test de l'affirmation « créneau libre »

| Affirmation du rapport | Verdict | Ce que la recherche montre | Sources |
|---|---|---|---|
| « L'hybride box ou studio + sauna/bain froid n'existe pas encore à Montpellier » | **FAUX** | **Le KREW** (530 rue Raymond Recouly, Montpellier) : salle Hyrox officielle de 650 m², bain froid, sauna, balnéo, 10 kinés du sport, abonnements de 65 à 109 €/mois. **Dopa House** (1 av. Émile Bertin-Sans, Montpellier, ouvert le 14 septembre 2026) : Lagree, Pilates, yoga + cryothérapie, sauna infrarouge, caisson hyperbare. Voir section 7 | [lekrew.fr](https://www.lekrew.fr/), [dopahouse.fr](https://dopahouse.fr/) |
| « Aucun lieu sport + sauna dans le Gard » (implicite, section F) | **FAUX** | **Le Carré, Nîmes** : salle de sport avec bain froid Avantopool et sauna infrarouge, 15 € la séance récupération | [lecarre-nimes.fr](https://www.lecarre-nimes.fr/epace-sauna) |
| « Les saunas sociaux n'existent en France qu'à Paris » | **FAUX** | **Coin Nordic**, plage d'Amphion-les-Bains (Léman) : saunas collectifs en bois sur la plage, séance collective de 1 h 20 à 16 €, saison du 26 septembre 2026 au 16 mai 2027. Le réseau Sauna et Bains Collectifs annonce d'autres sites en France | [coin-nordic.fr](https://www.coin-nordic.fr/), [Réseau SBC](https://saunas-collectifs.fr/reseau-des-saunas-collectifs) |
| « Aucun bain nordique extérieur en accès journée à Montpellier » | **PARTIEL** | Vrai pour la ville, selon les recherches. Mais dans l'Hérault, **Soulëyourt (Cazilhac)** vend sauna et bain nordique au feu de bois à 50 € l'heure et se référence sous « Sauna et Bain nordique à Montpellier ». L'ouverture aux non-résidents reste à confirmer par téléphone. Dans le Gard, Villa Occitana le propose déjà via Staycation | [souleyourt.com](https://souleyourt.com/sauna-et-spa/) |
| « Aucun sauna social à Montpellier, dans l'Hérault ni le Gard » | **NON VÉRIFIABLE** | Non réfuté : aucun sauna collectif extérieur à sessions ouvertes n'a été trouvé (Montpellier, Sète, Nîmes, Béziers, Lunel, Palavas, La Grande-Motte). Preuve impossible sans Instagram ni Google Maps | — |
| « Ni sauna mobile de plage » | **NON VÉRIFIABLE** | Non réfuté. Seul trouvé : Liva Sauna, location de sauna mobile au feu de bois livrée partout en France | [livasauna.fr](https://livasauna.fr/location-sauna/) |
| « Aucun lieu guinguette + sauna/bain froid en France » | **PARTIEL** | Contredit par l'exemple n° 24 du rapport lui-même : Ground Control est un bar-food court festif qui héberge des saunas collectifs. Le format « bar + sauna social » existe donc, à Paris | [Le Bonbon](https://www.lebonbon.fr/paris/news/premiers-saunas-bains-collectifs-debarquent-paris/) |
| « Les day spas autour de Montpellier sont petits et intérieurs » | **PARTIEL** | Trois acteurs de taille omis : Zéphyr Spa (700 m², Staycation), Vichy Spa Hôtel de Fontcaude à Juvignac (2 600 m², piscine extérieure, accès journée), O'balia à Balaruc (fermé pour travaux, réouverture annoncée pour 2026) | voir section 7 |
| « Concurrent le plus proche sur l'expérience : Villa Occitana, à 35 min » | **PARTIEL** | Vrai pour le format nature + restauration. Pour le sport + récupération, les concurrents sont dans Montpellier même (KREW, Dopa House, Verchant Wellness Club) | — |

**Lecture.** Ce qui reste libre, sous réserve de vérification terrain : un lieu **extérieur, collectif, à la session, avec bar**. Ce qui n'est plus libre : le couple sport + récupération chaud-froid en ville, déjà vendu **inclus dans un abonnement à 87-109 €/mois** chez Le KREW. Cela pèse sur l'hypothèse d'un pass à 25-40 € pour la clientèle sportive.

---

## 7. Concurrents et acteurs non repérés par le rapport

### 7.1 Montpellier et Hérault

| Acteur | Lieu | Ce qu'il propose | Prix | Pourquoi il compte | Source |
|---|---|---|---|---|---|
| **Le KREW** | Montpellier, 530 rue Raymond Recouly | Salle Hyrox officielle de 650 m², petits groupes, 10 kinés du sport, **bain froid, sauna, balnéo**, open gym, running club | 65 €/mois (3 séances/sem.), 87 € (4 séances + 1 récupération/sem.), 109 € (illimité, récupération illimitée) | Concurrent direct du volet « sport en containers + sauna ». Date d'ouverture non trouvée | [lekrew.fr](https://www.lekrew.fr/) |
| **Dopa House Health Club** | Montpellier, 1 av. Émile Bertin-Sans | Lagree, Pilates, yoga, stretching + cryothérapie -110 °C, sauna infrarouge privatif, caisson hyperbare, photobiomodulation. Ouvert 7 j/7 | « Athlete Recovery » 109 €, « Deep Relax » 69 € ; cours par crédits | **Ouvert le 14 septembre 2026**, deux mois avant le rapport. Concurrent direct du volet Pilates/yoga + récupération. Source : site officiel seul | [dopahouse.fr](https://dopahouse.fr/) |
| **La Maison Verchant** | Castelnau-le-Lez / Montpellier | Maison avec jardin, piscine, **sauna, bain froid, jacuzzi**, vendue sur Staycation, avec option 3 h au spa du Domaine | n.t. | Verchant décline déjà une offre plus accessible | [Staycation](https://www.staycation.co/fr/hotels/la-maison-verchant-3700) |
| **Les Bains d'Hygie** | Castelnau-le-Lez, 6 rue Étienne Dantoine | Balnéo privative de 200 m² : hammam, baignoire balnéo, **Ice Cave**, douche sensorielle | 102 € solo / 194 € duo (1 h balnéo + massage 30 min) | Chaud-froid privatif haut de gamme à 10 min du centre | [Tourisme Occitanie](https://www.tourisme-occitanie.com/fr/fiche/equipement/les-bains-d-hygie-castelnau-le-lez_TFOLOILAR034V52IXME/), [carte des soins](https://cdt34.media.tourinsoft.eu/upload/CARTE-DES-SOINS--5-.pdf) |
| **L'Esprit A** | Montpellier, Port Marianne | Hammam, sauna, bain à remous en accès direct | 15-20 € les 30 min, 40 € l'heure en duo | Day spa urbain d'entrée de gamme, confondu avec le Nid'O dans le rapport | [Funbooker](https://www.funbooker.com/fr/category/spa/montpellier) |
| **Vichy Spa Hôtel / Spa de Fontcaude** | Juvignac | 2 600 m² de bien-être, piscine intérieure, piscine extérieure en saison, hammam, sauna, accès journée | n.t. | Le plus grand spa de la métropole. Avis 2025 signalant sauna en panne | [TourMaG](https://www.tourmag.com/Vichy-Spa-Hotel-Montpellier-Juvignac-votre-echappee-Bien-etre-sante_a66030.html) |
| **O'balia (spa thermal)** | Balaruc-les-Bains | Thermoludisme (bassins, sauna, hammam) | — | **Fermé pour deux ans de travaux, réouverture annoncée pour 2026.** À surveiller : gros équipement public à 30 min | [Archipel de Thau](https://en.archipel-thau.com/spa-thermal-o-balia.html) |
| **Easy Spa Concept** (ex-Le Louxor) | Lattes, Port Ariane | Hammam, sauna, spa, soins à 1 €/min | — | C'est le vrai spa de Port Ariane | [Guide-piscine](https://www.guide-piscine.fr/thermes-de-france/herault/easy-spa-concept-a-lattes-1917_T) |
| **Spa Ostrealia – Domaine Tarbouriech** | Marseillan | Spa de domaine ostréicole, ouvert toute l'année 2026 | n.t. | Modèle « domaine + spa + table » sur l'étang de Thau | [Hérault Tourisme](https://www.herault-tourisme.com/fr/ficheequipements-de-loisirs/spa-ostrealia-au-domaine-tarbouriech-marseillan_TFOLOILAR034V51KZZK) |
| **Movida Montpellier**, **In&Out Fitness by Club 7** | Montpellier | Salles de sport avec sauna (et hammam, douche glacée, piscine pour Movida), sauna inclus dans l'abonnement | — | Le sauna en salle de sport est déjà banal | [Ma Salle de Sport](https://www.masalledesport.com/salle/12811,movida-montpellier,club-de-fitness,montpellier,34080,fr), [Hérault Tourisme](https://www.herault-tourisme.com/fr/fiche/equipements-de-loisirs/inout-fitness-by-club7-montpellier_TFOLOILAR034V50FMQQ) |
| Cryoform, Cryopôle, SBA Cryo Electro | Montpellier, Lattes | Cryothérapie corps entier, électrostimulation, sauna (SBA) | — | Offre « récupération » déjà installée | [Cryoform](https://www.cryoform.fitness/), [SBA](https://www.sbacryoelectro.com/) |
| Autres salles Hyrox : M34 CrossFit South (Pérols), Physik Perf (Mauguio), Fight Force (Saint-Jean-de-Védas) | Métropole | Hyrox, CrossFit ; espace récupération cité pour Fight Force, sans détail | — | À appeler : présence de bain froid non confirmée | [M34](https://m34crossfitsouth.fr/planning-box-crossfit-montpellier-perols/), [Blog Territoria](https://blog-territoria.org/sports/hyrox-montpellier/) |

### 7.2 Gard

| Acteur | Lieu | Ce qu'il propose | Prix | Source |
|---|---|---|---|---|
| **Le Carré Sport & Bien-être** | Nîmes, 620 chemin des Hauts de Nîmes | Salle de sport + espace récupération : bain froid Avantopool (10-15 °C), sauna infrarouge, pressothérapie | Bain froid + sauna 15 €, avec pressothérapie 30 € | [lecarre-nimes.fr](https://www.lecarre-nimes.fr/epace-sauna) |
| Cryopôle | Caissargues | Cryothérapie et récupération, cures et abonnements | — | [Planity](https://www.planity.com/cryopole-30132-caissargues) |

### 7.3 Reste de la France : acteurs qui contredisent « uniquement à Paris »

| Acteur | Lieu | Format | Prix | Source |
|---|---|---|---|---|
| **Coin Nordic** | Amphion-les-Bains (74), plage du Léman | Saunas collectifs en bois sur la plage, plongeon dans le lac, saisonnier (automne-printemps) | 16 € la séance collective de 1 h 20 | [coin-nordic.fr](https://www.coin-nordic.fr/) |
| **INVERSO*** | Crolles (38), près de Grenoble | Suites privatives sauna infrarouge + bain froid (3-10 °C), ateliers, soirées « apéro sauna & bain froid », privatisation entreprises | 40 €/pers. les 50 min ; abonnement dès 22,50 €/séance ; privatisation 490 € pour 12 pers. | [inversoexperience.fr](https://inversoexperience.fr/tarif-seances-sauna-bain-froid/) |
| **Recovery Lab – Saun'Ice** | Hem (59), près de Lille | Sauna infrarouge + bain glacé | 50 € l'heure, 200 € les 5 séances, **illimité à 69,90 €/mois** | [recoverylab.fr](https://recoverylab.fr/saunice/) |
| **Le Plongeoir Social Club** | Marseille 7e, villa La Luna | Événements de bains glacés en bord de mer (3e édition le 19 avril 2026) | « En dessous du marché » | [Luma](https://luma.com/d1d9zidv?locale=fr) |
| Pampa Sauna, Wild Sauna by Popaian | Pyrénées ; Bretagne (Le Pouldu, Guidel) | Saunas mobiles au feu de bois, bain froid inclus | — | [pampasauna.com](https://pampasauna.com/en/), [popaian.fr](https://www.popaian.fr/) |

**Marseille, Aix, Toulouse, Nice, Perpignan, Béziers, Sète** : aucun sauna social collectif ni studio de thérapie par contraste identifié dans ces recherches. Résultat négatif à prendre avec prudence (mêmes limites qu'en section 0).

---

## 8. Corrections à apporter au rapport d'origine

Par ordre d'importance pour la décision d'investissement.

1. **Sections B2-4, E1-4 et F-1 : retirer « l'hybride sport + sauna/bain froid n'existe pas à Montpellier » et « aucun équivalent local ».** Ajouter Le KREW et Dopa House au tableau B1 et reformuler le créneau : seul le format extérieur, collectif, à la session, avec bar reste introuvable.
2. **Sections B2-3 et F-1 : retirer « uniquement à Paris ».** Citer Coin Nordic (16 € la séance) comme comparable bien plus pertinent que Sant Roch pour un lieu de plein air hors métropole.
3. **Section F-2, prix cible du pass.** Ajouter les repères locaux réels : récupération illimitée incluse dans un abonnement à 109 €/mois (KREW), bain froid + sauna à 15 € (Le Carré), 16 € (Coin Nordic), 50 € l'heure en privatif (Soulëyourt), 63 €/pers. spa + déjeuner (Villa Occitana), 90 €/pers. spa 3 h (Plage Palace).
4. **Section A1, Villa Occitana.** Remplacer « villas dès 165 € / XXL dès 220 € [V] » par « dès 110 € selon l'office de tourisme, à vérifier sur le site officiel ». Remplacer 46 hébergements par 22 à 25. Ajouter les prix Staycation (126 € et 210 € pour 2). Préciser « village de vacances 5* ». Passer la note Booking en « non vérifiée ».
5. **Ligne 8 du tableau B1 : supprimer « Spa Lenido »** (établissement inexistant). Corriger la ligne 6 : les prix cités sont ceux de L'Esprit A.
6. **Ligne 26 et facteur de succès n° 10 : requalifier « 4 500 visiteurs, 85 % d'occupation »** en chiffre déclaré par l'exploitant, à ne pas reprendre dans un prévisionnel.
7. **Repère GWI : remplacer « la moitié » par 44 %**, et préciser l'échantillon (47 répondants, 35 américains, non représentatif).
8. **Section D.** Alpha Camping : corriger le rôle de Maeva. Millésime : date du redressement incertaine (2024 ou 2025). Swansea : refus de permis, pas fermeture. Vert Marine : fermeture temporaire. Nommer La Cour de Honau et en faire le cas d'école (complexe bien-être de 10 000 m², 1,27 M€ de CA, redressement). Retirer « La Cabane » (Romans) et la micro-entreprise de Béziers.
9. **Coucoo : occupation de 75-80 % (pas 85 %)**, 20 cabanes selon les offices de tourisme, prix TripAdvisor 180-250 €. Ajouter le coût de 3 M€ pour 25 cabanes.
10. **Mises à jour 2026 manquantes.** Balnéa : incendie du 1er juillet 2026 et tarifs abaissés. Proposition de loi cabanisation : adoptée par le Sénat le 6 mai 2026. O'balia : réouverture annoncée. Löyly : 25 € (pas 19 €). QC Terme : Wellness Lunch à 42 € (pas 26 €). Caudalie : 340-375 €.
11. **Section D1 :** écrire « 301 € pour les cabanes, 265 € toutes typologies ».
12. **Section A4 :** retirer les trois offres anonymes d'agrégateur ou les nommer.

## 9. Ce qui reste à faire hors de cette session

- **Vérification terrain du créneau** : Instagram et Google Maps sur « sauna », « bain froid », « ice bath », « sauna nomade » à Montpellier, Sète, Palavas, Pic Saint-Loup, Nîmes. C'est le seul moyen de confirmer l'absence de sauna social ou mobile.
- **Appels mystère** : Soulëyourt (accès non-résidents au bain nordique), Le KREW (date d'ouverture, nombre d'adhérents, accès récupération à la séance), Dopa House, Verchant (prix du pass journée et de l'abonnement), Villa Occitana (tarif spa seul).
- **BODACC et Pappers** : exploitant de Villa Occitana, Millésime (date exacte du redressement), Alpha Camping, La Cour de Honau.
- Pour lire les pages sources, les domaines suivants doivent être autorisés dans les réglages réseau de la session : `villaoccitana.com`, `staycation.co`, `bodacc.fr`, `pappers.fr`, `lekrew.fr`, `dopahouse.fr`, `objectifgard.com`.
