# wm-ocr

## How to use the filter

### import it from filtering.py

'''bash
 import filtering as filt
'''

### Call the method 

```python
 filt.filtering(imname, sourcefolder, outputfolder)
```

The parameters are:
'[String] imname'      : The name of the image (ex: "50752.jpg")
'[String] sourcefolder': The folder where the image is located (ex: "unfiltered/")
'[String] outputfolder': The folder here the image will be saved (ex:"filtered/")
The image will be saved with the same name as input

OBS:

```python
 filt.filtering ("50751.jpg", "unfiltered/", "filtered/")
 filt.filtering ("unfiltered/50751.jpg", "", "filtered/")
```

These two lines are equivalent and both save the image to "filtered/50751.jpg".
