# Hot Plate

Arrange 3D shapes (or import your own .obj / .stl), melt them like chocolate on a warm surface, scrub back to any moment, and export a PNG or a printable STL.

Everything runs in the browser. `index.html` is the whole app; it loads three.js and three-mesh-bvh from the jsDelivr CDN.

## Publish on GitHub Pages

1. Create a new public repository and upload `index.html` (and this README) to it.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, and save.
4. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

To update it, replace `index.html` with a new version and commit.
