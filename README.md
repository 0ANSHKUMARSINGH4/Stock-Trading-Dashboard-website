# StockViz - Interactive Stock Trading Dashboard

![StockViz Preview](https://images.unsplash.com/photo-1611974789855-9c2a0a7236a3?auto=format&fit=crop&q=80&w=1200&h=400)

A modern, interactive stock trading dashboard built with React, TypeScript, and Lightweight Charts. StockViz provides real-time visualization of stock data through line and candlestick charts, offering an intuitive interface for tracking market trends.

## Features

- 📈 Interactive line and candlestick charts
- 🔄 Real-time data visualization (mock data)
- 🎨 Dark mode interface
- 📱 Responsive design
- ⚡ Fast and lightweight
- 🔍 Interactive zooming and panning
- 💡 Hover tooltips with detailed price information

## Tech Stack

- React 18
- TypeScript
- Vite
- TailwindCSS
- Lightweight Charts
- Lucide React Icons

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm (v9 or higher)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/stockviz.git
cd stockviz
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and visit `http://localhost:5173`

### Building for Production

To create a production build:

```bash
npm run build
```

The built files will be in the `dist` directory.

## Project Structure

```
stockviz/
├── src/
│   ├── components/      # Reusable components
│   ├── utils/          # Utility functions and mock data
│   ├── types/          # TypeScript type definitions
│   ├── App.tsx         # Main application component
│   └── main.tsx        # Application entry point
├── public/             # Static assets
└── package.json        # Project dependencies and scripts
```

## Available Scripts

- `npm run dev` - Starts the development server
- `npm run build` - Creates a production build
- `npm run preview` - Previews the production build locally
- `npm run lint` - Runs ESLint to check code quality

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Lightweight Charts](https://www.tradingview.com/lightweight-charts/) for the charting library
- [Lucide React](https://lucide.dev/) for the beautiful icons
- [TailwindCSS](https://tailwindcss.com/) for the utility-first CSS framework