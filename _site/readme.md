# VMASC Datathon Project Website

This website uses ["Minimal Mistakes"](https://github.com/mmistakes/minimal-mistakes) free Jekyll theme.

Get familiar with Jekyll by following their [Quickstart Instructions](https://jekyllrb.com/docs/) 


### Edit Site Naviation

- /_data/navigation.yml

### Update QGIS Map

All maps are located within the "/qgis-maps" folder.

If you wish to update, just replace the folder with new export. 

**Notes:**

- must keep folder names the same


### Replacing QGIS Map Legend

You will have to replace the old legend with the new legend in every qgis map file. The files are:

- [Significant Tree's QGIS Map](/qgis-map-1.markdown)
- [Planted Tree's QGIS Map](/qgis-map-2.markdown)
- [Significant & Planted Tree's QGIS Map](/qgis-map-3.markdown)
- [Parks and Recreation QGIS Map](/qgis-map-4.markdown)


In each of the files, you must change the 'src' to reference the new legend.


```html
<img src="/images/legend.png" width="300" height="275" align="right" style="padding-right: 1.5em;">
```
