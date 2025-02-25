# PALACE - Memory Palace Browser

PALACE is a React-based web application designed to help you browse and organize your memory palace items. The application provides a smooth and intuitive interface for navigating through different stages of processing, from raw extracted text to fully developed memory palace items.

## Features

- **Multi-stage Content Browsing**: Navigate between different processing stages:
  - Extracted Text: Raw text extracted from images using OCR
  - Stage 1 Processing: Organized text with main concepts identified
  - Stage 2 Processing: Condensed content with related points combined
  - Memory Palace Items: Visualized memory aids with emoji anchors

- **Smooth Navigation**: Easily switch between file types and processing stages
- **Enhanced Visualization**: Special rendering for memory palace items with emoji and visual representations
- **Responsive Design**: Works on desktop and mobile devices
- **GitHub Pages Integration**: Accessible online via GitHub Pages

## Getting Started

### Prerequisites

- Node.js (v14 or newer)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/RobertsLuke/PALACE.git
   cd PALACE
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server:
   ```bash
   npm start
   # or
   yarn start
   ```

4. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Deployment

The application is configured for easy deployment to GitHub Pages:

```bash
npm run deploy
# or
yarn deploy
```

## Project Structure

```
PALACE/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── FileViewer.js
│   │   ├── Layout.js
│   │   ├── MarkdownRenderer.js
│   │   ├── Navbar.js
│   │   ├── PalaceRenderer.js
│   │   └── Sidebar.js
│   ├── pages/
│   │   ├── ExtractedTextView.js
│   │   ├── Home.js
│   │   ├── PalaceView.js
│   │   ├── Stage1View.js
│   │   └── Stage2View.js
│   ├── utils/
│   │   └── api.js
│   ├── App.css
│   ├── App.js
│   └── index.js
├── .gitignore
├── package.json
└── README.md
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.