# A Walk to Our Church — interactive prototype

## Run locally
Because this is a Three.js ES-module website, serve this folder over HTTP (do not open index.html as a file URL).

```bash
cd church_walkthrough
python3 -m http.server 8000
```
Then open http://localhost:8000

## Included
- Scroll-driven 3D approach scene
- Village path, trees and school on the right
- Church facade proportions and cross based on the supplied photographs
- Door-opening transition and supplied interior photograph
- Responsive layout

## Notes
This is a first visual prototype. It uses the supplied photographs as visual references/textures and procedural 3D geometry for the environment. For a production-grade, freely navigable photorealistic walkthrough, the church should be reconstructed as a detailed Blender model using additional side/rear/interior reference photos or a short video walkthrough. The Three.js module is loaded from jsDelivr, so an internet connection is required when previewing.
