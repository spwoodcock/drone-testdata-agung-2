# Drone Test Data Mt Agung 2

## Contents

- Images of Mt Agung, Bali, Indonesia.
  - Images are from adjacent tasks, allowing for processing in ODM.
  - As they are too large to store in Git, a link to a Google drive is provided.
- A GeoJSON AOI of the area.
- QGIS project to load and visually inspect.
- Images geopackage, to display inside QGIS easily.
- Image metadata CSV extracted via `exiftool`.

## Intentional Errors

- The imagery has a few intentional errors to be caught by DroneTM processing.
- As a result I would not recommend processing via tools like ODM, without
  first removing these files (i.e. by passing into DroneTM).
- Some have invalid EXIF, others blurry photos, or are simply black (indicating lens cap left on).
- These files are denoted by `_ISSUE_WITH_FILE.JPG`.

All imagery is licensed as CC-BY-4.0.
