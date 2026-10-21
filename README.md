# Skyforge: Drone Build Lab

A single-page tool for planning a drone build part by part. Pick a frame, motors, propellers, ESC,
flight controller and battery, and the page greys out parts that don't work together and says why.

## Features
- Compatibility rules for size class, stack mounting, current, cell count and battery fit
- Estimates for weight, thrust, thrust-to-weight, hover current and flight time
- 3D performance map (dots and surface views) and live drone diagram with a test flight
- Balance check and a wiring and setup checklist
- Undo and redo, share links and build codes, print view
- Bring your own parts catalog (JSON) to use real products

## Run locally
Open `index.html` in a browser. There is no build step and no dependencies.

## Deploy with GitHub Pages
1. Push `index.html` to the root of a repository.
2. In the repository, go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then Save.
4. After a minute, the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Note
All numbers are estimates for planning. Confirm specs with the manufacturer, and follow your local drone rules.
