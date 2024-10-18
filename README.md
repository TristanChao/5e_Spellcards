# D&D SpellCards

D&D SpellCards is a frontend web application designed as a gameplay tool for D&D players. It fetches data from the D&D 5e SRD API and displays it alongside custom visuals. Users can browse a list of spells, click on individual spells for more details, and add spells to a personal collection that is saved in local storage.

## Technologies

- HTML
- CSS
- TypeScript

## Using the App

### Spell List

Immediately upon entering the site, users have access to all 5th Edition D&D spells provided by the API. Each spell is rendered on its own card with its spell level and a spell circle visual in a random color. Spells can be searched, sorted by name/level, and filtered by name, level, and school of magic.

![sort, search, filter feature](https://github.com/user-attachments/assets/21a5ae9a-5aff-4732-9dac-c7e9fa7777d1)

### Spell Details

Clicking on a spell card will display the details of the spell on a new page.

![spell details feature](https://github.com/user-attachments/assets/eb6caba3-ddda-48ec-b05f-6702b8448acb)

### Spellbooks

Users can create a personal collection of spells (referred to as a spellbook) that will let them save spells of their choosing for easy reference. During spellbook creation, certain character classes that have default access to all spells for their class will have to option to prefill the spellbook with all available spells for their level.

![new spellbook feature](https://github.com/user-attachments/assets/651181b4-db93-4446-97dc-b0f2490eb552)

### Spellbook Management

Spells can easily be added and removed from spellbooks through the spell management mode, where a single click will toggle a spell's inclusion in the collection. Spell details can also be viewed while managing spells, so there's no need to switch in and out of management mode if you can't remember what a spell does.

![spellbook management feature](https://github.com/user-attachments/assets/d245cc68-0bb6-4c5f-8d7f-7f08a99289ab)
