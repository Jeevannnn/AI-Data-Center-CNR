# AI Environmental Impact Visualizer 🌍

An interactive web application that visualizes the hidden environmental costs of artificial intelligence, including energy consumption, water usage, carbon emissions, and human impact of AI data centers and operations.

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://jeevannnn.github.io/AI-Data-Center-CNR/)

## 🎯 Overview

The "invisible cost" of AI is anything but invisible. This project provides an educational, data-driven visualization of:

- **Energy consumption** of AI queries and model training
- **Water usage** for cooling data centers
- **Carbon footprint** of AI operations
- **Land usage** by hyperscale data centers
- **Human impact** including "ghost work" labor conditions
- **Global distribution** of AI infrastructure

## ✨ Features

### 📊 Personal Impact Calculator
- Calculate your yearly AI usage footprint
- Separate tracking for text prompts and image generation
- Real-time equivalency comparisons (phone charges, water bottles, car kilometers)

### 🔍 Task Cost Estimator
- Estimate the environmental cost of individual AI tasks
- Support for text, image, and video generation
- Per-task energy and water consumption metrics

### 🗺️ Global Data Center Map
- Interactive visualization of 1,136+ hyperscale data centers worldwide
- Hover tooltips with facility details
- Regional distribution insights

### 📈 Data Visualizations
- Training cost comparisons (GPT-3 vs GPT-4)
- Global energy consumption charts
- Data center registry with operational details

### 📚 Educational Content
- Comprehensive sources and methodology
- Real-world case studies
- Human impact documentation

## 🚀 Getting Started

### Prerequisites

No installation required! This is a standalone HTML application that runs entirely in the browser.

### Local Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Jeevannnn/AI-Data-Center-CNR.git
   cd AI-Data-Center-CNR
   ```

2. **Open the application**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Python 3
     python -m http.server 8000
     
     # Node.js
     npx serve
     ```

3. **View in browser**
   - Navigate to `http://localhost:8000`

### GitHub Pages Deployment

1. Push this repository to GitHub
2. Go to **Settings** → **Pages**
3. Select **main** branch as source
4. Your site will be live at `https://jeevannnn.github.io/AI-Data-Center-CNR/`

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first styling
- **Chart.js** - Data visualizations
- **Font Awesome** - Icons
- **Vanilla JavaScript** - Interactivity and calculations

## 📖 Data Sources

This project uses data from:

- **IEA (International Energy Agency)** - Energy and AI Report (2024/2025)
- **UC Riverside (Li et al., 2023)** - "Making AI Less Thirsty" research paper
- **Synergy Research Group** - Hyperscale data center statistics
- **ABI Research** - Global cloud data center forecasts
- **TIME Magazine** - Investigative reporting on AI labor practices
- **Gray & Suri (2019)** - "Ghost Work" research

See the **Sources & Methodology** section in the application for detailed references.

## 🎨 Customization

### Updating Constants

Edit the calculator constants in the JavaScript section (around line 850):

```javascript
const TEXT_ENERGY_KWH = 0.003;  // Energy per text query
const IMAGE_ENERGY_KWH = 0.15;  // Energy per image generation
const TEXT_WATER_L = 0.015;     // Water per text query
const IMAGE_WATER_L = 0.5;      // Water per image generation
```

### Adding Data Center Locations

Add new data centers to the registry table (around line 320) and map dots (around line 590).

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

### Areas for Contribution

- 🔢 **Data Updates** - Help keep energy/water metrics current
- 🌍 **Internationalization** - Translate to other languages
- 📊 **New Visualizations** - Add charts or interactive elements
- ♿ **Accessibility** - Improve ARIA labels and keyboard navigation
- 📱 **Mobile Optimization** - Enhance responsive design

## 📧 Contact

For questions, suggestions, or feedback:
- Open an issue on GitHub
- Submit a pull request

## ⚠️ Disclaimer

This is an educational visualization. Actual environmental impacts vary by:
- Model efficiency and architecture
- Data center location and infrastructure
- Energy grid mix (renewable vs. fossil fuel)
- Cooling technology employed

Estimates are conservative averages based on peer-reviewed research and industry reports.

---

**Made with 💚 for environmental awareness in the AI age**
