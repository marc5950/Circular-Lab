# Circular Lab - KEA Website

Dette repository indeholder kildekoden til Circular Lab's website for Københavns Erhvervsakademi (KEA). Hjemmesiden er bygget med Astro og inkluderer information om Circular Lab, deres events, tilbud og praktisk information.

## Funktioner

- Responsivt design til både mobil og desktop
- Dynamisk events-kalender med filtrering mellem nyeste og kommende events
- Dropdown-menuer for forskellige informationssektioner
- Integration med Supabase som backend for events data
- Event-detaljesider med dynamisk indholdsvisning

## Teknologier

- [Astro](https://astro.build/) - Web framework
- [Supabase](https://supabase.com/) - Database og API
- Vanilla JavaScript
- CSS

## Projektstruktur

- `src/components/` - Genbrugelige UI komponenter
- `src/layouts/` - Side layouts
- `src/pages/` - Forskellige sider og routes
- `src/assets/` - Billeder og andre statiske filer
- `src/styles/` - CSS styles

## Installation og kørsel

1. Klon dette repository:

```bash
git clone [repository-url]
```

2. Installer afhængigheder:

```bash
npm install
```

3. Start udviklingsserveren:

```bash
npm run dev
```

4. Byg til produktion:

```bash
npm run build
```

## Features

### Event Filtrering

Hjemmesiden inkluderer en event-filtreringsfunktion, der giver brugerne mulighed for at skifte mellem at se de nyeste events eller kommende events. Implementeringen bruger to separate lister, der vises/skjules baseret på brugerinteraktion.

### Dropdown-menuer

Siden bruger interaktive dropdown-menuer til at organisere information om Circular Lab's tilbud og services. Dette giver en mere overskuelig præsentation af indhold.

### Responsivt design

Hjemmesiden er fuldt responsiv og tilpasser sig forskellige skærmstørrelser, fra mobil til desktop.

## Credits

Udviklet af Gruppe 9 for KEA Circular Lab
