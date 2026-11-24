# Pictures for the Era Lost Legend app

Put each picture in the folder for its section, then set the path in that entry's JSON field.

| Folder | JSON file | Fields |
|---|---|---|
| `images/characters/` | `Characters.JSON` | `image`, `specialImage`, `extraImage` |
| `images/locations/` | `Locations.json` | `image` |
| `images/beasts/` | `Beasts.json` | `image` |
| `images/items/` | `Items.json` | `image` |

Example: upload `images/characters/lumi.jpg`, then in Characters.JSON set `"image": "images/characters/lumi.jpg"`.

- PNG or JPG, ideally around 1024 px and a few hundred KB.
- Paths are case-sensitive: `Lumi.jpg` and `lumi.jpg` are different files.
- The app downloads each picture once and keeps it. To change a picture, upload it under a new name (e.g. `lumi_2.jpg`) and update the path.
- An empty `image` keeps the picture built into the app.
