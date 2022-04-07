---
theme: default
_class: lead
paginate: true
backgroundColor: #fff
marp: true
backgroundImage: url('https://marp.app/assets/hero-background.svg')
---

![bg left:35% 100%](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fc.pxhere.com%2Fphotos%2F22%2Fd3%2Fhiking_shoes_hike_men_shoes_sport-612718.jpg!d&f=1&nofb=1)

# **Hiking with OSM**

## How to use and contribute to hiking data with OpentStreetMap


About this presentation:
👨‍💻 [User:grosjen](https://wiki.openstreetmap.org/wiki/User:grosjen)
👨‍💻 [User:Binnette](https://wiki.openstreetmap.org/wiki/User:Binnette)
📅 2022-04-11
🟢 License MIT

---

# PLAN

# **1️⃣ Intro**

# **2️⃣ Use OSM**

# **3️⃣ Contribute to OSM**

---

# **1️⃣ Intro**

---

# 🥾 Node networks

In Isère the routes are described according a Node Network (Réseau de Carrefours en français), it is not the case everywhere.

---

![bg fit](https://raw.githubusercontent.com/NicolasGrosjean/OSM_hiking_prez_2022/main/images/Guidepost.jpg)

---

# **2️⃣ Use OSM**

---

# 💻 WaymarkedTrails - global view

[WaymarkedTrails](https://hiking.waymarkedtrails.org/#?map=13.0/45.1853/5.7595) displays the data for some thems like hikings.

---

![bg fit](https://raw.githubusercontent.com/NicolasGrosjean/OSM_hiking_prez_2022/main/images/WaymarkedTrails_Grenoble.jpg)

---

# 💻 WaymarkedTrails - hiking legend


The hikings routes are rendered according their types

- Red : Node networks
- Purple : Itinerary
- Blue bold : European route
- Red bold : Other major route (Ex: Saint-Jacques de Compostelle routes)
- Orange bold : Round Trip (EX: Grand Tour du Vercors)

---

# 💻 WaymarkedTrails - data

We can click on a route to inspect the OSM object.

---

![bg fit](https://raw.githubusercontent.com/NicolasGrosjean/OSM_hiking_prez_2022/main/images/WaymarkedTrails_Guidepost.jpg)

![bg fit](https://raw.githubusercontent.com/NicolasGrosjean/OSM_hiking_prez_2022/main/images/WaymarkedTrails_Route.jpg)

---

# 💻 Brouter

[Brouter](https://brouter.de/brouter-web/#map=13/45.1802/5.7512/OpenTopoMap,Waymarked_Trails-Hiking&profile=hiking-beta) allow to plan trip for several mean of transport.

It has a hinking beta mode and uses the WaymarkedTrails layer among others.

⚠ Computation are done on all the paths, not only the hiking paths.

We can export the GPX track.

---

![bg fit](https://raw.githubusercontent.com/NicolasGrosjean/OSM_hiking_prez_2022/main/images/Brouter.jpg)


---

# 💻 GraphHopper

[GraphHopper](https://graphhopper.com/maps/?point=&point=&locale=fr&elevation=true&profile=foot&use_miles=false&layer=Omniscale) allow to plan trip for several mean of transport.

It doesn't use WaymarkedTrails layer but Thunderforest Outdoors where we see the hiking routes.

⚠ Computation are done on all the paths, not only the hiking paths.

We can export the GPX track.

---

![bg fit](https://raw.githubusercontent.com/NicolasGrosjean/OSM_hiking_prez_2022/main/images/GraphHopper.jpg)

---

# 📱 OsmAnd

Download map to see them offline
(with no download limit with OpenSource version downlable with FDroid).

You can set several profile, and so dedicate one for hiking.

---

# 📱 OsmAnd - WaymarkedTrails

We can add WaymarkedTrails in the overlayer of a map with the Topo style.

![bg right fit](https://raw.githubusercontent.com/NicolasGrosjean/OSM_hiking_prez_2022/main/images/OsmAndWaymarkedTrails.jpg)

---

# 📱 OsmAnd - Hinking Style

A contributor on the OSM Plein Air Telegram shared a [hike style](https://github.com/Hades1503/OsmAnd_Hiking_Map).

It uses the tags _trail_visibility_ and _sac_scale_.

![bg right fit](https://raw.githubusercontent.com/NicolasGrosjean/OSM_hiking_prez_2022/main/images/OsmAndHikingStyle.jpg)

---

# 📱 OsmAnd - Load GPX track

We can load the GPX track we have generated with Brouter, GraphHopper, ...
or found on the internet.

Simply put the file on your smartphone and open it with OsmAnd.

You can change the track color in the map settings.

---

# **3️⃣ Contribute to OSM**

---

# 📷 Photos

You can take geolocalised photos of guideposts and upload them to some websites.

- Wikimedia Commons : a cetegory by department, [for example for Isère's guideposts](https://commons.wikimedia.org/wiki/Category:Hiking_and_footpath_fingerposts_in_Is%C3%A8re?uselang=fr)
- [Mapillary](https://www.mapillary.com/)

---

# 💻 JOSM

[Noob friendly guide](https://wiki.openstreetmap.org/wiki/Guide_pour_cartographier_des_chemins_de_randonn%C3%A9es)

Several concepts :

- Guidepost
- Node of the network
- Route between nodes
- Network (a Community of Municipalities + an activity = a network)

Work in progress on the way to map and on the mapping completion in France.

---

# 💻 OpenData in Isère

- [Metro](https://data.metropolegrenoble.fr/ckan/dataset/espnat_sentier_chemins_metro)
- [Department](https://opendata.isere.fr/explore/dataset/plan-departemental-des-itineraires-de-promenades-et-de-randonnees-departement-de/information/)

---

# 💠 Appendix

* [Groupe Telegram Plein Air](https://t.me/osmpleinair)
* [Tutoriel d'installation d'OSMAnd et de traces GPX](https://github.com/Binnette/GAC/tree/main/TutoOsmAnd)
* [OsmAnd hike style](https://github.com/Hades1503/OsmAnd_Hiking_Map)
* On OSM wiki:
  * [Projet Plein Air](https://wiki.openstreetmap.org/wiki/FR:Projet_Plein_Air)
  * [Réseaux de carrefours](https://wiki.openstreetmap.org/wiki/FR:R%C3%A9seaux_de_carrefours)
  * [Randonnée pédestre](https://wiki.openstreetmap.org/wiki/FR:Randonn%C3%A9e_p%C3%A9destre)
  * [OsmAnd](https://wiki.openstreetmap.org/wiki/FR:OsmAnd)

---

# 💡 Any question ?

* Feel free to contact us by private message:
  * On OSM:
    * https://www.osm.org/user/NicolasGrosjean
    * https://www.osm.org/user/Binnette
  * On the Wiki:
    * https://wiki.openstreetmap.org/wiki/User:grosjen
    * https://wiki.openstreetmap.org/wiki/User:Binnette
