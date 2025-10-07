# HRD-CMD-diagrams

This Python program reads isochrone data from the [PARSEC](http://stev.oapd.inaf.it/cgi-bin/cmd) database, extracts the relevant parameters, and organizes them for further analysis. It then generates the **Color-magnitude diagram (CMD)** and the **Hertzsprung-Russell diagram (HRD)**, allowing comparison for a reference stellar population.

---

## Functions

* **read_isochrone**: reads PARSEC isochrone files in `txt` or `dat` format and extracts fundamental stellar parameters;
* **plot_diagrams**: generates HRD and CMD diagrams.

---

## Requirements

* Python 3.x
* [NumPy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [Matplotlib](https://matplotlib.org/)

These dependencies can be installed using:

```bash
pip install numpy pandas matplotlib
```
## Development and collaboration histort

This Python code was developed by Camilla Pianta during her collaboration with Dr. Antonino Milone’s research group, as part of a research project on multiple stellar populations (see Milone et al., 2025, https://arxiv.org/abs/2503.19214).

