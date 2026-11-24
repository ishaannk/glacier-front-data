# glacier-front-data

Data snapshot for a calving-front measurement benchmark task on Greenland outlet glaciers. The release holds two
tarballs (development and withheld sites). Each site is one glacier in one year: a measurement line (EPSG:3413),
a list of Landsat scenes, and a 4-band window (green, nir08, swir16, qa_pixel) of each scene.

Sources:
- Landsat Collection 2 Level-2 surface reflectance, USGS (public domain), read from Microsoft Planetary Computer.
- TermPicks V2 calving-front traces, Goliber et al. 2022, The Cryosphere 16, 3215-3233, doi:10.5194/tc-16-3215-2022;
  data doi:10.5281/zenodo.6557981, CC BY 4.0 (used to place the measurement lines).
