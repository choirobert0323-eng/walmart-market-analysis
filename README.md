# Walmart Market Analysis

**Historical exploratory notebook and presentation archive.**  
Python · pandas · NumPy · Matplotlib · seaborn · scikit-learn

Walmart와 미국 주요 시장 지수의 시계열을 비교하는 수업 프로젝트 자료입니다. 대용량 발표 PDF는 Drive에 유지하고 GitHub에는 검토 가능한 노트북을 제공합니다.

## Materials

- [Historical notebook](notebooks/walmart_market_draft.ipynb)
- [Original presentation on Drive](https://drive.google.com/file/d/1FAFCyBHOVVCzlWTTy57SPivY7hxFUjG0/view)
- [Required input files](data/README.md)

The Drive presentation is 277,332,362 bytes (about 277 MB); it is linked rather than copied into Git history. Its contents were not downloaded or independently verified in this preparation pass.

## Notebook scope

The recovered source contains data loading/column normalization, date alignment, index-price comparisons, rolling price ranges and intraday price changes. These are exploratory associations; this repository does not establish a causal effect of Walmart on market indices or a validated trading strategy.

## Release status

**Archival draft — not an end-to-end reproducible release.** The local notebook is a candidate source for the resume project; its exact match to the presentation still needs confirmation. Source CSV files were not recovered, outputs were removed, and execution has not been independently reproduced.

Python cells were syntax-checked only. Historical non-Python planning cells were retained as markdown rather than silently deleted. Source logic is preserved; data alignment, duplicate column names, rolling calculations and downstream runtime behavior still require validation.

To inspect locally, install Jupyter and the imported libraries in a virtual environment and open `notebooks/walmart_market_draft.ipynb`. Supply the separately obtained CSV files in the notebook working directory. No tested dependency lockfile or execution-success claim is provided.

## Provenance

Prepared from an existing local coursework draft. No prices, model scores, graphs or performance results were fabricated for this release. Personal machine paths and notebook outputs are excluded. Original source data, presentation rights and team contributions should be credited before further redistribution. A project license has not been selected.
