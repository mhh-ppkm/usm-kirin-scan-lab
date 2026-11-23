# Kirin Scan Lab – Hand-Gesture Scanning

Ir. Ts. Dr. Muhammad Hafiz HASSAN · School of Mechanical Engineering, Universiti Sains Malaysia

Live page: https://mhh-ppkm.github.io/usm-kirin-scan-lab/

This repository is a single page (`index.html`, about 1.1 MB). The 3D engine is built into the page. The hand-tracking model loads from the internet the first time you press **Start camera**, so the computer needs internet access.

## Publish
1. Upload `index.html`, `README.md` and `.nojekyll` (Add file → Upload files → Commit changes).
2. Go to Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
3. After 1–2 minutes, open https://mhh-ppkm.github.io/usm-kirin-scan-lab/

## Scanning process
1. In the software, use the mouse to start a New Project Group, calibrate and choose Laser mode, as usual.
2. Press **Start camera** in the Hand-gesture scanner panel (bottom-right), and allow the camera.
3. **Pick up:** move your hand over the dashed Scanner cradle (bottom-left of the software window). Close the middle, ring and little fingers for about 1 second.
4. **Calibrate while holding:** move over the board to cover the gray circle. Moving toward or away from the webcam sets the height, and turning the wrist sets the tilt.
5. **Scan global markers:** close the index finger as well (full fist) to pull the trigger. Move left–right and up–down to sweep round the plate. The markers stop automatically at 80 % and are optimized.
6. **Scan the mesh:** keep the trigger pressed and walk round the part at low, middle and high angles. Keep the distance inside the green band until the coverage target is reached (80 % by default).
7. **Put it back:** keep gripping and bring the scanner to the cradle. The result card shows the total time, trigger time, % of time inside the working distance, coverage and number of drops.
8. Continue in the software: Mesh processing → hole filling → STL export.

If you open your hand while holding, the scanner is dropped and the scan pauses. Each drop is counted. Pick it up again at the cradle to continue.

Use Chrome or Edge on a laptop with a webcam and good, even lighting.
