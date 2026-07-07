# corr_transport_street_pattern

Notebook experiments linking transport accessibility and street-pattern classes.

## Scheme

```mermaid
flowchart LR
    A[Inputs] --> B[Run: cleaned_ver.ipynb]
    B --> C[Checked outputs]
    C --> D[Paper / thesis use]
```

## Main Result

![Main result](docs/readme_result.svg)

## Run

Entrypoint: `cleaned_ver.ipynb`

Human:

```bash
jupyter notebook cleaned_ver.ipynb
```

Agent:

Confirm local `data/` bundle exists before running notebooks.

## Publication

No standalone publication tracked.

## Next Steps / Heuristics

Simplify by treating notebooks as exploratory; promote stable code to pipeline/submodule scripts.
