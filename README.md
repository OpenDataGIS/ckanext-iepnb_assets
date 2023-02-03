# ckanext-iepnb_assets
Web assets of ckanext-iepnb: https://github.com/OpenDataGIS/ckanext-iepnb

## ckanext-iepnb parameters
```ini
## ckanext-iepnb
#Server to download menu an breadcrumbs
iepnb.server = https://opendatagis.github.io/ckanext-iepnb_assets

#default breadcrumbs
iepnb.breadcrumbs = [{"title":"Nuestros datos","description":"Nuestros datos","uri":"node/27","alias":"nuestros-datos","external":false,"relative":"/nuestros-datos"},{"title":"Catálogo de datos","description":"Catálogo de datos","uri":"node/47","alias":"catalogo-de-datos","external":false,"relative":"/nuestros-datos/catalogo-de-datos"}]

#relative path to download menu in iepnb.server
iepnb.path_menu = /main.json

#number of popular tags to show
iepnb.popular_tags = 3

#relative path to download. Uncomment to take precedence over iepnb.headcrumbs
#iepnb.path_breadcrumbs = No_Default_Value 
```
