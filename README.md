# WF_Severity
GEE app for Wildfire's Severity Assesment
This app allows to the user to perform severity assesment of wildfires using Sentinel-2 imagery.

## Cloud masking
For Sentinel-2 masking, this project uses the code available at https://developers.google.com/earth-engine/tutorials/community/sentinel-2-s2cloudless adapted to JavaScript.

## Methodology
### Severity
The severity estimation is performed by the difference of pre-fire and post-fire conditions using NBR, NDVI, BAIS2, BAI and NDWI.
More about the methodology at (Spanish): http://repositorio.espe.edu.ec/handle/21000/25968

### Classification
The burned area definition is performed by a supervised classification using the RF algorithm and the samples provided by the user. The user can change the inputs and samples and perform again the classification in order to get better results.


Video available at: https://www.linkedin.com/posts/jonathan-panimboza-deleg-6251b6a8_googleearthengine-activity-6887453473558929408-CFnk?utm_source=share&utm_medium=member_desktop
APP: https://jonathangej.users.earthengine.app/view/anlisis-de-incendios-forestales
