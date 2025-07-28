# Acrylic Painting Image Specifications for Yirga Cheffe Coffee Research App

## Overall Artistic Direction
- **Style**: Acrylic painting with visible brushstrokes and painterly texture
- **Color Palette**: Warm coffee tones - rich browns, deep greens, golden yellows, rust oranges, cream highlights
- **Technique**: Impressionistic realism with artistic interpretation
- **Resolution**: 1200x800px for main cards, 1400x600px for detail headers
- **Format**: High-quality JPG optimized for web

## Main Topic Card Images (1200x800px)

### 1. Geography Card - "geography.jpg"
**Subject**: Mountainous Yirga Cheffe terrain with coffee plants
**Composition**: 
- Foreground: Lush green coffee plants with red cherries at mid-level elevation
- Middle ground: Rolling hills covered in traditional "garden coffee" cultivation
- Background: Distant mountains at 2,000+ meters with misty clouds
- Lighting: Golden hour sunlight filtering through forest canopy
**Color Emphasis**: Deep forest greens, golden earth tones, misty blues for mountains
**Key Elements**: 
- Coffee plants with visible cherries
- Traditional agroforestry intercropping
- Volcanic soil texture
- Elevation changes showing different growing zones

### 2. History Card - "history.jpg"
**Subject**: Traditional Ethiopian coffee ceremony with ancient pottery
**Composition**:
- Center: Traditional clay jebena pot over glowing embers
- Foreground: Ancient coffee beans scattered on woven mat
- Background: Soft-focus traditional Ethiopian home interior
- Side elements: Mortar and pestle, small clay cups (cini)
**Color Emphasis**: Warm earth tones, glowing amber from fire, deep browns of pottery
**Key Elements**:
- Authentic jebena pot with characteristic shape
- Glowing coals creating warm light
- Traditional woven textiles
- Smoke wisps carrying aromatic blessing

### 3. Culture Card - "culture.jpg"
**Subject**: Ethiopian women performing traditional coffee ceremony
**Composition**:
- Center: Graceful Ethiopian woman in traditional white dress conducting ceremony
- Foreground: Ceremonial coffee setup with roasting pan and beans
- Background: Community gathering, other women and children watching respectfully
- Environment: Traditional Ethiopian home setting
**Color Emphasis**: Pure whites of traditional dress, warm browns of coffee, golden skin tones
**Key Elements**:
- Traditional white cotton dress with colorful borders
- Respectful, sacred atmosphere
- Community participation
- Three stages of ceremony represented

### 4. Technology Card - "technology.jpg"
**Subject**: Modern coffee processing equipment alongside traditional methods
**Composition**:
- Left side: Traditional natural processing - coffee cherries drying on raised beds
- Right side: Modern wet processing facility with machinery
- Center: Transition showing both methods working in harmony
- Background: Processing facility with quality control equipment
**Color Emphasis**: Natural browns of drying coffee, metallic silvers of machinery, vibrant reds of fresh cherries
**Key Elements**:
- African raised drying beds
- Modern pulping machinery
- Quality control equipment
- Traditional hand-sorting methods

## Detail Page Header Images (1400x600px)

### 5. Geography Detail - "geography-detail.jpg"
**Subject**: Aerial view of Yirga Cheffe coffee growing regions
**Composition**:
- Panoramic view showing elevation changes from 1,700m to 2,200m
- Patchwork of coffee farms integrated with forest
- Rivers and watersheds feeding the region
- Distant view of traditional villages nestled in hills
**Color Emphasis**: Aerial perspective blues and greens, earth tones of cultivated areas
**Key Elements**:
- Clear elevation gradients
- Forest-coffee integration
- Natural water sources
- Sustainable land use patterns

### 6. History Detail - "history-detail.jpg"
**Subject**: Historical timeline visualization of Ethiopian coffee
**Composition**:
- Timeline flowing from ancient times (left) to modern era (right)
- Visual markers: Kaldi's goat discovery, traditional cultivation, cooperative formation
- Background: Evolving landscape showing historical progression
- Symbolic elements representing each era
**Color Emphasis**: Sepia tones for ancient history, gradually warming to modern vibrant colors
**Key Elements**:
- Legendary Kaldi with goats
- Traditional farming evolution
- Cooperative building
- UNESCO heritage symbol

### 7. Culture Detail - "culture-detail.jpg"
**Subject**: Women's sacred role in coffee ceremony traditions
**Composition**:
- Central focus: Elderly woman teaching young girl ceremony traditions
- Background: Extended family gathering around coffee ceremony
- Sacred elements: Aromatic smoke, blessing gestures, community bonds
- Cultural artifacts: Traditional tools, ceremonial items
**Color Emphasis**: Warm family tones, sacred golden light, traditional textile colors
**Key Elements**:
- Generational knowledge transfer
- Sacred ceremony atmosphere
- Community participation
- Cultural preservation

### 8. Technology Detail - "technology-detail.jpg"
**Subject**: Traditional and modern coffee processing methods comparison
**Composition**:
- Split composition showing parallel processing streams
- Traditional side: Hand-picking, natural drying, traditional tools
- Modern side: Mechanical processing, quality control, certification
- Center: Quality outcomes showing both produce excellent results
**Color Emphasis**: Natural earth tones for traditional, clean modern colors for technology
**Key Elements**:
- Processing equipment comparison
- Quality control systems
- Traditional knowledge preservation
- Innovation integration

## Technical Implementation

### CSS Integration
```css
.card-image img {
    filter: saturate(1.1) contrast(1.05);
    transition: all 0.4s ease;
}

.card:hover .card-image img {
    filter: saturate(1.2) contrast(1.1);
    transform: scale(1.1);
}
```

### Fallback Solutions
1. **CSS Gradients**: Rich background gradients when images aren't available
2. **SVG Patterns**: Artistic patterns representing each theme
3. **Color Coding**: Distinct color schemes for each topic area

### Optimization Requirements
- File size: Target 150-300KB per image
- Format: JPG with 85% quality for best balance
- Responsive: Multiple sizes for different screen densities
- Loading: Lazy loading with intersection observer
- Alt text: Detailed descriptions for accessibility

## Color Palette Reference

### Geography Theme
- Forest Green: #2d5016
- Earth Brown: #8B4513
- Mountain Blue: #4682B4
- Golden Light: #DAA520

### History Theme
- Ancient Clay: #CD853F
- Pottery Brown: #A0522D
- Ember Glow: #FF6347
- Smoke Gray: #696969

### Culture Theme
- Ceremony White: #FFF8DC
- Sacred Gold: #FFD700
- Traditional Red: #DC143C
- Community Brown: #8B4513

### Technology Theme
- Natural Coffee: #6F4E37
- Modern Silver: #C0C0C0
- Innovation Blue: #4169E1
- Quality Green: #228B22

## Implementation Notes
1. Images should be generated by AI image tools using these specifications
2. Each image needs careful composition to work with overlay text
3. Acrylic painting style should be consistent across all images
4. Colors should complement the existing CSS design system
5. Focus on storytelling - each image should convey the essence of its topic