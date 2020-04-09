# ULB_PflichtMap

Web-Karte zur Darstellung der Pflicht-Sammelgebiete der ULB Bonn zu verschiedenen historischen Zeitpunkten

- check out page via https://cbittner82.github.io/ULB_PflichtMap/

## data sources:

### boundaries:

- OSM-boundaries via https://wambachers-osm.website/boundaries/
  * Regierungsbezirk Düsseldorf (from 13.12.2019)
  * Regierungsbezirk Köln (from 6.12.2019)

- Rheinprovinz from https://geodata.lib.berkeley.edu/catalog/GHGIS1890PROVINCES

- files have been processed and geometrically adjusted

JavaScript Libraries:
 - lafletjs 1.6.0: https://leafletjs.com/download.html
 - leaflet-search: https://labs.easyblog.it/maps/leaflet-search/examples/geocoding-nominatim.html
 - leaflet.FileLayer: https://github.com/makinacorpus/Leaflet.FileLayer
