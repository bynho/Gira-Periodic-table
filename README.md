# GIRA — Tabela Periódica Mágica

An interactive periodic table application built with React, designed to make chemistry education engaging and fun.

## Features

- Interactive periodic table interface
- Element data and information
- Beautiful, responsive design
- Built with React (CDN-based)

## Development

### Local Development

```bash
npm run dev
```

This will start a local server at `http://localhost:3000`

### Build

```bash
npm start
```

## Deployment

This project is configured for deployment on Vercel. Simply connect your repository to Vercel and it will automatically deploy on every push.

### Manual Deployment

```bash
npm install -g vercel
vercel
```

## Project Structure

```
.
├── public/
│   ├── index.html          # Main application file
│   ├── elements-data.js    # Element data definitions
│   └── .thumbnail          # Thumbnail asset
├── package.json            # Project metadata and dependencies
├── vercel.json             # Vercel deployment configuration
└── README.md               # This file
```

## Technologies

- React 18.3.1 (CDN)
- Babel (for JSX transformation)
- HTML5 & CSS3

## License

MIT
