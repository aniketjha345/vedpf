# T-Shirt Customizer

A React-based t-shirt customization application that allows users to:
- Upload custom images via drag-and-drop or file selection
- Add custom text to be printed on the t-shirt
- Specify height, weight, and build type
- Switch between different themes using Alt+Q

## Features

- Responsive design
- Image upload with preview
- Theme switching (Alt+Q)
- Form validation using react-hook-form
- Modern UI with Tailwind CSS

## Project Structure

```
├── src/
│   ├── App.tsx         # Main React component (fully commented)
│   ├── index.css       # Tailwind and custom styles (commented)
│   └── assets/         # Default t-shirt SVG and other images
├── index.html          # Main HTML file
├── tailwind.config.js  # Tailwind CSS config (commented)
├── vite.config.ts      # Vite config (commented)
├── package.json        # Project dependencies and scripts
└── README.md           # Project documentation
```

## Development

1. Install dependencies:
```bash
npm install
```

2. Start development server:
```bash
npm run dev
```

## Deployment to Cloudflare Pages

1. Build the project:
```bash
npm run build
```

2. Deploy to Cloudflare Pages:
   - Create a new project in Cloudflare Pages
   - Connect your Git repository
   - Set build command: `npm run build`
   - Set build output directory: `dist`
   - Deploy!

## Usage

- Use Alt + Q to switch between themes
- Drag and drop images or click to upload
- Enter text in the text area (max 3 lines)
- Adjust measurements using the form controls
- Choose text color, size, and position

## Technologies Used

- React
- TypeScript
- Vite
- Tailwind CSS
- react-hook-form
- react-hotkeys-hook

## Theme Switching
Press Alt+Q to switch between different themes:
1. Modern Light
2. Modern Dark
3. Nature

---

**All major files are commented for clarity. See each file for inline explanations.** 