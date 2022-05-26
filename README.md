# AIChallenge2022
AI Challenge 2022 by GoMotive
## YOLO
## Preprocessing
### YOLO FORMAT
1. As data given is similar to COCO format.
2. COCO format dataset have labels in single json file.
3. YOLO requires dataset labels to be txt files for each image with class and boundary box parameters.
4. COCO format boundary box have parameters x,y,w,h where x,y is top left corner of boundary box and w,h are absolute width and height of boundary box.
5. While YOLO boundary box have parameters x,y,w,h where x,y are center of boundary box and w,h are relative width and height of boundary box.