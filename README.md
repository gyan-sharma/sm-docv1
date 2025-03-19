# SettleMint - Documentation

✨ [SettleMint Documentation](https://console.settlemint.com/documentation) ✨

This repository contains the source code for SettleMint's documentation website.

## Prerequisites

- [Bun](https://bun.sh/) - Make sure you have Bun installed on your system
- Node.js version specified in `.nvmrc`

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/settlemint/docs.git
cd docs
```

2. Install dependencies:

```bash
bun install
```

## Running the Documentation

1. Start the development server:

```bash
bun run dev
```

2. Access the documentation:
   - Open your browser and navigate to:
     [http://localhost:3000/documentation](http://localhost:3000/documentation)
   - The documentation should now be available in your browser

## Development

The documentation is built using:

- Next.js
- MDX for content
- TypeScript
- Tailwind CSS

## Building for Production

To create and run a production build:

1. Create the production build:

```bash
bun run build
```

2. Start the production server:

```bash
bun run start
```

## Project Structure

- `/content` - Documentation content files
- `/src` - Source code for the documentation website
- `/.cursor/rules` - Project-specific rules and configurations
- `/public` - Static assets

## Troubleshooting

If you encounter any issues:

1. Make sure all dependencies are properly installed:

```bash
bun install
```

2. Try clearing the Next.js cache and rebuilding:

```bash
rm -rf .next
bun run build
bun run start
```

3. Verify that you're using the correct URL:
   `http://localhost:3000/documentation`

## Contributing

Please read through our contributing guidelines before making any changes to the
documentation.

## Need Help?

If you encounter any issues or need assistance:

1. Check the console for error messages
2. Create an issue in the
   [GitHub repository](https://github.com/settlemint/docs/issues)
3. Ensure all environment variables are properly set (if required)

## License

This project is licensed under the terms specified in the repository's LICENSE
file.

## Links

- [SettleMint Website](https://settlemint.com)
- [Documentation](https://console.settlemint.com/documentation)
- [GitHub Repository](https://github.com/settlemint/docs)
