# Atmospheric Correction of a Landsat 8 Image (ENVI)

Academic project, Master of Science in GNSS, Mohammed First University (Morocco), 2022 to 2023.

## Goal
Prepare raw satellite data so that images can be compared over time and across places, by removing the effect of the atmosphere.

## Data
Landsat 8 scene of Nador (Morocco), downloaded from the USGS EarthExplorer portal (public data). The raw scene is not included in this repository because of its size: download it from EarthExplorer (scene ID: ADD THE SCENE ID).

## Method (ENVI 5.3)
1. Open the multispectral image in ENVI.
2. Radiometric calibration: convert the raw sensor values to top-of-atmosphere reflectance.
3. Dark Object Subtraction: remove atmospheric effects to obtain surface reflectance.

## Documentation
The theory (atmospheric absorption and scattering, spectral signatures) and every processing step are documented in a 39-page report (in French).

## Files
| File | Description |
|---|---|
| `screenshots/` | Screenshots of the main steps and results (ADD) |
| `report/` | 39-page report in French (PDF) |

## Tools
ENVI 5.3, USGS EarthExplorer.

## Credits
Data: USGS (Landsat 8). Software: ENVI 5.3.

## Author
Hakim El Azzouzi, github.com/Hakim-elazzouzi
