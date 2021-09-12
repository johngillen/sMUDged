# sMUDged
simple python mud server

at the moment, the project will be simply text based and operate over telnet. eventually it will handle being able to send simpler data which will be rendered by a special python client user-side.

### server setup
- [] implement simple socket for connection
- [] implement events and codes
- [] implement simple read states
- [] implement version function
- [] implement login function

### database setup
- [] implement sqlite3 database initialization (player folder, dimensions, maps, item database, monster database, etc)
- [] write scripts to populate dimensions, maps, items, monsters, etc

### user account setup
- [] implement quit function
- [] implement password function
- [] implement email recovery

### character setup
- [] initialize race (human, elf, orc, etc)
- [] initialize stats (hp, armor, mana, etc)
- [] initialize class (figher, ranger, etc)
- [] initialize abilities, decks, spells
- [] initialize items and equips

### chat setup
- [] implement mail
- [] implement channels (local, dimension, global)
- [] implement whisper

### gameplay setup
- [] implement moving
- [] implement looking
- [] implement interaction
- [] implement combat (attack, block, cast, dash, dodge, protect)
