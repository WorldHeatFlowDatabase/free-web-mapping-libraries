Tabel of Content
- [Summary ](#summary-)
- [Extend the functionality matrix ](#extend-the-functionality-matrix-)

## Summary <a name="summary"></a>

Further development of front-end technologies makes client-side web mapping applications a promising way of providing (interactive explorable) geodata to the global community. Which libraries address this topic and how the implementation of essential web GIS functionalities can be done using LeafLet, MapLibre or OpenLayers is part of this document. Therefore, internet research has been done collecting already existing solutions based upon each functionality and library. As a result, links to implementation examples, plugins or references in the API documentations have been gathered in a functionality matrix.<br>
The information gained by this research is in use for developing and implementing an interactive web mapping application as part of the World Heat Flow Database Project. Beside this, the document offers an overview for people who are new to this topic, provides code examples for common web GIS features and makes the readers familiar with topic-specific vocabulary and terms.

## Extend the functionality matrix <a name="extend"></a>
You can send a merge request containing the addition. Therefore, a basic template should be satisfied:<br>
<br>
⬌ Within one row:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;links only related to the corresponding functionality<br>
 ⬍  Within one column:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;links only related to the corresponding library <br>
⬌ + ⬍ Within one field:&nbsp;&nbsp;&nbsp;&nbsp;links only related to the corresponding functionality and library following the template below<br>
<br>
o Add a new Link to an existing functionality (as bullet point)
 ```html
<li>
    <a href="<link_to_web_source>"><Title></a>
</li>
 ```
o Add workflow to an existing functionality (as numbered list)
 ```html
<ol type="1">
    <li>
        <a href="<link_to_web_source>"><Title></a>
    </li>
</ol>
 ```
o Add a new functionailty (as row)
```html
<tr>
    <!--Functionality name-->
    <td>Vector file formats</td>
    <td>
        <li>
            <!--Leaflet link-->
            <a href="https://leafletjs.com/plugins.html#overlay-data-formats">Overlay data formats</a>
        </li>
    </td>
    <td>
        <li>
            <!--MapLibre link-->
            <a href="https://maplibre.org/maplibre-gl-js-docs/style-spec/sources/#geojson">GeoJSON</a>
        </li>
    </td>
    <td>
        <li>
            <!--OpenLayers link-->
            <a href="https://openlayers.org/en/latest/apidoc/module-ol_format_Feature-FeatureFormat.html">ol/format/Feature~FeatureFormat</a>
        </li>
    </td>
</tr>
```
