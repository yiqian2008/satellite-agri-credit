# Coffee Credit Risk

Using satellite and climate data to estimate future agricultural cash flow and credit risk in Brazilian coffee regions.

## Project motivation

Traditional agricultural lending faces significant challenges due to limited visibility into crop conditions, expected yield, and future farm revenue. This project explores whether satellite imagery and climate data can be used to construct a forward looking agricultural credit risk indicator.

## Research question

Can remote sensing and weather signals from Brazilian coffee regions help predict future yield, revenue volatility, and agricultural credit risk?

## Study area

Initial focus: coffee-producing regions in Minas Gerais, Brazil, with a case study in the southern Minas Gerais area (e.g., Três Pontas).

## Data sources

- Sentinel-2 surface reflectance imagery
- NDVI and related vegetation indicators
- Weather and climate data
- Coffee price data
- Regional yield statistics

## Project pipeline

1. Define region of interest (ROI)
2. Extract vegetation signals from satellite imagery
3. Build monthly NDVI time series
4. Predict coffee yield
5. Estimate expected revenue
6. Construct a credit risk proxy

## Repository structure

- `data/`: raw and processed datasets
- `notebooks/`: exploratory analysis and modeling notebooks
- `scripts/`: reusable code for preprocessing and modeling
- `outputs/`: figures, tables, and maps
- `docs/`: project notes and references

## Current status

- [x] Initial ROI defined in Google Earth Engine
- [x] RGB composite exported
- [x] NDVI map generated
- [ ] Monthly NDVI time series export
- [ ] Yield model
- [ ] Revenue risk indicator

## Future directions

- Refine coffee-specific ROI
- Add multi-year time series
- Integrate coffee market price data
- Build agricultural credit risk score
