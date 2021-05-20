# PNGmetadata
Javascript library to change PNG metadata (tEXt)

Check example in "sample.html"

Load PNG into memory, change the metadata and then save the new png created.

Command to change the metadata:
```javascript
var newpng=metadataPNG.replatetEXt(PNGdata, "new metadata code");
```

This is an adaptation from kujirahand node code.
