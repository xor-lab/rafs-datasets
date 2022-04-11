Datasets for the paper: Formulating and solving integrated order batching and routing in multi-depot AGV-assisted mixed-shelves warehouses

There are four folders in datasets, including distances, sku24, sku360, sku3240. The folder distances include the distance of each two locations (including depot/output station, picking location and shelves/pod) in a json-file, e.g. layout_sku_3240_8.json. In this file, the distance information within the layout of 3240 shelves and 8 depots are shown. The folder sku 24 include following files of the layout with 24 pods (same for the 360 and 3240 pods): 

**layout_sku_24_2.xml** includes all waypoints of the layout of 24 pods and 2 output stations and the path between two waypoints. Furthermore, it also includes the coordinate positions of picking locations (ID, x- and y-coordinates), pod locations, output stations location and the beginning location of cobot / bot. Note that there are more information as needed as listed in this file for further research. 

**orders_10_mean_1x6_sku_24.xml** include the information of 10 orders with average 1.6 order lines (small-line orders) in a layout with 24 pods. We have a, b, and none at the end of each xml, which represent three different order sets. 1.6 can be replaced by 5 if we considered multi-line orders, i.e. average 5 order lines. \
In each xml-file, we have ItemDescription, which shows the properties of items, including color, ID, letter and weight. Furthermore, we have Orders, including the order lines and items. 

**pods_items_dedicated_1.xml** and **pods_items_mixed_shevels_1-x.xml** show the information of the distribution of SKUs per pod. Dedicated means that each pod includes only one SKU while mixed_shelves_x means that one SKU can be spread between 1 and x pods.
Pod_ID; x-coorinate/y-coordinate; color/letter/count;…;
For example:
0;7.3500000000000005/0.65;red/c/16;green/d/19;blue/f/16;red/g/15;blue/h/31;


**24 pods with 2 stations layout**:
![layout](https://user-images.githubusercontent.com/61032543/162757138-cf804594-0423-4312-80a5-d41a87f0e340.png)
**360 pods with 2 stations layout**:
![layout](https://user-images.githubusercontent.com/61032543/162757436-eeb2f9ff-4821-4460-9241-471952914ceb.png)
**360 pods with 4 stations layout**:
![layout - 4](https://user-images.githubusercontent.com/61032543/162757473-b960f27e-67af-4ffc-9358-f43bade3dda0.png)
**3240 pods with 2 stations layout**:
![layout](https://user-images.githubusercontent.com/61032543/162757568-efb5eda0-f959-4ddb-a567-062c98c54b0d.png)
**3240 pods with 4 stations layout**:
![layout_3240_4](https://user-images.githubusercontent.com/61032543/162757614-ea09a803-9884-42c6-ab28-afde02876863.png)
**3240 pods with 8 stations layout**:
![layout_3240_8](https://user-images.githubusercontent.com/61032543/162757637-fbf4a6c1-40ef-45b0-8347-bacc05e56757.png)
