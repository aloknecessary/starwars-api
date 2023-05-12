# starwars-api

StarWars characters REST API

### base url

`https://aloknecessary.github.io/starwars-api/api`

### [routes](#routes-1)

- [`/all.json`](#alljson)
- [`/id`](#id)

---

## Routes

##### `/all.json`

GET all characters as a single JSON object

eg. [`/all.json`](https://aloknecessary.github.io/starwars-api/api/all.json)

##### `/id`

GET character complete informations by id

eg. [`/id/1.json`](https://aloknecessary.github.io/starwars-api/api/id/1.json)

```json
{
  "id": 1,
  "name": "Luke Skywalker",
  "height": 1.72,
  "mass": 73,
  "gender": "male",
  "homeworld": "tatooine",
  "wiki": "http://starwars.wikia.com/wiki/Luke_Skywalker",
  "image": "https://vignette.wikia.nocookie.net/starwars/images/2/20/LukeTLJ.jpg",
  "born": -19,
  "bornLocation": "polis massa",
  "died": 34,
  "diedLocation": "ahch-to",
  "species": "human",
  "hairColor": "blond",
  "eyeColor": "blue",
  "skinColor": "light",
  "cybernetics": "Prosthetic right hand",
  "affiliations": [
    "Alliance to Restore the Republic",
    "Red Squadron",
    "Rogue Squadron",
    "Massassi Group",
    "Leia Organa's team",
    "Endor strike team",
    "Jedi Order",
    "Bright Tree tribe",
    "New Republic",
    "Resistance"
  ],
  "masters": ["Obi-Wan Kenobi", "Yoda"],
  "apprentices": [
    "Leia Organa",
    "Ben Solo (along with a dozen apprentices)",
    "Rey"
  ],
  "formerAffiliations": []
}
```
