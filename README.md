# Yirga Cheffe Coffee Research Web Application

## Overview
Interactive web application showcasing comprehensive research on Yirga Cheffe coffee production in Ethiopia. Features responsive card-based design with detailed topic pages covering geography, history, culture, and technology.

## Features
- **Interactive Cards**: Hover effects and smooth transitions
- **Responsive Design**: Mobile-optimized layouts
- **Detailed Pages**: Comprehensive research content for each topic
- **Smooth Navigation**: Seamless page transitions and accessibility features
- **Modern UI**: Coffee-themed design with professional typography

## Topics Covered

### 1. Geography & Environment
- Location and topography (1,700-2,200m elevation)
- Climate characteristics and seasonal patterns
- Volcanic soils and environmental conditions
- Microclimate variations and biodiversity

### 2. Historical Development
- Ancient origins and the legend of Kaldi (~850 AD)
- Evolution from wild harvesting to cultivation
- Key milestones including UNESCO recognition
- Traditional knowledge systems and practices

### 3. Cultural Impacts
- Traditional coffee ceremony and women's sacred role
- Social functions and community decision-making
- Economic impact on 45,094+ farmers
- Gender roles and cultural preservation

### 4. Technologies & Methods
- Traditional processing (natural and washed methods)
- Modern agricultural technologies and equipment
- Quality control and grading systems
- Sustainable and organic practices

## Project Structure
```
yirga-cheffe-app/
├── index.html              # Main landing page
├── css/
│   ├── styles.css          # Main stylesheet
│   └── detail-pages.css    # Detail page styles
├── js/
│   ├── main.js            # Main page JavaScript
│   └── detail-pages.js    # Detail page functionality
├── pages/
│   ├── geography.html     # Geography & Environment
│   ├── history.html       # Historical Development
│   ├── culture.html       # Cultural Impacts
│   └── technology.html    # Technologies & Methods
├── assets/
│   └── placeholder-info.txt # Image requirements
└── README.md              # This file
```

## Technical Features
- **Vanilla JavaScript**: No framework dependencies
- **CSS Grid & Flexbox**: Modern layout techniques
- **Intersection Observer**: Scroll-triggered animations
- **Accessibility**: Keyboard navigation and ARIA labels
- **Performance**: Optimized loading and animations
- **Print Support**: Print-friendly styling

## Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Local Development

### Option 1: Python Server
```bash
cd yirga-cheffe-app
python3 -m http.server 8080
```
Visit: http://localhost:8080

### Option 2: Node.js Server
```bash
npx serve yirga-cheffe-app
```

### Option 3: VS Code Live Server
Install "Live Server" extension and right-click index.html → "Open with Live Server"

## Key Statistics Displayed
- **45,094+** farmers in cooperative system
- **1,700-2,200m** elevation range for coffee growing
- **20,000** metric tons produced annually
- **UNESCO** World Heritage site designation

## Research Sources
Based on comprehensive research including:
- Academic publications on Ethiopian coffee
- YCFCU cooperative reports
- UNESCO World Heritage documentation
- Industry quality standards and processing methods

## Future Enhancements
- [ ] Add real photography for each topic
- [ ] Implement search functionality
- [ ] Add multilingual support (Amharic/English)
- [ ] Interactive maps for geographical data
- [ ] Video content integration
- [ ] API integration for live data

## Credits
Developed using Claude Flow SPARC mode for rapid prototyping and comprehensive content development.

## License
Educational and research use. Content based on publicly available research and documentation about Yirga Cheffe coffee production.

---

**Note**: This application is designed to work with or without images. CSS provides elegant fallbacks when images are not available. See `assets/placeholder-info.txt` for image requirements and specifications.