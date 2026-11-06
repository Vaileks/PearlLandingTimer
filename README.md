<div align="center">

# Pearl Landing Timer

**Practice pearl throws with precise tick-based timing.**

`FABRIC` · `MINECRAFT 1.21.11` · `CLIENT-SIDE`

[Download](https://github.com/Vaileks/PearlLandingTimer/releases/latest) · [Report an issue](https://github.com/Vaileks/PearlLandingTimer/issues)

</div>

---

Pearl Landing Timer is a client-side Fabric mod by **Vaileks**.

## Features

- Measures your own pearl flights on the integrated single-player server.
- Shows collision time in ticks and seconds.
- Keeps a session history of up to 50 throws.

## Installation

1. Use **Minecraft Java 1.21.11**, **Fabric Loader 0.19.2+** and **Java 21+**.
2. Download `pearl-landing-timer-1.0.0+1.21.11.jar` from [Releases](https://github.com/Vaileks/PearlLandingTimer/releases/latest).
3. Put the JAR in your client `mods` folder and start the game.

No server installation or Fabric API is required. The shared runtime is already bundled in the JAR, so this mod can be installed on its own or alongside other mods in the series.

## Configuration

Press **F8** or use the mod's settings button in **Mod Menu**. Mod Menu is optional.

Adjust the available colors, thresholds and feature controls in the settings screen. HUD panels support scale, shadow, background, item names or icons, and mouse placement where applicable. Save changes with **Done / Готово**. The action key is unbound by default to avoid conflicts; assign one in **Functions / Функции**.

Settings are stored in `config/pearl_landing_timer.json`.

## Compatibility notes

Single-player only. Seconds are calculated from server ticks at 20 ticks per second, so they are gameplay time rather than wall-clock time during lag.

## Русский

Pearl Landing Timer измеряет полёт вашего жемчуга до столкновения в одиночном мире. Показывает тики и секунды, хранит историю до 50 бросков за сессию.

Установка: Fabric **1.21.11**, Java **21+**. Поместите JAR в клиентскую папку `mods`. Настройки — **F8** или Mod Menu. Fabric API не требуется.

## Build

With JDK 21–25 and Python 3 installed:

```sh
./gradlew packageMods
```

Output: `dist/mods/pearl-landing-timer-1.0.0+1.21.11.jar`.

## License

[MIT](LICENSE).
