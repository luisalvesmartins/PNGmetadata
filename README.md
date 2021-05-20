# PNGmetadata
Javascript library to change PNG metadata (tEXt)

Check example in "sample.html"

Load PNG into memory, retrieve the metadata or change the metadata and save the new png created.

To get the PNG metadata:
```javascript

var metadata=metadataPNG.gettEXt(PNGdata);
```

Command to change the metadata:
```javascript
var newpng=metadataPNG.replatetEXt(PNGdata, "new metadata code");
```
This is an adaptation from kujirahand node code.
