# Squad Layers

This repository contains a list of all current [Squad](https://joinsquad.com/) layers. It is manually managed by members of the [We ♥️ Squad](https://welovesquad.com/) community and will be updated as close to new version releases as possible. It is used internally to generate map rotations.

## Data

**Data for Squad Version: *v4***

You can find the data export [here](./squad-layers.json).

**Example**
```json
[
    ...
    {
        "id": "Yehorivka_RAAS_v01",
        "level": "Yehorivka",
        "gamemode": "RAAS",
        "teamOne": "USMC",
        "teamTwo": "RUS"
    },
    ...
]
```

### ID
A valid Squad layer ID that can be used via RCon to switch layers.

### Level
A level ID as logged by the Squad dedicated server.

One of:
- `Al Basrah`
- `Anvil`
- `Belaya Pass`
- `Black Coast`
- `Chora`
- `Fallujah`
- `Fool's Road`
- `Goose Bay`
- `Gorodok`
- `Harju`
- `Jensen's Range`
- `Kamdesh Highlands`
- `Kohat Toi`
- `Kokan`
- `Lashkar Valley`
- `Logar Valley`
- `Manic-5`
- `Mestia`
- `Mutaha`
- `Narva`
- `Pacific Proving Grounds`
- `Skorpo`
- `Sumari Bala`
- `Tallil Outskirts`
- `Training`
- `Yehorivka`

### Gamemode
One of:
- `AAS`
- `Insurgency`
- `Invasion`
- `RAAS`
- `Seed`
- `Skirmish`
- `Track Attack`
- `Territory Control`
- `Destruction`
- `Training`

### Teams / Fractions
Fraction IDs as logged by the Squad dedicated server.

One of:
- `AUS`
- `CAF`
- `GB`
- `INS`
- `PLA`
- `MEA`
- `MIL`
- `RUS`
- `US`
- `USMC`

## Data Extraction Projects
- https://github.com/Squad-Wiki-Editorial/squad-wiki-pipeline-map-data
- https://github.com/w4rum/squadlanes
