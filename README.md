# 3D Seismic Attribute Reservoir Analytics

Exploratory 3D seismic attribute notebooks for reservoir property prediction and interpretation.

## Screenshots

<!-- screenshots:start -->
![Curated notebook output 1](assets/screenshots/curated-output-01.png)

![Curated notebook output 2](assets/screenshots/curated-output-02.png)

![Curated notebook output 3](assets/screenshots/curated-output-03.png)

![Curated notebook output 4](assets/screenshots/curated-output-04.png)

![Curated notebook output 5](assets/screenshots/curated-output-05.png)

![Curated notebook output 6](assets/screenshots/curated-output-06.png)

![Curated notebook output 7](assets/screenshots/curated-output-07.png)

![Curated notebook output 8](assets/screenshots/curated-output-08.png)

![Curated notebook output 9](assets/screenshots/curated-output-09.png)

![Curated notebook output 10](assets/screenshots/curated-output-10.png)

![Curated notebook output 11](assets/screenshots/curated-output-11.png)

![Curated notebook output 12](assets/screenshots/curated-output-12.png)

![Curated notebook output 13](assets/screenshots/curated-output-13.png)

![Curated notebook output 14](assets/screenshots/curated-output-14.png)

![Curated notebook output 15](assets/screenshots/curated-output-15.png)

<!-- screenshots:end -->


## Repository Status

Private review draft. This repository was staged from a private working folder for review before any public publishing decision.

## What This Demonstrates

- Domain-focused analytical thinking
- Python/Jupyter workflow development
- Data cleaning and transformation
- Visualization and interpretation
- Reproducible project packaging

## Data And Privacy

High sensitivity risk: seismic, well, and reservoir data must be replaced with synthetic/public data before public release.

The files in this staged repository have been mechanically cleaned where possible:

- Jupyter checkpoint folders were removed.
- Absolute local paths were scrubbed from text files and notebooks.
- Notebook error outputs were removed.
- Risky or likely third-party binary files were excluded and listed in `EXCLUDED_FILES.csv`.

## Output Policy

Notebook outputs are intentionally not all cleared in this private review draft. Useful plots and tables can make the project understandable, but outputs must be reviewed before public release. For public repositories, the preferred approach is:

1. Keep a clean, rerunnable notebook.
2. Export selected sanitized plots to `assets/`.
3. Show the best 2-4 figures in this README.
4. Clear notebook outputs only when they expose private data, private paths, excessive raw tables, or execution noise.

## Run Locally

```bash
python -m venv .venv
pip install -r requirements.txt
jupyter lab
```

For Streamlit apps:

```bash
streamlit run app.py
```

## Review Checklist Before Public Release

- [ ] Confirm all data is public, synthetic, or approved for sharing.
- [ ] Confirm outputs do not expose private field names, coordinates, paths, UWIs, or production records.
- [ ] Replace placeholder paths with relative paths or sample data paths.
- [ ] Rerun notebooks from top to bottom.
- [ ] Export the best sanitized figures into `assets/`.
- [ ] Choose the final license.
