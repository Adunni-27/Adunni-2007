# AIDA 2362 Lab 1

## 1. Who is the decision-maker?

The decision-maker is the analyst reviewing the fictional facility and service-zone data to determine whether the data are suitable for integration.
## 2. What action might they take?

The decision-maker may decide whether the fictional facility and service-zone data should be used for a limited integration check.
## 3. What area or spatial unit are you checking?

The spatial units being checked are the fictional facility points and service-zone polygons provided in the lab.
## 4. What geographic area do the supplied data cover?

The supplied data cover a fictional example area in Alberta, Canada.
## 5. What scale is appropriate for interpreting the results?

The results should be interpreted at a local scale because the data represent a small fictional Alberta study area rather than the whole province.
## 6. What date or time limitation applies?

The supplied fictional data have a time limitation because the lab does not indicate that they are current or suitable for real-world operational use.
## 7. Is your decision ready, conditional, quarantine, or reject?

My decision is conditional because the data can be used for this limited fictional integration exercise, but they still have important limitations related to CRS, time, scale, and real-world authority.
## 8. Why is your decision limited to this fictional learning example?

The decision is limited to this fictional learning example because the supplied data are instructional and should not be used for real operational decisions.
## Facility Layer Check

The Facilities layer contains 5 point features. The geometry type is Point. All five feature IDs are present and unique, and no blank values were observed in the important fields checked.

QGIS shows the layer CRS as Unknown, although the supplied metadata identifies the intended storage CRS as EPSG:4326. This discrepancy should be considered before using the data for spatial analysis.
## Service Zone Layer Check

The Service zones layer contains 3 polygon features. The geometry type is Polygon. All three feature IDs are present and unique, and each zone has a zone name.

QGIS shows the layer CRS as Unknown, although the supplied metadata identifies the intended storage CRS as EPSG:4326. This discrepancy should be checked before spatial analysis.
## Geometry Validity Check

The Service zones layer was checked using the QGIS Check Validity tool with the GEOS method.

The result showed 3 valid features, 0 invalid features, and 0 errors. No invalid feature IDs or geometry errors were reported.
## CRS and Units

The supplied data use EPSG:4326 for storage. EPSG:4326 uses longitude and latitude measured in degrees, not metres.

For any distance or area analysis, a separate projected working copy should be created. For this Alberta example, the lab suggests EPSG:32612, which uses metres.

The CRS used for analysis must be appropriate for the geographic location and for the type of measurement being performed.