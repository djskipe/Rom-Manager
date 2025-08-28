# ROM Manager - Advanced ROM Collection Cataloger / Catalogatore Avanzato per Collezioni ROM

[🇬🇧 English](#english) | [🇮🇹 Italiano](#italiano)

---

## English

A powerful web-based tool for cataloging and managing your retro gaming ROM collection. Completely offline, no server required!

### Features

**Smart Console Detection**
- Advanced detection system based on 100+ file extensions
- Confidence algorithm analyzing extensions, filenames, and folder paths
- Support for 50+ consoles from NES to PlayStation 4, Xbox One, Nintendo Switch and vintage systems
- Intelligent ambiguous extension handling (.iso, .bin, .chd, etc.)

**Metadata Management**
- GiantBomb API integration for automatic metadata
- Manual search with user-friendly interface
- Automatic cover art download during search
- Visual indicators for ROMs with/without metadata
- CORS proxy system to bypass browser limitations

**ROM Management**
- Multiple selection with checkboxes for bulk operations
- Individual or group console editing
- Download renamed ROMs with clean names
- Automatic name cleaning removes regional tags, versions, duplicates
- File System Access API support for direct disk saving

**Export & Sharing**
- JSON/CSV export of cataloged collection
- Generate collection.html for elegant web visualization
- Individual metadata saving for backup

### How to Use

1. **Open HTML file** in Chrome, Edge, Opera or Brave (required for folder access)
2. **Select ROM folder** with "Choose ROM folder" button
3. **Filter extensions** (optional): enter space-separated extensions (e.g., `.nes .gba .iso`)
4. **Scan** folder - system will automatically detect consoles
5. **Search metadata** using GiantBomb API or manual search
6. **Manage collection** with multiple selections and console modifications
7. **Export results** in various formats

### Supported Consoles

**Nintendo**: NES, SNES, N64, GameCube, Wii, Wii U, Switch, Game Boy/Color/Advance, DS, 3DS  
**Sony**: PlayStation 1-4, PSP, PS Vita  
**Microsoft**: Xbox, Xbox 360, Xbox One  
**Sega**: Master System, Genesis/Mega Drive, Game Gear, Saturn, Dreamcast, Sega CD  
**Atari**: 2600, 5200, 7800, Lynx, Jaguar  
**Others**: TurboGrafx-16, 3DO, Neo Geo, Arcade (MAME), Commodore 64, Amiga, MSX, and many more

### Browser Compatibility

- ✅ **Chrome** (recommended)
- ✅ **Microsoft Edge** 
- ✅ **Opera**
- ✅ **Brave**
- ❌ Firefox/Safari (folder API limitations)

### Technical Features

- **Completely offline** - no server or installation required
- **Advanced name cleaning algorithms** removing standard ROM tags
- **Multiple CORS proxy system** for reliable API access
- **Responsive interface** optimized for desktop and mobile
- **Robust error handling** with automatic fallbacks
- **Session state saving** of collection during use

---

## Italiano

## ✨ Caratteristiche Principali

## Italiano

Un potente strumento web-based per catalogare e gestire la tua collezione di ROM retro gaming. Completamente offline, nessun server richiesto!

### Caratteristiche Principali

**Rilevamento Console Intelligente**
- Sistema di rilevamento avanzato basato su oltre 100+ estensioni di file
- Algoritmo di confidenza che analizza estensioni, nomi file e percorsi delle cartelle
- Supporto per 50+ console da NES a PlayStation 4, Xbox One, Nintendo Switch e sistemi vintage
- Gestione estensioni ambigue con priorità intelligente (.iso, .bin, .chd, ecc.)

**Gestione Metadati**
- Integrazione API GiantBomb per metadati automatici
- Ricerca manuale con interfaccia user-friendly
- Download automatico copertine durante la ricerca
- Indicatori visivi per ROM con/senza metadati
- Sistema proxy CORS per aggirare limitazioni browser

**Gestione ROM**
- Selezione multipla con checkbox per operazioni di massa
- Modifica console individuale o di gruppo
- Download ROM rinominate con nomi puliti
- Pulizia automatica nomi rimuove tag regionali, versioni, duplicati
- Supporto File System Access API per salvare direttamente su disco

**Export e Condivisione**
- Export JSON/CSV della collezione catalogata
- Generazione collection.html per visualizzazione web elegante
- Salvataggio metadati individuali per backup

### Come Usare

1. **Apri il file HTML** in Chrome, Edge, Opera o Brave (richiesto per accesso cartelle)
2. **Seleziona cartella ROM** con il pulsante "Scegli cartella ROM"
3. **Filtra estensioni** (opzionale): inserisci estensioni separate da spazio (es: `.nes .gba .iso`)
4. **Scansiona** la cartella - il sistema rileverà automaticamente le console
5. **Ricerca metadati** usando l'API GiantBomb o ricerca manuale
6. **Gestisci collezione** con selezioni multiple e modifiche console
7. **Esporta risultati** in vari formati

### Console Supportate

**Nintendo**: NES, SNES, N64, GameCube, Wii, Wii U, Switch, Game Boy/Color/Advance, DS, 3DS  
**Sony**: PlayStation 1-4, PSP, PS Vita  
**Microsoft**: Xbox, Xbox 360, Xbox One  
**Sega**: Master System, Genesis/Mega Drive, Game Gear, Saturn, Dreamcast, Sega CD  
**Atari**: 2600, 5200, 7800, Lynx, Jaguar  
**Altri**: TurboGrafx-16, 3DO, Neo Geo, Arcade (MAME), Commodore 64, Amiga, MSX, e molti altri

### Compatibilità Browser

- ✅ **Chrome** (raccomandato)
- ✅ **Microsoft Edge** 
- ✅ **Opera**
- ✅ **Brave**
- ❌ Firefox/Safari (limitazioni API cartelle)

### Funzionalità Tecniche

- **Completamente offline** - nessun server o installazione richiesta
- **Algoritmi di pulizia nomi** avanzati che rimuovono tag ROM standard
- **Sistema proxy CORS multiplo** per accesso API affidabile
- **Interfaccia responsive** ottimizzata per desktop e mobile
- **Gestione errori robusta** con fallback automatici
- **Salvataggio stato** della collezione durante la sessione

---

## API Requirements / Requisiti API

For automatic metadata features / Per le funzionalità di metadati automatici:
- **GiantBomb API Key** (demo key included / chiave demo inclusa)
- Internet connection for metadata/cover downloads / Connessione internet per download metadati/copertine

## File Structure Support / Struttura File Supportata

The tool works with any folder structure / Il tool funziona con qualsiasi struttura di cartelle:
```
ROMs/
├── Nintendo/
│   ├── NES/
│   └── SNES/
├── Sony/
│   ├── PS1/
│   └── PS2/
└── Mixed/
```

## Technologies / Tecnologie

- **HTML5** + **CSS3** + **Vanilla JavaScript**
- **File System Access API** for folder management / per gestione cartelle
- **Fetch API** with CORS proxy system / con sistema proxy CORS
- **CSS Grid/Flexbox** for responsive layout / per layout responsive

## Contributing / Contribuire

This is an open source project. Contributions welcome for:
Questo è un progetto open source. Contributi benvenuti per:
- Adding new consoles/extensions / Aggiunta nuove console/estensioni
- Improving detection algorithms / Miglioramenti algoritmi rilevamento
- Interface optimizations / Ottimizzazioni interfaccia
- Bug fixes / Correzioni bug


## Credits / Crediti

- **Console data / Dati console**: emulation.gametechwiki.com
- **Game metadata / Metadati giochi**: GiantBomb API

---


