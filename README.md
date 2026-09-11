<div align="center">

# Aricord

**The other cutest Discord client mod — now with extra Ari.**

Aricord is a fork of [Illegalcord](https://github.com/ImHisako/Illegalcord) (which is a fork of [Equicord](https://github.com/Equicord/Equicord), which is a fork of [Vencord](https://github.com/Vendicated/Vencord)) — bundling the best plugins from the whole family tree, plus its own.

[![GPL-3.0 License](https://img.shields.io/badge/License-GPL--3.0-blue.svg)](LICENSE)

</div>

## Features

- **150+ bundled plugins** — from Vencord, Equicord, Illegalcord and Aricord, all toggleable in settings
- **Client-side custom CSS** — theming without limits
- **In-app updater** — gets fixes the moment they land on `main`
- **Works everywhere** — Discord desktop, Vesktop, Equibop, and as a browser extension / userscript

## Installing (from source)

```bash
git clone https://github.com/AriOfTabor/Aricord
cd Aricord

# Install dependencies
pnpm install

# Build the client
pnpm build

# Inject into your local Discord client
pnpm inject
```

To remove it: `pnpm uninject`.

For the browser, load the built extension from `dist/` or use the userscript build.

## Plugin directory layers

| Layer | Origin |
|---|---|
| `src/plugins` | Vencord plugins (upstream) |
| `src/equicordplugins` | Equicord plugins |
| `src/aricordplugins` | Illegalcord + Aricord plugins |
| `src/userplugins` | Your own local plugins |

## Contributing

All plugin layers accept contributions. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines — the same rules apply, just with better taste.

## Credits & License

- **[Vendicated](https://github.com/Vendicated)** and all Vencord contributors — the foundation
- **[Equicord](https://github.com/Equicord/Equicord)** — the Equicord plugin layer
- **[ImHisako](https://github.com/ImHisako)** — Illegalcord and its plugin layer

Licensed under **GPL-3.0-or-later** — see [LICENSE](LICENSE). Aricord is not affiliated with Discord or Valve.
