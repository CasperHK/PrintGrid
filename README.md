# PrintGrid

> A high-performance, modern JavaScript/TypeScript library built with [Rslib](https://github.com/web-infra-dev/rslib) for managing and generating printable paper layouts and documents.

---

## 🚀 Features

* **⚡ Blazing Fast Build**: Powered by Rspack and Rsbuild for ultra-fast compilation.
* **📦 Multiple Formats**: Out-of-the-box support for both **ESM** and **CJS** output formats.
* **📐 TypeScript Ready**: Automatic generation and bundling of `.d.ts` declaration files.
* **🛠️ Flexible Output**: Supports both bundled and bundleless distribution modes.

---

## 📦 Installation

```bash
# Using npm
npm install paper-pulse

# Using pnpm
pnpm add paper-pulse

# Using yarn
yarn add paper-pulse

```

---

## 💡 Usage

### ES Modules (ESM)

```javascript
import { createPrintLayout } from 'paper-pulse';

createPrintLayout();

```

### CommonJS (CJS)

```javascript
const { createPrintLayout } = require('paper-pulse');

createPrintLayout();

```

---

## 🛠️ Development

If you want to contribute or develop locally, follow these steps:

### 1. Clone the repository

```bash
git clone https://github.com/your-username/paper-pulse.git
cd paper-pulse

```

### 2. Install dependencies

```bash
pnpm install

```

### 3. Start development mode

Run the build tool in watch mode to automatically recompile on changes:

```bash
pnpm dev

```

### 4. Build for production

Generate distribution files and TypeScript declarations:

```bash
pnpm build

```

---

## 📁 Project Structure

```text
paper-pulse/
├── src/
│   ├── index.ts      # Entry point
│   └── ...           # Source files
├── dist/             # Generated output (ESM, CJS, types)
├── rslib.config.ts   # Rslib configuration
├── package.json      # Dependencies & scripts
└── README.md

```

---

## 📜 License

[MIT](https://www.google.com/search?q=LICENSE) © Your Name
