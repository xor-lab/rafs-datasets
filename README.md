Datasets for the paper: _Formulating and solving integrated order batching and routing in multi-depot AGV-assisted mixed-shelves warehouses_

There are four folders in datasets: _distances, sku24, sku360_ and _sku3240_. The _distances_ folder includes the distance between each pair of locations (including depot/output station, picking location and shelves/pod) in a JSON file, e.g. _layout_sku_3240_8.json_. In this file, the distance information within the layout of 3240 shelves and 8 depots is shown. The _sku24_ folder includes the following files for the layout with 24 pods (likewise for those with 360 and 3240 pods): 

**layout_sku_24_2.xml** includes all waypoints of the layout with 24 pods and 2 output stations and the path between two waypoints. Furthermore, it also includes the coordinate positions of picking locations (ID, x- and y-coordinates), pod locations, output station locations and the beginning location of each cobot/bot. Note that this file contains more information that is needed for further research. 

**orders_10_mean_1x6_sku_24.xml** includes the information for 10 orders with an average of 1.6 order lines (small-line orders) in a layout with 24 pods. We have a, b and none at the end of each XML, which represent three different order sets. 1.6 can be replaced by 5 if we consider multi-line orders, i.e. an average of 5 order lines. 

In each XML file, we have _ItemDescription_, which shows the properties of items, including color, ID, letter and weight. Furthermore, we have _Orders_, including the order lines and items. 

**pods_items_dedicated_1.xml** and **pods_items_mixed_shevels_1-x.xml** shows information about the distribution of SKUs per pod. _Dedicated_ means that each pod includes only one SKU, while _mixed_shelves_x_ means that one SKU can be spread between one and x pods.

The data format ist:
_Pod_ID; x-coordinate/y-coordinate; color/letter/count;…;_

For example:

_0;7.3500000000000005/0.65;red/c/16;green/d/19;blue/f/16;red/g/15;blue/h/31;_ 


**24 pods with 2 stations layout**:
![layout](https://user-images.githubusercontent.com/61032543/162757138-cf804594-0423-4312-80a5-d41a87f0e340.png)
**24 pods with 1 stations layout**:
![layout_sku_24_1](https://user-images.githubusercontent.com/61032543/169673288-d6fc26c7-5c92-4d84-98dc-d2c0c02c1463.png)
**360 pods with 2 stations layout**:
![layout](https://user-images.githubusercontent.com/61032543/162757436-eeb2f9ff-4821-4460-9241-471952914ceb.png)
**360 pods with 1 stations layout**:
![layout_sku_360_1](https://user-images.githubusercontent.com/61032543/169673307-8bdb4e2f-0169-4f38-aa5a-9ca556ff72bb.png)
**360 pods with 4 stations layout**:
![layout - 4](https://user-images.githubusercontent.com/61032543/162757473-b960f27e-67af-4ffc-9358-f43bade3dda0.png)
**3240 pods with 2 stations layout**:
![layout](https://user-images.githubusercontent.com/61032543/162757568-efb5eda0-f959-4ddb-a567-062c98c54b0d.png)
**3240 pods with 4 stations layout**:
![layout_3240_4](https://user-images.githubusercontent.com/61032543/162757614-ea09a803-9884-42c6-ab28-afde02876863.png)
**3240 pods with 8 stations layout**:
![layout_3240_8](https://user-images.githubusercontent.com/61032543/162757637-fbf4a6c1-40ef-45b0-8347-bacc05e56757.png)
