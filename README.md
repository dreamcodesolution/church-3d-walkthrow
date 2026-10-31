# A Walk to Our Church — 3D website prototype

## Important: open it through a web server
Do **not** open `index.html` directly from Android Files / a ZIP viewer. The 3D scene imports Three.js as an ES module and loads the church photographs as relative assets. Direct `content://` or `file://` opening can leave the scene blank.

## Easiest way to preview online (Vercel)
1. Extract this ZIP on your computer.
2. Upload the whole `church_walkthrough` folder to a GitHub repository (keep `index.html`, `vercel.json`, and the `assets` folder together).
3. In Vercel, choose **Add New → Project**, import that repository, and deploy.
4. Leave the Framework Preset as **Other**. No build command is needed; the root directory is the folder containing `index.html`.
5. Open the HTTPS deployment URL on your phone. Scroll to move through the scene.

## Preview locally on a computer
Run this from the extracted project folder:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser on that computer.

## What is included
- Scroll-driven Three.js scene
- Village road, trees, and school building on the right
- Church facade image based on the supplied church photographs
- Door-opening transition and supplied church-interior photograph
- Responsive layout for mobile and desktop

## Current prototype limitations
This is a first 3D visual prototype. It uses a procedural 3D environment and your photographs as facade/interior visual references. It is not yet a fully reconstructed photorealistic 3D model of the exact church. For that next stage, more side-angle and interior reference photos or a short video walkthrough would help.
