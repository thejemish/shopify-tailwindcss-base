# Shopify Theme with Tailwind CSS

A modern, customizable Shopify theme built with Tailwind CSS that provides a solid foundation for creating responsive e-commerce experiences with easy-to-use customization options.

## Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (Latest LTS version recommended)
- [Shopify CLI](https://shopify.dev/docs/api/shopify-cli)
- [Git](https://git-scm.com/)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/thejemish/shopify-tailwindcss-base
cd shopify-tailwindcss-base
```

2. Install dependencies:
```bash
npm install
```

## Development

This theme includes several npm scripts to help with development:

```bash
# Start theme development server
npm run dev

# Watch and compile Tailwind CSS
npm run css

# Watch and compile minified Tailwind CSS
npm run css:min

# Run theme check
npm run theme:check
```

## Theme Structure

```
├── assets/
│   ├── input.css     # Tailwind CSS input file
│   └── style.css     # Compiled CSS output
│   blocks/
├── config/
│   └── settings_schema.json  # Theme settings
├── layout/
├── sections/
├── snippets/
├── templates/
└── package.json
```

## Development Scripts

- `npm run dev`: Starts the Shopify theme development server
- `npm run css`: Watches and compiles Tailwind CSS in development mode
- `npm run css:min`: Watches and compiles Tailwind CSS in production mode (minified)
- `npm run theme:check`: Runs Shopify Theme Check for best practices and issues