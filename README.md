# Stremio Stack en auto-hébergement

Stack personnelle **Stremio** en auto-hébergement, pour du FRENCH/MULTi en sources BitTorrent/caches de débrideurs + bonus IPTV.  
Certains développeurs ne publient pas d'image Docker, j'ai cloné leurs dépôts et fait des images (multi-architectures).  
Tout est donc compatible amd64/arm64.  


Les fichiers `.yml` sont considérés comme immuables :  
- Ils utilisent les **sources directes des outils** depuis GitHub,
- Les mises à jour sont **automatisées** via WatchTower.


## Prérequis

- Un minimum de connaissances des environnements Linux (ou d'apprentissage),
- Un NAS ou un.e VM/CT/LXC/VPS/serveur/PC/NUC sous Linux/macOS/Windows(?) embarquant Docker à jour,
- Un nom de domaine gratuit ou payant supportant la création de sous-domaines,
- Un reverse proxy tel que [NPM](https://github.com/NginxProxyManager/nginx-proxy-manager),
- Des clés API pour les services connexes : TMDB, TVDB, MDBList, FanArt etc.


## Article de blog lié
[Stremio : ma stack du moment (auto-hébergée) et liste d'addons VoD/IPTV](https://upandclear.org/2025/11/10/stremio-ma-stack-du-moment-auto-hebergee-et-liste-daddons-vod-iptv/)  
Des **visuels** pour chaque addon sont disponibles dans les dossiers.


## Configuration 

- Il suffit de remplacer les xxx avec vos **clés API** ainsi qu'adapter **ports**, **domaines/sous-domaines** et **chemins de montage**,
- Vous pouvez également modifier les divers mots de passe arbitraires utilisés en exemples.

