# Universe

[![Join our Discord](https://skillicons.dev/icons?i=discord)](https://dsc.gg/bluefront) [![View on GitHub](https://skillicons.dev/icons?i=github)](https://github.com/bluefront-network/universe-proxy)

## What is Universe?

Universe is a web proxy designed to bypass censorship and provide an exceptional user experience.

## Features

- 🚀 **High-Speed Performance**
- 🪞 **Advanced Tab Cloaking**
- 🎮 **Alot of games & apps**
- ℹ️ **URL Paths (lunar://home, lunar://games, ect.)**

## Deployment Options

<div>
    <a href="https://render.com/deploy?repo=https://github.com/bluefront-network/universe-proxy">
        <img src="https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/main/buttons/remade/render.svg" alt="Deploy to Render">
    </a>
    <a href="https://app.koyeb.com/services/deploy?type=git&repository=github.com/bluefront-network/universe-proxy&builder=dockerfile&instance_type=free&regions=was&ports=8080%3Bhttp%3B%2F&hc_protocol%5B808">
        <img src="https://binbashbanana.github.io/deploy-buttons/buttons/remade/koyeb.svg" alt="Deploy to Koyeb" style="float: left; margin-right: 10px;">
    </a>
</div>

> [!NOTE]
> Universe cannot be deployed to Netlify, Vercel, GitHub Pages, or any static hosting platform.

## Deployment via Terminal

> [!NOTE]
> Before deploying, install [git](https://git-scm.com/downloads), [node.js](https://nodejs.org/en/download/prebuilt-installer) and pnpm by running in terminal `npm install -g pnpm` (Before installing pnpm install nodejs).

### Production

1. Clone the Lunar repository:

   ```bash
   git clone https://github.com/bluefront-network/universe-proxy.git
   cd Lunar-v1
   ```

2. Install dependencies and start Lunar:
   ```bash
   pnpm i && pnpm start
   ```

### Development

If you’re making changes to Lunar, use the development setup to avoid rebuilding repeatedly:

```bash
pnpm install && pnpm dev
```

# Contributing

If you are doing a change to Universe, please read [this guide](CONTRIBUTING.md) before commiting.

# Support

For help, make a [GitHub Issue](https://github.com/bluefront-network/universe-proxy/issues) or ask in [our Discord](https://dsc.gg/bluefront).
