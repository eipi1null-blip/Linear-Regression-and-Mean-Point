# Correlation & Regression Visualizer

A self-contained, static applet. No build step, dependencies, server-side code, or API keys are required.

## Publish with GitHub Pages

1. Create a GitHub repository and upload `index.html` to its root.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then select your default branch and **/(root)**. Save.
4. Open the Pages URL shown in Settings after publication finishes.

You can also place `index.html` in a `docs/` folder and select **/docs** in the Pages settings. `README.md` is optional for deployment.

## Use

Click or tap the square to add data points. Drag points to change the data. Double-click or double-tap a point to remove it. Use the checkboxes to reveal the least-squares regression line and the mean lines.

The graph represents both x and y values from 0 to 100. All processing happens in the browser; no point data is uploaded or saved.
