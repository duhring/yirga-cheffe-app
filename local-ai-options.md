# Local AI Image Generation Options for Mac

## 🚀 Best Options for Your Mac

### 1. **Diffusion Bee** (Recommended - Easy Start)
- **What**: Native Mac app for Stable Diffusion
- **Install**: Download from diffusionbee.com
- **Pros**: Simple GUI, no terminal needed, optimized for Mac
- **Cons**: Limited customization
- **Perfect for**: Quick generation with our prompts

### 2. **Draw Things** (App Store)
- **What**: iOS/macOS app for Stable Diffusion
- **Install**: Mac App Store (free)
- **Pros**: Very user-friendly, works on Apple Silicon
- **Cons**: Mobile-focused interface
- **Perfect for**: Immediate use, no setup

### 3. **Stable Diffusion WebUI** (Most Powerful)
- **What**: Full-featured Stable Diffusion interface
- **Install**: Via Homebrew or GitHub
- **Pros**: Highly customizable, many models, extensions
- **Cons**: More technical setup required
- **Perfect for**: Professional results, fine control

### 4. **ComfyUI** (Advanced)
- **What**: Node-based interface for Stable Diffusion
- **Install**: GitHub download
- **Pros**: Extremely flexible workflows
- **Cons**: Steep learning curve
- **Perfect for**: Complex image generation workflows

## 🎯 Quick Setup Recommendations

### Option A: Immediate Use (5 minutes)
```bash
# Install Draw Things from Mac App Store
# Or download Diffusion Bee from website
# Use our prompts directly
```

### Option B: Full Setup (30 minutes)
```bash
# Install Homebrew if you don't have it
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# Install Python and dependencies
brew install python@3.11 git

# Clone Stable Diffusion WebUI
git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui.git
cd stable-diffusion-webui

# Run setup (downloads models automatically)
./webui.sh
```

## 🎨 Using Our Yirga Cheffe Prompts

### For Any Tool:
1. Copy prompts from our `generate-images.md`
2. Add these settings:
   - **Style**: "acrylic painting, visible brushstrokes"
   - **Size**: 1024x1024 (then crop to our ratios)
   - **Steps**: 30-50 for quality
   - **Guidance**: 7-12 for prompt adherence

### Example Workflow:
```
1. Open your chosen AI tool
2. Paste: "Acrylic painting of Yirga Cheffe Ethiopian mountainous coffee region..."
3. Add style: "painterly, visible brushstrokes, warm coffee colors"
4. Generate 4 variations
5. Pick best result
6. Resize to 1200x800px
7. Save as geography.jpg in assets/
```

## 💻 Mac-Specific Considerations

### Apple Silicon (M1/M2/M3):
- **Excellent**: All tools run great with Metal acceleration
- **Recommendation**: Start with Draw Things or Diffusion Bee
- **Performance**: Very fast generation times

### Intel Mac:
- **Good**: All tools work but slower
- **Recommendation**: Use cloud options or lighter models
- **Performance**: 2-5x slower than Apple Silicon

## 🔍 Check What You Have

### System Info:
```bash
# Check your Mac type
system_profiler SPHardwareDataType | grep "Chip\|Processor"

# Check available RAM (need 8GB+ for good results)
system_profiler SPHardwareDataType | grep "Memory"

# Check available storage (need 10GB+ for models)
df -h
```

## 📋 Step-by-Step for Beginners

### 1. Quick Start (Draw Things):
1. Open Mac App Store
2. Search "Draw Things"
3. Install (free)
4. Open app
5. Paste our geography prompt
6. Click generate
7. Save result as `geography.jpg`

### 2. Better Quality (Diffusion Bee):
1. Go to diffusionbee.com
2. Download for Mac
3. Install and open
4. Paste our prompts
5. Adjust settings for "artistic" style
6. Generate all 8 images
7. Save with correct filenames

## 🎯 Optimized Settings for Our Use Case

### Prompt Enhancements:
```
Base Prompt: [Our detailed prompt]
+ Style: "acrylic painting, visible brushstrokes, painterly texture"
+ Quality: "high quality, detailed, artistic"
+ Colors: "warm coffee colors, rich browns, forest greens"
+ Avoid: "photographic, digital art, cartoon"
```

### Technical Settings:
- **Resolution**: 1024x1024 or 1024x768
- **Steps**: 30-50
- **Guidance Scale**: 8-12
- **Sampler**: DPM++ 2M or Euler A
- **Model**: Stable Diffusion 1.5 or XL

## 🚀 Ready to Generate?

1. **Choose your tool** based on technical comfort
2. **Copy our prompts** from generate-images.md
3. **Generate the 8 images** we need
4. **Resize and save** with correct filenames
5. **Test in the app** - they'll load automatically!

## ✅ What You'll Get

Perfect acrylic paintings showing:
- Geography: Mountain coffee terrain
- History: Traditional ceremony
- Culture: Women's sacred roles  
- Technology: Traditional + modern methods

All with visible brushstrokes and warm coffee colors that perfectly match our app design!