# FLAM-ToolpathGenerator

3D printing with natural materials is tricky due to warpage observed post curing. This results from evaporation of embedded moisture in material. To improve accuracy of prints with FLAM, a set of neural networks was trained with 3D scan data of various objects in two states: 1) Immediately after printing and 2) After complete drying. Outer surfaces of the objects were discretized into points and displacements of the same were measured between corresponding points from the two scans. The original toolpath is segmented into vertical slices and positional information from these slices is used to predict displacement of surface points arising from this localzied region.

The results are highly successful. The models were used to produce the largest biological structure ever printed at the time.


FLAM- https://www.nature.com/articles/s41598-018-26985-2
Hydra-https://dmand.sutd.edu.sg/news-events/news/come-visit-3d-printed-biological-structure-developed-sutd-scientists/
