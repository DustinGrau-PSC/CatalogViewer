# CatalogViewer

Standalone viewer for JSDO catalogs.

Installation/setup
====================
Run from your browser directly, and provide the URL to your PDSOE-produced catalog file. Or, drop in your project under the RESTContent or PASOEContent directory, and it will attempt to auto-detect the path to your catalog.

Once a catalog is loaded, you should see a list of available services on the left. These are the exposed "resources" from the PDSOE annotations, as seen by the JSDO. Expanding a service will reveal any operations available. Selecting an operation will allow you to see the full URL to the service, the expected HTTP verb to utilize, a listing of request parameters, any associated schema, and give you the ability to run sample code against the endpoint.