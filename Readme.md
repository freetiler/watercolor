
# Watercolor Map Tiles by Stamen Design

![npm](https://img.shields.io/npm/v/@freetiler/watercolor)

This package contains tiles from the Watercolor Map Tiles by Stamen Design set. 

## Usage

The tiles can be used offline, be self-hosted, or accessed via the included CDN link for easy integration into web mapping applications.

To install offline via NPM: 
```
npm install @freetiler/watercolor
```

### CDN Links

You can use any NPM CDN to serve the tiles.

```
 - https://esm.sh/@freetiler/watercolor/tiles/{z}/{x}/{y}.jpg
 - https://unpkg.com/@freetiler/watercolor/tiles/{z}/{x}/{y}.jpg
```

### Tile Access Pattern

- `{z}` represents the zoom level (from 0 to 7).
- `{x}` and `{y}` represent the tile coordinates at the given zoom level.

## Tile Specs:

- **Minimum Zoom Level**: 0
- **Maximum Zoom Level**: 7
- **Projection Used**: EPSG:3857
- **Tile Size**: 256x256
- **Tile Format**: JPEG
- **Attribution**: "FreeTiler | Map tiles by Stamen Design, under CC BY 4.0. Data by OpenStreetMap, under CC BY SA."

### Example

Using it with Leaflet:

```javascript
  // If you have examples please create pull request.
```

Using it with OpenLayers:

```javascript
  // If you have examples please create pull request.
```

## License

Attribution Required: 

FreeTiler.com | Map tiles by Stamen Design, under CC BY 4.0. Data by OpenStreetMap, under CC BY SA.

## Disclaimer

This package is provided "as is", without warranty of any kind. Use at your own risk.
