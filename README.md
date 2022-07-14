# **Active Fire Detection using VIIRS Data**

#### 01.11.2021

### **Data Source:** Images from the VIIRS instrument onboard the Suomi-NPP satellite from California on 2020-08-20 and 2020-08-21
### **Spectral Band:** MWIR (M13) Band

#### **Workflow** 

- Step 0: Exploratory Data Analysis
- Step 1: Data Preprocessing and Transformation
- Step 2. Filtering thermal anomaly for hotspot detection **(Otsu's method)**
- Step 3: Clustering of fire hotspots **(DBSCAN Clustering Algorithm)**
- Step 4: Vector generation **(Convex Hull Algorithms)**

Output: 
1) Jupyter notebook for the full workflow
2) A CSV file on coordinates of the fire hotspots detected
3) A geojson file storing the cluster polygons 

<br>

![alt text](https://github.com/pinkychow1010/machine-learning-project/blob/main/image/fire-cluster.jpg)
