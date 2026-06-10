# 🦴 Wuff & Knusper – Die Hundebäckerei

Ein gemütliches Idle-/Clicker-Game im Browser: Baue deine eigene Hundekeks-Bäckerei auf –
vom Küchentisch bis zum galaktischen Keks-Imperium. 🐶

**▶️ Jetzt spielen:** https://psaxde.github.io/dog-bakery-idle-game/

## Features

- 🍪 **Klicken & Backen** – mit Squish-Animation, Krümel-Partikeln und Sound
- 🏠 **8 Ausbau-Stufen** – vom Welpen-Praktikanten bis zur Keks-Rakete
- ✨ **10 Verbesserungen** – Klick-Power, Gebäude-Boosts & globale Multiplikatoren
- 🌟 **Goldene Knochen** – zufällige Events mit Wuff-Rausch (×7), Keks-Regen & Klick-Rausch (×10)
- 🏆 **15 Erfolge** – jeder Erfolg gibt dauerhaft +1 % Produktion
- ⭐ **Prestige-System** – Bäckerei verkaufen für Sterne-Rezepte (+10 % für immer pro Stern)
- 💤 **Offline-Fortschritt** – bis zu 8 Stunden Produktion, während du weg bist
- 💾 **Auto-Save** im localStorage, kein Account nötig

## Entwicklung

Eine einzige Datei, kein Build-Schritt:

```bash
python3 -m http.server 8423
# → http://localhost:8423
```

Oder einfach `index.html` direkt im Browser öffnen.

## Deployment

Jeder Push auf `main` deployt automatisch via GitHub Actions auf GitHub Pages
(siehe [.github/workflows/deploy-pages.yml](.github/workflows/deploy-pages.yml)).
