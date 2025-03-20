# SettleMint - Documentation

✨ [SettleMint Documentation](https://console.settlemint.com/documentation) ✨


## Prerequisites

- [Bun](https://bun.sh/) installed
- Node.js version specified in `.nvmrc`

## Getting Started

1. Clone the repository:-
   ```bash
   git clone https://github.com/settlemint/docs.git && cd docs
   ```
2. Install dependencies:
   ```bash
   bun install
   ```

## Running the Documentation

Start the development server:
```bash
bun run dev
```
Visit [http://localhost:3000/documentation](http://localhost:3000/documentation) in your browser.

## Building for Production

1. Build the project:
   ```bash
   bun run build
   ```
2. Start the production server:
   ```bash
   bun run start
   ```

## Project Structure

- `/content` - Documentation files
- `/src` - Website source code
- `/public` - Static assets

## Troubleshooting

- Ensure dependencies are installed:  
  ```bash
  bun install
  ```
- Clear the Next.js cache:  
  ```bash
  rm -rf .next && bun run build && bun run start
  ```

## Contributing

Check our contributing guidelines before submitting changes.

## Need Help?

1. Check error logs in the console.
2. Report issues in the [GitHub repository](https://github.com/settlemint/docs/issues).

## Links

- [SettleMint Website](https://settlemint.com)
- [Documentation](https://console.settlemint.com/documentation)
- [GitHub Repository](https://github.com/settlemint/docs)
