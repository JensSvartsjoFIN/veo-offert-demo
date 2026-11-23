veo-demo-lib: three.js for veo-offert-demo.html (step 3b, the Teams call with 3D people), 2026-11-20.
three-r160.classic.min.js = fatgame/lib/three.module.min.js (three@0.160.0, MIT, see LICENSES.txt) as a
classic script (window.THREE), so the page also works opened from disk (file://), e.g. in VEO-offline.
Keep this folder NEXT TO veo-offert-demo.html; without it the call shows initials instead of 3D people.
Rebuild on pve: python3 /root/veo_demo_threelib_20261120.py
