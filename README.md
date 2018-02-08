# voc2coco
Convert voc annotation xml to COCO json format.

1. pip install lxml
2. python voc2coco.py xmllist.txt ../Annotations output.json

The xmllist.txt is the list of xml file names to convert.
000005.xml
000007.xml
000009.xml

The "../Annotations" is the place where all xmls located.

The "output.json" is the output json file.
