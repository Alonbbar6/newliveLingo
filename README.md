# 🌍 LiveLingo - Real-Time Text Detection & Translation

A browser-based computer vision application that detects text from webcam or uploaded images and translates it in real-time.

## ✨ Features

- **Real-time Text Detection**: Uses Tesseract.js OCR for accurate text recognition
- **Live Translation**: Automatic translation to 10+ languages using MyMemory API
- **Webcam Support**: Capture text directly from your camera
- **Image Upload**: Upload images for text detection and translation
- **Interactive UI**: Beautiful, responsive interface with real-time feedback
- **100% Browser-Based**: No backend required - runs entirely in JavaScript

## 🎯 Computer Vision Techniques Used

- **OCR (Optical Character Recognition)**: Tesseract.js for text detection and extraction
- **Bounding Box Detection**: Visual highlighting of detected text regions
- **Image Processing**: Canvas-based image manipulation and preprocessing
- **Confidence Thresholding**: Adjustable detection accuracy

## 🚀 Live Demo

**Deployed on Netlify**: [Your Netlify URL will appear here]

## 📦 Technologies

- **Tesseract.js** - Browser-based OCR engine
- **MyMemory Translation API** - Free translation service (no API key needed)
- **HTML5 Canvas** - Image rendering and bounding box visualization
- **MediaStream API** - Webcam access
- **Pure JavaScript** - No frameworks, no dependencies beyond CDN libraries

## 🛠️ Local Development

1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   cd myLiveLingo
   ```

2. Open `index.html` in a modern browser:
   ```bash
   # macOS
   open index.html

   # Linux
   xdg-open index.html

   # Windows
   start index.html
   ```

3. Or use a simple HTTP server:
   ```bash
   # Python 3
   python3 -m http.server 8000

   # Node.js
   npx serve
   ```

4. Navigate to `http://localhost:8000`

## 📤 Deploying to Netlify

### Option 1: Manual Upload via Netlify UI

1. Go to [Netlify](https://app.netlify.com/)
2. Sign up or log in
3. Click "Add new site" → "Deploy manually"
4. Drag and drop ONLY these files:
   - `index.html`
   - `netlify.toml`
   - `_redirects`
5. Your site will be live in seconds!

### Option 2: Deploy via Git (Recommended)

1. Create a new GitHub repository

2. Initialize git in your project:
   ```bash
   cd myLiveLingo
   git init
   git add index.html netlify.toml _redirects README.md .gitignore
   git commit -m "Initial commit: LiveLingo text detection app"
   ```

3. Add your GitHub remote:
   ```bash
   git remote add origin <your-github-repo-url>
   git branch -M main
   git push -u origin main
   ```

4. Connect to Netlify:
   - Go to [Netlify](https://app.netlify.com/)
   - Click "Add new site" → "Import an existing project"
   - Choose "GitHub" and select your repository
   - Build settings will auto-detect from `netlify.toml`
   - Click "Deploy site"

5. Your site is live! Netlify will provide a URL like `https://your-app.netlify.app`

### Option 3: Netlify CLI

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy
netlify deploy --prod
```

## 🎮 How to Use

1. **Start Webcam**: Click "Start Webcam" to enable your camera
2. **Capture & Translate**: Point camera at text and click "Capture & Translate"
3. **Upload Image**: Or upload an image with text using the "Upload Image" button
4. **Adjust Settings**:
   - Choose target language from dropdown
   - Adjust OCR confidence threshold (higher = more accurate, lower = more detections)
5. **View Results**: Detected text and translations appear below with bounding boxes

## 📋 Requirements Met

✅ **Computer Vision**: OCR text detection using Tesseract.js
✅ **Runs in Browser**: Pure HTML/CSS/JavaScript with CDN libraries
✅ **Interactive**: Webcam input + image upload + adjustable settings
✅ **Deployed**: Ready for Netlify deployment

## 🎨 Supported Languages

- Spanish (Español)
- French (Français)
- German (Deutsch)
- Italian (Italiano)
- Portuguese (Português)
- Chinese (中文)
- Japanese (日本語)
- Korean (한국어)
- Arabic (العربية)
- Russian (Русский)

## 🔧 Browser Compatibility

- Chrome 90+ (Recommended)
- Firefox 88+
- Safari 14+
- Edge 90+

**Note**: Webcam access requires HTTPS (automatically enabled on Netlify)

## 📝 Project Structure

```
myLiveLingo/
├── index.html          # Main application (standalone, all-in-one)
├── netlify.toml        # Netlify configuration
├── _redirects          # Netlify redirect rules
├── README.md           # This file
└── .gitignore          # Git ignore file
```

## 🤝 Contributing

This is a student project for a computer vision course. Feel free to fork and experiment!

## 📄 License

MIT License - feel free to use this project for learning purposes.

## 🙏 Acknowledgments

- **Tesseract.js** - Amazing OCR library
- **MyMemory API** - Free translation service
- Course requirements inspiration

---

**Built with ❤️ for Computer Vision class**
