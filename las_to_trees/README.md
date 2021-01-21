First off, loading a LAS file into R and plotting it is a super easy way to visualize what LiDAR data looks like for an area:
![Point cloud from LAS file](https://imgur.com/73gvnMZ)
It is hard to see much detail in that first image, but you can plot it with various options. Here is classification by type:
![Classified point cloud](https://imgur.com/lnE9Svh)
You can see the red is buildings, green is trees, and the white/blue is ground (I don't know if that is two layers or not).

You can also create CHM rasters, as seen below:
![CHM Raster](https://imgur.com/oyxEZT3)
Taken further, you can segment and isolate the individual trees from the LAS data:
![Tree segmentation](https://imgur.com/hGmVrwC)
And also show the crown spread polygons of each individual tree (coloured by height):
![Crown hulls delineated](https://imgur.com/dVxvGC5)


