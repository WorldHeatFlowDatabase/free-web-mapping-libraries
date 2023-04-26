<!DOCTYPE html>
<html>
  <body>
    <table>
      <tr>
        <th>Functionality</th>
        <th>Leaflet v1.9</th>
        <th>MapLibre v2.4</th>
        <th>OpenLayers v7.3</th>
      </tr>
      <tr>
        <td>Support WebGL</td>
        <td>
          Only with
          <a href="https://leafletjs.com/plugins.html">plugins</a>
          <li>
            <a
              href="https://gitlab.com/IvanSanchez/Leaflet.TileLayer.GL"
              >Leaflet.TileLayer.GL</a
            >
          </li>
          <li>
            <a
              href="https://github.com/ihmeuw/leaflet.tilelayer.glcolorscale"
              >Leaflet.TileLayer.GLColorScale</a
            >
          </li>
          <li>
            <a
              href="https://github.com/equinor/leaflet.tilelayer.gloperations"
              >Leaflet.TileLayer.GLOperations</a
            >
          </li>
          <li>
            <a
              href="https://gitlab.com/IvanSanchez/Leaflet.GLMarkers"
              >Leaflet.GLMarkers</a
            >
          </li>
        </td>
        <td>Maplibre uses WebGL <a href="https://maplibre.org/maplibre-gl-js-docs/api/">(Source)</a></td>
        <td>
          <li>
            <a
              href="https://openlayers.org/en/latest/apidoc/module-ol_webgl.html"
              >ol/webgl</a
            >
          </li>
          <li>
            <a
              href="https://openlayers.org/en/latest/apidoc/module-ol_layer_WebGLTile-WebGLTileLayer.html"
              >ol/layer/WebGLTile~WebGLTileLayer</a
            >
          </li>
          <li>
            <a
              href="https://openlayers.org/en/latest/apidoc/module-ol_webgl_Buffer-WebGLArrayBuffer.html"
              >ol/webgl/Buffer~WebGLArrayBuffer</a
            >
          </li>
          <li>
            <a
              href="https://openlayers.org/en/latest/apidoc/module-ol_webgl_RenderTarget-WebGLRenderTarget.html"
              >ol/webgl/RenderTarget~WebGLRenderTarget</a
            >
          </li>
          <li>
            <a
              href="https://openlayers.org/en/latest/apidoc/module-ol_webgl_PostProcessingPass-WebGLPostProcessingPass.html"
              >ol/webgl/PostProcessingPass~WebGLPostProcessingPass</a
            >
          </li>
          <li>
            <a
              href="https://openlayers.org/en/latest/apidoc/module-ol_renderer_webgl_TileLayer-WebGLTileLayerRenderer.html"
              >ol/renderer/webgl/TileLayer~WebGLTileLayerRenderer</a
            >
          </li>
          <li>
            <a
              href="https://openlayers.org/en/latest/apidoc/module-ol_renderer_webgl_PointsLayer-WebGLPointsLayerRenderer.html"
              >ol/renderer/webgl/PointsLayer~WebGLPointsLayerRenderer
            </a>
          </li>
        </td>
      </tr>
        <td>Change map language</td>
        <td>
          <li>
            <a
              href="https://github.com/leaflet-extras/leaflet-providers#leaflet-providers"
              >leaflet-extras/leaflet-providers</a
            >
          </li>
          <li>
            <a
              href="https://wiki.openstreetmap.org/wiki/Map_internationalization"
              >Map internationalization</a
            >
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://github.com/mapbox/mapbox-gl-language#mapbox-gl-language--"
              >Mapbox GL Language</a
            >
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://wiki.openstreetmap.org/wiki/Map_internationalization"
              >Map internationalization</a
            >
          </li>
        </td>
      </tr>
      <tr>
        <td>Basemap (OSM, Stamen, ...)</td>
        <td>
          <li>
            <a href="https://leafletjs.com/plugins.html#basemap-formats"
              >Basemap formats</a
            >
          </li>
          <li>
            <a href="https://leafletjs.com/plugins.html#basemap-providers"
              >Basemap providers
            </a>
          </li>
          <li>
            <a href="https://github.com/leaflet-extras/leaflet-providers"
              >leaflet-extras/leaflet-providers</a
            >
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://maplibre.org/maplibre-gl-js-docs/style-spec/sources/"
              >maplibre-style-spec/sources/</a
            >
          </li>
          <li>
            <a
              href="https://maplibre.org/maplibre-gl-js-docs/example/map-tiles/"
              >Add a raster tile source</a
            >
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://openlayers.org/en/latest/apidoc/module-ol_source.html"
              >ol/source</a
            >
          </li>
          <li>
            <a
              href="https://openlayers.org/en/latest/apidoc/module-ol_source_OSM-OSM.html"
              >ol/source/OSM~OSM
            </a>
          </li>
          <li>
            <a
              href="https://maplibre.org/maplibre-gl-js-docs/example/map-tiles/"
              >Add a raster tile source</a
            >
          </li>
        </td>
      </tr>
      <tr>
        <td>Vector file formats</td>
        <td>
          <li>
            <a href="https://leafletjs.com/plugins.html#overlay-data-formats"
              >Overlay data formats</a
            >
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://maplibre.org/maplibre-gl-js-docs/style-spec/sources/#geojson"
              >GeoJSON</a
            >
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://openlayers.org/en/latest/apidoc/module-ol_format_Feature-FeatureFormat.html"
              >ol/format/Feature~FeatureFormat</a
            >
          </li>
        </td>
      </tr>
      <tr>
        <td>Raster file formats</td>
        <td>
          <li>
            <a href="https://leafletjs.com/plugins.html#tileimage-display"
              >Tile/image display
            </a>
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://maplibre.org/maplibre-gl-js-docs/api/sources/#imagesource"
              >ImageSource
            </a>
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://openlayers.org/en/latest/apidoc/module-ol_source_Raster-RasterSource.html"
              >ol/source/Raster~RasterSource
            </a>
          </li>
        </td>
      </tr>
      <tr>
        <td>Vector tiles</td>
        <td>
          <li>
            <a href="https://leafletjs.com/plugins.html#vector-tiles"
              >Vector tiles
            </a>
          </li>
          <li>
            <a href="https://github.com/mapbox/geojson-vt"
              >geojson-vt — GeoJSON Vector Tiles
            </a>
          </li>
        </td>
        <td>
          <li>
            <a href="https://maplibre.org/maplibre-style-spec/sources/#vector"
              >vector
            </a>
          </li>
          <li>
            <a href="https://github.com/mapbox/geojson-vt"
              >geojson-vt — GeoJSON Vector Tiles
            </a>
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://openlayers.org/en/latest/apidoc/module-ol_source_VectorTile-VectorTile.html"
              >ol/source/VectorTile~VectorTile
            </a>
          </li>
          <li>
            <a href="https://github.com/mapbox/geojson-vt"
              >geojson-vt — GeoJSON Vector Tiles
            </a>
          </li>
        </td>
      </tr>
      <tr>
        <td>Raster tiles</td>
        <td>
          <li>
            <a href="https://leafletjs.com/plugins.html#tileimage-display"
              >Tile/image display
            </a>
          </li>
        </td>
        <td>
          <li>
            <a href="https://maplibre.org/maplibre-style-spec/sources/#raster"
              >raster
            </a>
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://openlayers.org/en/latest/apidoc/module-ol_source_Tile-TileSource.html"
              >ol/source/Tile~TileSource
            </a>
          </li>
        </td>
      </tr>
      <tr>
        <td>OGC services</td>
        <td>
          <li>
            <a href="https://leafletjs.com/examples/wms/wms.html"
              >WMS in Leaflet
            </a>
          </li>
          <li>
            <a href="https://leafletjs.com/examples/wms/wms.html"
              >TMS in Leaflet
            </a>
          </li>
          <li>
            <a href="https://github.com/Flexberry/Leaflet-WFST#leaflet-wfst"
              >Leaflet-WFST
            </a>
          </li>
          <li>
            <a
              href="https://github.com/opengeospatial/ogcapi-features/blob/master/implementations/clients/leaflet.md#leaflet"
              >OGC API Features
            </a>
          </li>
        </td>
        <td>
          <li>
            <a href="https://maplibre.org/maplibre-gl-js-docs/example/wms/"
              >Add a WMS source
            </a>
          </li>
          <li>WMTS (set URL to TileMatrixSet {z}/{y}/{x}.png)</li>
          <li>
            <a
              href="https://github.com/opengeospatial/ogcapi-features/blob/master/implementations/clients/leaflet.md#leaflet"
              >OGC API Features
            </a>
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://openlayers.org/en/latest/apidoc/module-ol_source_wms.html"
              >ol/source/wms
            </a>
          </li>
          <li>
            <a
              href="https://openlayers.org/en/latest/apidoc/module-ol_source_WMTS-WMTS.html"
              >ol/source/WMTS~WMTS
            </a>
          </li>
          <li>
            <a
              href="https://openlayers.org/en/latest/apidoc/module-ol_format_WFS-WFS.html"
              >ol/format/WFS~WFS
            </a>
          </li>
          <li>
            <a
              href="https://github.com/opengeospatial/ogcapi-features/blob/master/implementations/clients/leaflet.md#leaflet"
              >OGC API Features
            </a>
          </li>
        </td>
      </tr>
      <tr>
        <td>Projections</td>
        <td>
          <li>
            <a href="https://github.com/kartena/Proj4Leaflet">Proj4Leaflet</a>
          </li>
        </td>
        <td>
          <li>
            <a href="https://maplibre.org/maplibre-gl-js-docs/api/geography/"
              >Geography and geometry</a
            >
          </li>
          <li>
            <a href="https://github.com/maplibre/maplibre-gl-js/issues/168"
              >Support rendering in multiple CRS #168</a
            >
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://openlayers.org/en/latest/apidoc/module-ol_proj_Projection-Projection.html"
              >ol/proj/Projection~Projection</a
            >
          </li>
          <li>
            <a href="https://openlayers.org/en/latest/examples/?q=projection"
              >OpenLayers Examples</a
            >
          </li>
        </td>
      </tr>
      <tr>
        <td>Import user data</td>
        <td>
          <li>
            <a href="https://github.com/makinacorpus/Leaflet.FileLayer"
              >Leaflet.FileLayer</a
            >
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://maplibre.org/maplibre-gl-js-docs/example/local-geojson/"
              >View local GeoJSON</a
            >
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://openlayers.org/en/latest/examples/drag-and-drop.html"
              >Drag-and-Drop</a
            >
          </li>
        </td>
      </tr>
      <tr>
        <td>Download features as GeoJSON</td>
        <td>
          <ol type="1">
            <li>
              Bring features in GeoJSON format and change the input of the
              following tutorial (to the GeoJSON)
            </li>
            <li>
              <a
                href="https://ourcodeworld.com/articles/read/189/how-to-create-a-file-and-generate-a-download-with-javascript-in-the-browser-without-a-server"
                >How to create a file and generate a download with Javascript in
                the Browser (without a server)</a
              >
            </li>
          </ol>
        </td>
        <td>
          <ol type="1">
            <li>
              Bring features in GeoJSON format and change the input of the
              following tutorial (to the GeoJSON)
            </li>
            <li>
              <a
                href="https://ourcodeworld.com/articles/read/189/how-to-create-a-file-and-generate-a-download-with-javascript-in-the-browser-without-a-server"
                >How to create a file and generate a download with Javascript in
                the Browser (without a server)</a
              >
            </li>
          </ol>
        </td>
        <td>
          <ol type="1">
            <li>
              Bring features in GeoJSON format and change the input of the
              following tutorial (to the GeoJSON)
            </li>
            <li>
              <a
                href="https://ourcodeworld.com/articles/read/189/how-to-create-a-file-and-generate-a-download-with-javascript-in-the-browser-without-a-server"
                >How to create a file and generate a download with Javascript in
                the Browser (without a server)</a
              >
            </li>
          </ol>
        </td>
      </tr>
      <tr>
        <td>Layer switcher</td>
        <td>
          <li>
            <a
              href="https://leafletjs.com/plugins.html#layer-switching-controls"
              >Layer switching controls
            </a>
          </li>
          <li>
            <a href="https://leafletjs.com/examples/layers-control/"
              >Layer Groups and Layers Control</a
            >
          </li>
        </td>
        <td>
          <li>
            <a href="https://github.com/ka7eh/maplibre-gl-basemaps"
              >MapLibre GL Basemaps Control</a
            >
          </li>
          <li>
            <a href="https://github.com/watergis/mapbox-gl-legend"
              >mapbox-gl-legend</a
            >
          </li>
          <li>
            <a
              href="https://blog.astrid-guenther.de/maplibregl-show-and-hide-layers/"
              >Maplibre GL - Ebenen ein- und ausblenden</a
            >
          </li>
        </td>
        <td>
          <li>
            <a href="https://github.com/walkermatt/ol-layerswitcher"
              >OpenLayers LayerSwitcher</a
            >
          </li>
        </td>
      </tr>
      <tr>
        <td>Data driven feature visualization</td>
        <td>
          <li>
            <a href="https://github.com/lizardtechblog/Leaflet.OpacityControls"
              >Leaflet.OpacityControls</a
            >
          </li>
          <li>
            <a
              href="https://stackoverflow.com/questions/69859196/leaflet-change-color-onclick"
              >Leaflet: Change color onClick</a
            >
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://maplibre.org/maplibre-gl-js-docs/example/color-switcher/"
              >Change a layer's color with buttons</a
            >
          </li>
          <li>
            <a href="https://github.com/dayjournal/maplibre-gl-opacity"
              >maplibre-gl-opacity</a
            >
          </li>
          <li>
            <a
              href="https://docs.mapbox.com/mapbox-gl-js/example/data-driven-circle-colors/"
              >Style circles with a data-driven property</a
            >
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://openlayers.org/en/latest/examples/color-manipulation.html"
              >Color Manipulation</a
            >
          </li>
          <li>
            <a href="https://openlayers.org/en/latest/examples/cog-style.html"
              >Change Tile Layer Style</a
            >
          </li>
          <li>
            <a
              href="https://viglino.github.io/ol-ext/examples/filter/map.filter.colorize.html?lon=2.219234&lat=50.593699&z=8"
              >ol-ext: Color filter on map</a
            >
          </li>
          <li>
            <a href="https://openlayers.org/workshop/en/vector/style.html"
              >Making it look nice</a
            >
          </li>
        </td>
      </tr>
      <tr>
        <td>Graticule / Grid</td>
        <td>
          <li>
            <a href="https://github.com/Leaflet/Leaflet.Graticule"
              >leaflet.latlng-graticule</a
            >
          </li>
        </td>
        <td>
          <li>
            <a href="https://github.com/maptiler/maplibre-grid"
              >maplibre-grid</a
            >
          </li>
        </td>
        <td>
          <li>
            <a href="https://openlayers.org/en/latest/examples/graticule.html"
              >Map Graticule</a
            >
          </li>
        </td>
      </tr>
      <tr>
        <td>Time slider</td>
        <td>
          <li>
            <a href="https://github.com/dwilhelm89/LeafletSlider"
              >LeafletSlider</a
            >
          </li>
          <li>
            <a href="https://github.com/svitkin/leaflet-timeline-slider"
              >leaflet-timeline-slider</a
            >
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://maplibre.org/maplibre-gl-js-docs/example/timeline-animation/"
              >Create a time slider</a
            >
          </li>
        </td>
        <td>
          <li>
            <a href="https://openlayers.org/workshop/en/webgl/animated.html"
              >Animating meteorite impacts</a
            >
          </li>
          <li>
            <a
              href="https://www.earder.com/tutorials/timeseries-with-geoserver-and-openlayers/"
              >Creating a Timeseries with GeoServer and Open Layers</a
            >
          </li>
          <li>
            <a
              href="https://github.com/Bayer-Group/ol-kit/tree/master/src/TimeSlider"
              >ol-kit TimeSlider</a
            >
          </li>
        </td>
      </tr>
      <tr>
        <td>Cluster point features</td>
        <td>
          <li>
            <a href="https://github.com/Leaflet/Leaflet.markercluster"
              >Leaflet.markercluster
            </a>
          </li>
          <li>
            <a href="https://leafletjs.com/plugins.html#clusteringdecluttering"
              >Clustering/Decluttering
            </a>
          </li>
        </td>
        <td>
          <li>
            <a href="https://maplibre.org/maplibre-gl-js-docs/example/cluster/"
              >Create and style clusters
            </a>
          </li>
        </td>
        <td>
          <li>
            <a href="https://openlayers.org/en/latest/examples/cluster.html"
              >Clustered Features
            </a>
          </li>
        </td>
      </tr>
      <tr>
        <td>Show coordinates of cursor</td>
        <td>
          <li>
            <a href="https://github.com/ardhi/Leaflet.MousePosition"
              >Leaflet.MousePosition
            </a>
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://maplibre.org/maplibre-gl-js-docs/example/mouse-position/"
              >Get coordinates of the mouse pointer
            </a>
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://openlayers.org/en/latest/examples/mouse-position.html"
              >Mouse Position
            </a>
          </li>
        </td>
      </tr>
      <tr>
        <td>Popup showing feature info</td>
        <td>
          <li>
            <a href="https://leafletjs.com/reference.html#popup"
              >DivOverlay Popup
            </a>
          </li>
          <li>
            <a href="https://leafletjs.com/examples/geojson/"
              >Using GeoJSON with Leaflet
            </a>
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://maplibre.org/maplibre-gl-js-docs/api/markers/#popup"
              >Popup
            </a>
          </li>
          <li>
            <a
              href="https://maplibre.org/maplibre-gl-js-docs/example/?search=popup"
              >Examples of Popup
            </a>
          </li>
        </td>
        <td>
          <li>
            <a href="https://openlayers.org/en/latest/examples/popup.html"
              >Popup
            </a>
          </li>
        </td>
      </tr>
      <tr>
        <td>Export map / view</td>
        <td>
          <li>
            <a href="https://leafletjs.com/plugins.html#printexport"
              >Print/export
            </a>
          </li>
        </td>
        <td>
          <li>
            <a href="https://github.com/watergis/maplibre-gl-export"
              >malibre-gl-export
            </a>
          </li>
        </td>
        <td>
          <li>
            <a href="https://openlayers.org/en/latest/examples/export-map.html"
              >Map Export
            </a>
          </li>
        </td>
      </tr>
      <tr>
        <td>Geocoding</td>
        <td>
          <li>
            <a href="https://leafletjs.com/plugins.html#geocoding">Geocoding</a>
          </li>
        </td>
        <td>
          <li>
            <a href="https://maplibre.org/maplibre-gl-js-docs/example/geocoder/"
              >Geocode with Nominatim</a
            >
          </li>
        </td>
        <td>
          <li>
            <a href="https://github.com/jonataswalker/ol-geocoder"
              >OpenLayers Control Geocoder</a
            >
          </li>
        </td>
      </tr>
      <tr>
        <td>Select feature on click</td>
        <td>
          <li>
            <a href="https://leafletjs.com/examples/geojson/"
              >Using GeoJSON with Leaflet</a
            >
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://maplibre.org/maplibre-gl-js-docs/example/queryrenderedfeatures/"
              >Get features under the mouse pointer</a
            >
          </li>
        </td>
        <td>
          <li>
            <a
              href="https://openlayers.org/en/latest/examples/select-features.html"
              >Select Features</a
            >
          </li>
        </td>
      </tr>
      <tr>
        <td>Select features within circle</td>
        <td>
          <ol type="1">
            <li>
              <a
                href="https://leaflet.github.io/Leaflet.draw/docs/leaflet-draw-latest.html#l-draw-circle"
                >L.Draw.Circle</a
              >
            </li>
            <li>
              <a href="https://turfjs.org/docs/#buffer">Turfjs buffer</a>
            </li>
            <li>
              <a href="https://turfjs.org/docs/#pointsWithinPolygon"
                >Turfjs pointsWithinPolygon</a
              >
            </li>
          </ol>
        </td>
        <td>
          <ol type="1">
            <li>
              <a href="https://github.com/iamanvesh/mapbox-gl-draw-circle"
                >mapbox-gl-draw-circle</a
              >
            </li>
            <li>
              <a href="https://turfjs.org/docs/#buffer">Turfjs buffer</a>
            </li>
            <li>
              <a href="https://turfjs.org/docs/#pointsWithinPolygon"
                >Turfjs pointsWithinPolygon</a
              >
            </li>
          </ol>
        </td>
        <td>
          <ol type="1">
            <li>
              <a
                href="https://openlayers.org/en/latest/examples/draw-features.html"
                >Draw Features -> Circle</a
              >
            </li>
            <li>
              <a href="https://turfjs.org/docs/#buffer">Turfjs buffer</a>
            </li>
            <li>
              <a href="https://turfjs.org/docs/#pointsWithinPolygon"
                >Turfjs pointsWithinPolygon</a
              ><br />
              <a
                href="https://rawgit.com/webgeodatavore/ol3-extras-demos/master/select-jsts/select-advanced.html"
                >OpenLayers demo for selecting by polygon, circle, square and
                rectangle</a
              >
            </li>
          </ol>
        </td>
      </tr>
      <tr>
        <td>Select features within bounding box</td>
        <td>
          <ol type="1">
            <li>
              <a
                href="https://leaflet.github.io/Leaflet.draw/docs/leaflet-draw-latest.html#l-draw-rectangle"
                >L.Draw.Rectangle</a
              >
            </li>
            <li>
              <a href="https://turfjs.org/docs/#pointsWithinPolygon"
                >Turfjs pointsWithinPolygon</a
              >
            </li>
          </ol>
        </td>
        <td>
          <ol type="1">
            <li>
              <a
                href="https://github.com/thegisdev/mapbox-gl-draw-rectangle-mode"
                >Mapbox GL Draw Rectangle Mode</a
              >
            </li>
            <li>
              <a href="https://turfjs.org/docs/#pointsWithinPolygon"
                >Turfjs pointsWithinPolygon</a
              >
            </li>
          </ol>
        </td>
        <td>
          <ol type="1">
            <li>
              <a
                href="https://openlayers.org/en/latest/examples/draw-shapes.html"
                >Draw Shapes -> Box</a
              >
            </li>
            <li>
              <a href="https://turfjs.org/docs/#pointsWithinPolygon"
                >Turfjs pointsWithinPolygon</a
              >
              <a
                href="https://rawgit.com/webgeodatavore/ol3-extras-demos/master/select-jsts/select-advanced.html"
                >OpenLayers demo for selecting by polygon, circle, square and
                rectangle</a
              >
            </li>
          </ol>
        </td>
      </tr>
      <tr>
        <td>Select features within polygon</td>
        <td>
          <ol type="1">
            <li>
              <a
                href="https://leaflet.github.io/Leaflet.draw/docs/leaflet-draw-latest.html#l-draw-polygon"
                >L.Draw.Polygon</a
              >
            </li>
            <li>
              <a href="https://turfjs.org/docs/#pointsWithinPolygon"
                >Turfjs pointsWithinPolygon</a
              >
            </li>
          </ol>
        </td>
        <td>
          <ol type="1">
            <li>
              <a
                href="https://docs.mapbox.com/mapbox-gl-js/example/mapbox-gl-draw/"
                >Draw a polygon and calculate its area</a
              >
            </li>
            <li>
              <a href="https://turfjs.org/docs/#pointsWithinPolygon"
                >Turfjs pointsWithinPolygon</a
              >
            </li>
          </ol>
        </td>
        <td>
          <ol type="1">
            <li>
              <a
                href="https://openlayers.org/en/latest/examples/draw-shapes.html"
                >Draw Shapes -> Polygon</a
              >
            </li>
            <li>
              <a href="https://turfjs.org/docs/#pointsWithinPolygon"
                >Turfjs pointsWithinPolygon</a
              >
              <a
                href="https://rawgit.com/webgeodatavore/ol3-extras-demos/master/select-jsts/select-advanced.html"
                >OpenLayers demo for selecting by polygon, circle, square and
                rectangle</a
              >
            </li>
          </ol>
        </td>
      </tr>
    </table>
  </body>
</html>
