#  Input Raster Stack Format

## Input Channels (X)

| Layer            | Description                  |
|------------------|------------------------------|
| Dem              | From Bhuvan                  |
| Slope            | From DEM                     |
| Aspect           | From DEM                     |
| Temperature      | From ERA5                    |
| Humidity         | From ERA5                    |
| Wind Speed       | From ERA5                    |
| Wind Direction   | From ERA5                    |
| LULC             | From Bhuvan                  |

- Format: GeoTIFF  
- Resolution: 30m  
- Projection: EPSG:4326 (WGS 84)  
- Final stacked shape: (1194,676,52)

##  Output Label (Y)

- Fire/No-Fire binary mask  
- Shape: (1194,676, 1)  
- Derived from VIIRS fire points  
