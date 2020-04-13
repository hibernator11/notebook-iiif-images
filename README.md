[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hibernator11/notebook-iiif-images/master)

# notebook-iiif-images
GLAM institutions are starting to adopt new technology and services to provide access to image-based resources in order to encourage research, scholarship and the transmission of cultural knowledge. The International Image Interoperability Framework [IIIF](https://iiif.io/) aims to set of common application programming interfaces that support interoperability between image repositories.

The jupyter notebooks provided in this projectt are based on IIIF repositories in order to extract metadata and images, creating a CSV file representing de dataset as a result. These are examples of exploitation that can serve as a basis for further development.

## accessing-iiif-smithsonian
This jupyter notebook extracts a dataset as a CSV file from the Smithsonian Open Access digital collection. This example performs an automatic search, retrieving the manifests from the IIIF server to create a dataset with the metadata as a CSV file.

## accessing-iiif-europeana
This jupyter notebook extracts a dataset as a CSV file using the Europeana APIs. This example performs an automatic search, retrieving the manifests from the IIIF server to create a dataset with the metadata as a CSV file. It also includes a code to show the thumbnails as a gallery.

This example shows how to navigate the collection using the API by means of the manifest, annotations and full text resources.

## accessing-iiif-ugent
This jupyter notebook extracts a dataset as a CSV file from the UGent libraries collection. This example performs an automatic search, retrieving the manifests from the IIIF server to create a dataset with the metadata as a CSV file. The content used in this notebook is based on *la Russie illustrée* which is a periodical with 15 volumes and 748 issues. The digital content can be retrieved [here](https://lib.ugent.be/viewer/collection/RUG01-001643403#?c=&m=&s=&cv=&xywh=-2290%2C-224%2C7504%2C4200). 

## Requirements
The Open Access API requires an API key to access the endpoints. Please register with https://api.data.gov/signup/ to get a key.
Europeana IIIF APIs requires an API key to access the endpoints. Please register with https://pro.europeana.eu/page/get-api to get a key.

# References
[Smithsonian Open Access](https://www.si.edu/openaccess)
[Europeana APIs](https://pro.europeana.eu/page/iiif)
