## DNS TV 4.4.0 – fini les micro-coupures

| Appareil | Fichier |
|---|---|
| Windows (installateur) | `dns-tv-windows-4.4.0-setup.exe` |
| Windows (portable, sans installation) | `dns-tv-windows-4.4.0-portable.exe` |
| Téléphone et tablette Android | `dns-tv-android-4.4.0.apk` |
| Android TV, Google TV, boîtiers | `dns-tv-tv-4.4.0.apk` |

S'installe par-dessus la version précédente : réglages, sources, favoris et reprises sont conservés (et sauvegardés juste avant).

### Lecture fluide
- **Fini les micro-coupures** apparues avec la 4.2 : le lecteur repris du « zapping instantané » gardait une toute petite réserve pour toutes les chaînes suivantes. Corrigé, avec une vraie réserve au démarrage sur la TV.
- **Mode « réseau difficile » automatique** : si une chaîne coupe 3 fois en 3 minutes, la réserve est agrandie pour la suite.
- **Zapping instantané désactivé par défaut** (2e connexion chez le fournisseur) ; réactivable dans Réglages › Lecture.
- **Windows** : plus de sauts d'image pour « rattraper le direct » (sauf en mode faible latence).
- **TV** : la version proposée d'une chaîne en double respecte votre connexion (« Qualité proposée en premier »).

### Téléphone et tablette
- La chaîne s'affiche en **portrait** si vous tenez l'appareil droit, en **paysage** si vous le tournez (Réglages › Lecture › Orientation du lecteur).

### Finitions et corrections
- Lecteur au repos avec une invitation au lieu d'un écran noir, programme TV plus lisible sur téléphone, bandeau de l'accueil TV qui ne déborde plus, réglages mieux rangés.
- Corrigé : plantage possible de la liste des enregistrements sur téléphone, double lecture depuis le widget ou l'accueil Google TV, film choisi depuis la recherche de la TV.
