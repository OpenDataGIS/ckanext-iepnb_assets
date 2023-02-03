# ckanext-iepnb_assets
Backup web assets of the [IEPNB Open Data portal](https://iepnb.es/catalogodatos) needed for the plugin [ckanext-iepnb](https://github.com/OpenDataGIS/ckanext-iepnb) plugin.

```ini
## ckanext-iepnb
# Server to download menu an breadcrumbs.
iepnb.server = https://github.com/OpenDataGIS/ckanext-iepnb_assets

# Default breadcrumbs
iepnb.breadcrumbs = [{"title":"Nuestros datos","description":"Nuestros datos","uri":"node/27","alias":"nuestros-datos","external":false,"relative":"/nuestros-datos"},{"title":"Catálogo de datos","description":"Catálogo de datos","uri":"node/47","alias":"catalogo-de-datos","external":false,"relative":"/nuestros-datos/catalogo-de-datos"}]

# Relative path to download menu in iepnb.server.
iepnb.path_menu = /main.json

# Number of popular tags to show
iepnb.popular_tags = 3

# Relative path to download. Uncomment to take precedence over iepnb.breadcrumbs
#iepnb.path_breadcrumbs = No_Default_Value 
```
