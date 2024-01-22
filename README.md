# [itch](https://github.com/itchio/itch)

Install, update and play indie games

**NOTICE: This package is not verified by, affiliated with, or supported by itch.io.**

## Notes

Uses wine as a base, to provide support for windows games.

## Development
  - Development tools: `sudo dnf install -y flatpak-builder`
  - Install dependencies: `flatpak install flathub org.winehq.Wine/x86_64/stable-23.08 org.freedesktop.Sdk/x86_64/23.08`
  - Build application: `flatpak-builder build io.itch.Itch.yaml --install --user --force-clean`
  - Run application: `flatpak run io.itch.Itch`

## References
Built off work of [@gjpin](https://github.com/gjpin/itch-flatpak)
Flatpak manifest based on: `https://github.com/flathub/com.fightcade.Fightcade/pull/81`
