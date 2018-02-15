# Red and Roe deer distribution in Great Britain

Raster (.geoTIFF) datasets of Red deer and Roe deer index od presence in Great Britain aggregated and aligned per 1 and 5km square grid of Great Britain.

## Primary datasets

### Roe deer (Capreolus capreolus) distribution over Europe

Authors: Alexander, N.S. et al., (2014). A First Attempt at Modelling Roe Deer (Capreolus capreolus) Distributions Over Europe. Open Health Data. 2(1), p.e2. DOI: http://doi.org/10.5334/ohd.ah

Repository location: http://dx.doi.org/10.6084/m9.figshare.1008335

Link to article: https://openhealthdata.metajnl.com/articles/10.5334/ohd.ah/#

### Red deer (Cervus elaphus) distribution over Europe

Authors: Wint, W. et al., (2014). A First Attempt at Modelling Red Deer (Cervus elaphus) Distributions Over Europe. Open Health Data. 2(1), p.e1. DOI: http://doi.org/10.5334/ohd.ag

Repository location: http://dx.doi.org/10.6084/m9.figshare.1008334

Link to article: https://openhealthdata.metajnl.com/articles/10.5334/ohd.ag/#

### License
Both datasets by Wint, W. et al., (2014) and Alexander, N.S. et al., (2014) are licensed under the Creative Commons Attribution 3.0 Unported License. To view a copy of this license, visit http://creativecommons.org/licenses/by/3.0/

## Secondary datasets

### Processing
Datasets were obtained using both Q-GIS software and R programming language and especially the package raster.
Primary rasters were first clipped with the Untied Kingdom shape file available from the DIVA-GIS webpage at: http://www.diva-gis.org.
Next they were re-projected to the ukgrid = "+init=epsg:27700" and aligned to fit the 1km and 5km square grids of the Ordnance Survey Grids of Great Britain. For these purposes I calculated the mean of the raster pixel values that fall within the 1km or 5km square grid.
The index of presence for each of the rasters ranges from 0 to 100.

### Authors
* **Elena Arsevska** - *Initial work* - [arsevska](https://github.com/arsevska)

### License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

### Acknowledgments
This secondary dataset was created for the purposes of the Small Animal Veterinary Surveillance Network (SAVSNET) - share of data initiative.
SAVSNET is an initiative from the British Small Animal Veterinary Association and the University of Liverpool. Both share the same passion for companion animal welfare, education and science.
More information on SAVSNET activities can be found here: https://www.liverpool.ac.uk/savsnet/about/
For further details on the dataset please write to: savsnet@liverpool.ac.uk
