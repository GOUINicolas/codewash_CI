# Level Up RPG (CodeWash)

A Minecraft-themed educational RPG built with React, Vite and Electron.

## Dependencies

- [Node.js](https://nodejs.org) 20.19 or newer (includes npm)
- Git
- Chrome, Edge or Chromium (needed for the microphone feature)

Check what you already have:

```bash
node -v
npm -v
git --version
```

### Install Node.js

**Windows** (PowerShell):

```powershell
winget install OpenJS.NodeJS.LTS
```

**macOS** (Homebrew):

```bash
brew install node
```

**Linux** (via [nvm](https://github.com/nvm-sh/nvm)):

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.1/install.sh | bash
# close and reopen your terminal, then:
nvm install 22
nvm use 22
```

Close and reopen your terminal afterwards, then check `node -v` again.

### Install Git

| OS | Command |
|---|---|
| Windows | `winget install Git.Git` |
| macOS | `brew install git` |
| Debian / Ubuntu | `sudo apt install git` |

### Install a browser

Download [Chrome](https://www.google.com/chrome/) or
[Chromium](https://www.chromium.org/getting-involved/download-chromium/).
Firefox does not support the speech recognition used by the Reading skill.

## Install

Run from the folder that contains `package.json`:

```bash
npm ci
```

## Run

```bash
npm run dev
```

Then open the address shown in the terminal (usually http://localhost:5173).

## Commands

| Command | Description |
|---|---|
| `npm ci` | Install dependencies |
| `npm run dev` | Start the game in the browser |
| `npm run build` | Build the web app into `dist/` |
| `npm run preview` | Preview the production build |
| `npm run lint` | Run ESLint |
| `npm run electron:dev` | Run the desktop version |
| `npm run electron:build` | Build the Windows `.exe` into `release/` |

## Documentation

See [`docs/DEBT.md`](docs/DEBT.md) for the technical debt register.
