# Overlay d'Avamind pour "Commu ZEvent/Place"

## Instructions

- Installez Tampermonkey :
  - Chrome : https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo
  - Firefox : https://addons.mozilla.org/fr/firefox/addon/tampermonkey/
  - Opera : https://addons.opera.com/fr/extensions/details/tampermonkey-beta/

- Installez le script du [Discord "Commu ZEvent/Place"](https://discord.gg/sXe5aVW2jV) via ce lien : https://raw.githubusercontent.com/ludolpif/overlay-zevent-place/main/browser-script/zevent-place-overlay.user.js
  - Le script en version de test se trouve [ici](https://raw.githubusercontent.com/ludolpif/overlay-zevent-place/develop/browser-script/zevent-place-overlay.user.js)

- Allez sur le site https://place.zevent.fr
  - Dans le menu "Overlays" à gauche, ajoutez "Avamind"
  - Placez vos pixels !

- L'artwork `avamindLove` se situe entre `(330,239)` et `(358,270)` (686 pixels à colorier)

- Vous pouvez faire en sorte que l'overlay se mette directement, en ajoutant dans le script la ligne suivante (attention, faudra la remettre si mise à jour du script)

```js
loadOverlay("https://github.com/bunlan-g/zevent-place-avamind/raw/master/avamind-overlay.png", "Avamind" );
```

## Crédits

- *Version pixelisée de l'emote `avamindLove` par Givr_*
