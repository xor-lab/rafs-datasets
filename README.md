# rafs-datasets
Datasets for RAFS paper: Formulating and solving integrated order batching and routing in multi-depot AGV-assisted mixed-shelves warehouses

There are four folders, distance, sku24, sku360, sku3240. sku24 means layout with 24 pods, sku360 means layout with 360 pods, sku3240 means layout with 3240 pods. In the distances folders gives the json format files for every layout.


for layout*.xml:
Layout file:
Pods position, Robot beginning position, Stations position, Waypoint etc.
•	N X tier
•	N X pick station
•	N X robots
•	N X pods

for pods_infos.txt:
for example: 184;1.50/19.50;red/r/12;blue/i/6;blue/u/6;green/u/6;red/u/6;green/a/12;blue/m/6;green/m/6;red/m/18;red/s/6;
•	184 means pod number.
•	1.50/19.50 means the pod position, X: 1.50, Y: 19.50, origin of coordinate is in the bottom left corner. 
•	blue/u/6 means there are 6 pieces for the item “character ‘u’ with blue color”.

for distances data in distances folder:
json format data for distances between pods or station to pods or station to station.



24 pods with 2 stations layout:
![layout](https://user-images.githubusercontent.com/61032543/162757138-cf804594-0423-4312-80a5-d41a87f0e340.png)

360 pods with 2 stations layout:
![layout](https://user-images.githubusercontent.com/61032543/162757436-eeb2f9ff-4821-4460-9241-471952914ceb.png)

360 pods with 4 stations layout:
![layout - 4](https://user-images.githubusercontent.com/61032543/162757473-b960f27e-67af-4ffc-9358-f43bade3dda0.png)

3240 pods with 2 stations layout:
![layout](https://user-images.githubusercontent.com/61032543/162757568-efb5eda0-f959-4ddb-a567-062c98c54b0d.png)

3240 pods with 4 stations layout:
![layout_3240_4](https://user-images.githubusercontent.com/61032543/162757614-ea09a803-9884-42c6-ab28-afde02876863.png)

3240 pods with 8 stations layout:
![layout_3240_8](https://user-images.githubusercontent.com/61032543/162757637-fbf4a6c1-40ef-45b0-8347-bacc05e56757.png)
