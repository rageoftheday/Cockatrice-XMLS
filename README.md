on updater change first link to:

https://raw.githubusercontent.com/rageoftheday/Cockatrice-XMLS/refs/heads/main/mtg.xml

token link: 

https://raw.githubusercontent.com/rageoftheday/Cockatrice-XMLS/refs/heads/main/tokens.xml.xz


=====================================================================================================
Cockatrice Universal Deck Importer 5.0 R2–R11

Improved 8–16 GB RAM performance and card database caching
Added performance/crash diagnostics
Fixed Card Database Browser layout/modeless behavior
Added Scryfall search help and keyword/syntax searching
Hardened image loading and removed unstable hover previews
Added double-click deck rows to open art/printing selector
Unified Scryfall image downloading with timeouts and safer disposal
Improved selected printing/set/collector/UUID handling
Added real-time crash recovery after deck changes
Added atomic recovery temp files
Fixed recovery restore so Cockatrice cards.xml loads before validation
Multiple stability/crash fixes around Choose Art, browser previews, and WinForms events

==================================================================================================

Cockatrice Deck Importer Updater v1 

A Windows PowerShell tool that imports and updates Cockatrice .cod deck files directly from Moxfield and Archidekt.
It supports creating new linked decks, linking existing .cod files, updating one or all linked decks, automatic backups, multiple Cockatrice deck folders, and portable or installed Cockatrice setups.
It also cleans imported card names using Cockatrice and Scryfall data, including flavor-name fixes, safe Front // Back handling, punctuation/case normalization, and unknown-card reporting.
Deck zones are mapped automatically:
Mainboard → Main
Commander → Sideboard
Companion → Sideboard
Sideboard → Sideboard
Maybeboard / Considering → Optional prompt
