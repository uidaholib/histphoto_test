# histphoto_test

replace Fusion table, https://www.google.com/fusiontables/DataSource?docid=1rg-iVOXas2zhZ2lY9kvmxkZonyOfrh6HMI_gboYO

https://www.lib.uidaho.edu/special-collections/histphoto/

## Scaling DataTables

- enable paging, https://datatables.net/reference/option/paging
- use ajax, https://datatables.net/reference/option/ajax
- deferRender, https://datatables.net/reference/option/deferRender
- orderClasses, https://datatables.net/reference/option/orderClasses

## notes 

image link types:

- http://digital.lib.uidaho.edu/cdm/search/collection/pg1/searchterm/Third Annual Swine Type Conference. University of Idaho.
- https://digital.lib.uidaho.edu/digital/collection/pg1/search/searchterm/dogs
- "https://digital.lib.uidaho.edu/cdm/search/collection/{{ site.data.theme.cdm-collection-id }}/searchterm/" + encodeURIComponent(query) + "/field/all/mode/all/conn/and/order/title/ad/asc", "_blank"
- https://www.lib.uidaho.edu/special-collections/histphoto/Pg6010/6010-95-10.jpg

- collection names don't match cdm stubs
