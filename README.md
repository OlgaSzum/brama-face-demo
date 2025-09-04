# Brama Face Demo

Demo project: archival face recognition and mapping for digital humanities.  
Created as a volunteer project at **Brama Grodzka – Teatr NN** (Lublin, Poland).  

⚠️ **Note:** This repository contains *demo data only*.  
Full archival data is not included due to copyright and privacy restrictions.  

---

## Run in Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/USER/brama-face-demo/blob/main/notebooks/face_matching_demo.ipynb)

---

## Repository structure
- `notebooks/` – Colab notebooks (demo + full mode)
- `src/` – helper functions (I/O, detection, visualization)
- `data/reference/` – 2–3 demo reference photos (CC / Public Domain)
- `data/gallery/` – 5–10 demo gallery photos
- `reports/` – outputs generated during runs (CSV, HTML)
- `docs/` – GitHub Pages site (public demo)
  - `index.md` – landing page
  - `reports/` – published reports (static snapshots)

---

## Modes
- **DEMO_MODE = True** → runs on the small sample data included in `data/`
- **DEMO_MODE = False** → mounts Google Drive and runs on full local dataset

---

## License
- **Code**: MIT License (see `LICENSE`)  
- **Demo data**: see `data/README.md` (sources & licenses)  
- **Archival data**: restricted, not published in this repository  

---

## Languages
- Documentation & code: English  
- Reports for the institution: Polish  
