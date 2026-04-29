# Altered non-unique cards export

This repository contains all the cards data of non-unique cards of the Altered TCG.

Data and assets are available in en_US, fr_FR, es_ES; de_DE and it_IT locales.

**TODO** : Add link to unique exports repositories.

## JSON data

JSON exports are available in the `json` directory.

Structure is the following:

```
json/
  <SET>/
    <CARD_FAMILY>/
      ALT_<SET>_<CARD_PRODUCT>_<FACTION>_<SLOT>_<RARITY>.json
```

## Assets

JPG exports are available in the `assets` directory.

Structure is the following:

```
assets/
  <SET>/
    CARDS/
      <CARD_ID>/
        JPG/
          <LANGUAGE>/
            <hash>.jpg
```
