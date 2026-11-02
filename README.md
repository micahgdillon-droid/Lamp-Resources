# Lamp Resources

Bibles, commentaries, and dictionaries that [Lamp](https://github.com/micahgdillon-droid) can download from its Resources page.

The files are in the [releases](../../releases). Each one is a SQLite file that Lamp reads; `catalog.json` lists them with their license, credit, size, and SHA-256 checksum, and Lamp checks every download against that checksum before installing it.

## What is here

Every resource is Public Domain, CC0, or CC BY, and each entry in `catalog.json` names its license and its source.

| Resource | Kind | License | Source |
| --- | --- | --- | --- |
| Barnes' Notes on the Bible | Commentary | Public Domain | CrossWire Bible Society |
| Clarke's Commentary | Commentary | Public Domain | CrossWire Bible Society |
| Hitchcock's Bible Names | Dictionary | Public Domain | CrossWire Bible Society, from CCEL |
| Darby Translation | Bible | Public Domain | eBible.org |
| Reina-Valera 1909 | Bible (Spanish) | Public Domain | eBible.org |
| Luther Bible 1912 | Bible (German) | Public Domain | eBible.org |
| Louis Segond 1910 | Bible (French) | Public Domain | eBible.org |

These are conversions of the original texts into Lamp's database format. The words are unchanged; verse references in the commentaries are turned into links.

## Using it

Lamp reads `https://github.com/micahgdillon-droid/Lamp-Resources/releases/latest/download/catalog.json`.
