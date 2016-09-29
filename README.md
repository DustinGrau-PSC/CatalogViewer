# CatalogViewer

Standalone viewer for Data Object Catalogs.

Installation / Setup
====================
Run from your browser directly, and provide the URL to your PDSOE-produced catalog file. Or, drop in your project under the RESTContent or PASOEContent directory, and it will attempt to auto-detect the path to your catalog.

Once a catalog is loaded, you should see a dropdown list of available Services on the left. These contain the exposed Resources from any PDSOE annotations, as seen by the JSDO. Selecting a Resource will reveal any operations available. Selecting an Operation will allow you to see the full URL to the Resource, the expected HTTP verb to utilize, a listing of request parameters, any associated schema, and give you the ability to run sample code against the endpoint.