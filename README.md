# Playwright Testing Project

A TypeScript-based automation testing project using Playwright.

## Setup

### Prerequisites
- Node.js (v16 or higher)
- npm

### Installation

1. Clone the repository
```bash
git clone https://github.com/mayurpolewar/playwrightmayur.git
cd playwrightmayur
```

2. Install dependencies
```bash
npm install
```

3. Install browsers
```bash
npx playwright install
```

## Project Structure

```
├── tests/                    # Test files
│   ├── example.spec.ts      # Example Playwright tests
│   ├── welcome.ts           # Welcome TypeScript file
│   └── test.ts              # Additional test file
├── playwright.config.ts     # Playwright configuration
├── tsconfig.json            # TypeScript configuration
├── package.json             # Project dependencies
└── README.md                # This file
```

## Running Tests

### Run all tests
```bash
npx playwright test
```

### Run specific test file
```bash
npx ts-node tests/welcome.ts
```

### Run with specific browser
```bash
npx playwright test --project=chromium
npx playwright test --project=firefox
npx playwright test --project=webkit
```

## Development

### Tools
- **Playwright**: End-to-end testing framework
- **TypeScript**: For type-safe testing code
- **ts-node**: Run TypeScript files directly

### TypeScript Compilation
The project uses `tsconfig.json` for TypeScript configuration. Key settings:
- Target: ES2020
- Module: CommonJS
- Strict mode enabled
- Node types included for proper typing

## Test Reports

After running tests, view the HTML report:
```bash
npx playwright show-report
```

## Contributing

Push changes to the repository:
```bash
git add .
git commit -m "Your commit message"
git push origin main
```

## License

ISC

## Author

Mayur
plawright learning with ts
>>>>>>> 537139b95782e433d9b29166111a5f0f815286c5
