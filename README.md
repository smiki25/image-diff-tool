# Image Diff Tool

A standalone, browser-based image comparison tool that highlights differences between two images in red.

## Features

? **100% Client-Side** - No server required, all processing happens in your browser  
? **Privacy First** - Your images never leave your computer  
? **Visual Diff Highlighting** - Differences shown in bright red  
? **Adjustable Sensitivity** - Control how strict the comparison is  
? **Responsive Design** - Works on desktop and mobile  
? **Zero Dependencies** - Single HTML file, works offline  
? **Lightbox View** - Click any image to view full-size  

## How to Use

### Option 1: Direct File
Simply open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge)

### Option 2: Local Server
```bash
# Python 3
python -m http.server 8000

# Node.js (if you have http-server installed)
npx http-server

# Then open: http://localhost:8000
```

## Using the Tool

1. **Upload Images**
   - Click on the left box to upload your first image
   - Click on the right box to upload your second image

2. **Adjust Sensitivity** (Optional)
   - Use the slider to control comparison strictness
   - Lower values = more sensitive (detects smaller differences)
   - Higher values = less sensitive (only major differences)

3. **Compare**
   - Click "Compare Images" button
   - Wait for processing (usually instant)

4. **View Results**
   - **Left**: Your first image
   - **Middle**: Diff with red highlights showing differences
   - **Right**: Your second image
   - Click any image to view full-size

## Use Cases

- ?? **Design QA** - Compare design mockups vs implementation
- ??? **Visual Regression Testing** - Check for unintended UI changes
- ?? **Screenshot Comparison** - Compare app screens across versions
- ?? **Website Testing** - Compare production vs staging pages
- ?? **Image Verification** - Verify image processing/compression results
- ?? **Spot the Difference** - Find subtle changes between images

## Technical Details

- Pure HTML5 Canvas API for image processing
- RGB color difference calculation
- Pixel-by-pixel comparison algorithm
- Muted background for identical pixels
- Bright red highlighting for different pixels

## Browser Compatibility

Works in all modern browsers that support:
- HTML5 Canvas
- FileReader API
- ES6 JavaScript

## Privacy & Security

- ? No data is sent to any server
- ? All processing happens locally in your browser
- ? Images are never uploaded anywhere
- ? No cookies or tracking
- ? Can be used completely offline

## License

Free to use, modify, and distribute. No attribution required.

## Credits

Created as a standalone tool for comparing images and highlighting differences visually.


