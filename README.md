# Human-Readable Precision-Recall curve construction procedure - (Pascal VOC 2012)
Since all I found in the web are really big sets of scripts to construct the curve defined in Pascal VOC 2012 and you need to believe that those scripts are gonna work (otherwise you will have to read a lot of code to understand what the guy is doing), I decided to build a notebook with the least amount of code to understand and build the curve.

## A few things to note
Actually, it's just one thing. Your annotations or detections coordinates will need to be as defined below.
The annotations are formated close to YOLO format, but the coordinates are not `<X[center]> <Y[center]> <W> <H>` they need to be like this `<X[top]> <Y[left]> <W> <H>`

In case you have annotations and detections in YOLO format you can still use this notebook, but you will have to do a code fast-read to see where you need to do those minor changes.
