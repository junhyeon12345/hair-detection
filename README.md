# Hair Detection
Objective: Detect pores and hairs with rotated bounding boxes, then further classify hair types <br>
Problem: Imperfect training data, rotated bounding boxes on CVAT (not Roboflow), specific guidelines on annotation and attribute classification <br>
Solution: Use the Element Tree module to manipulate CVAT XML annotations <br>
