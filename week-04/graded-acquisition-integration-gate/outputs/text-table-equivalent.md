# Text/Table Equivalent of Map Result

The spatial join analysis compared the Facilities layer with the valid Service zones layer.

| Result | Count |
|---|---:|
| Total facilities | 5 |
| Facilities matched to service zones using within | 5 |
| Facilities matched to service zones using intersect | 5 |
| Invalid service-zone geometries | 0 |

The main finding is that all 5 facility features matched a service zone in both the within and intersect tests.

Changing the spatial predicate from within to intersect did not change the feature count, so the integration recommendation remained unchanged.

CRS: EPSG:4326 (WGS 84). Coordinates are in degrees.