Important surfaces:
1) Head Dataset
There are 4 important surfaces in this dataset, the first one is the skin of the head at the most outer surface of the head volume, the second surface is the surface represents the internal space and ear of the model. The third surface is the surface represents the skull of the head and the last surface represents the teeth on the skull of the head.

2) Teapot Dataset:
There are 4 important surfaces in this dataset, the first one is the outer surface of the teapot, the second surface is the surface represents the inner surface of the model including the lid and the spout of the teapot. The third surface is the surface represents the container of the content in the teapot whereas the last surface represents the content inside the teapot, which is a lobster.

3) Frog2ci Dataset:
There are 2 important surfaces in this data set, the first one is the skin of the frog, and the second surface is the surface represents the skin texture of the frog model.

4) MRbrain Dataset:
There are 3 important surfaces in this dataset, the first one is the skin of the face. The second surface is the surface represents the outer surface of the brain which outline the brain. The third surface is the surface represents the internal layers of the brain such as medula and corpus callosum.

User Interactions:
1) Key 0 to 9
Key 0 to 9 are used to select the point in the color or opacity transfer function to adjust the position of the point in the function. These keys are only enabled in using ray marching method and will only functional when the key pressed by the user is within the number of points in the transfer function. The error statement if the number of point selected is out of bound in the cli.

2) Key /
The key "/" is used to toggle between adjusting ray step and adjusting points in transfer function when the volume is rendered in ray marching. This will change the behaviour of other keys, which are "+" and "-" keys when different mode is used.

3) Key .
The key "." is used to toggle between adjusting points in color transfer function and adjusting points in opacity transfer function. This will allow the users to switch which transfer function they are going to adjust the points.

4) Key "+"/"=" and Key "-"/"_"
There will be three behaviours for these keys. These keys will only functional when the volume is rendered under ray marching method. 

The first behaviour is occured when the user select the adjusting ray step function by using key "/". When the adjusting ray step function is selected, the key "+"/"=" will be used to increase the ray step whereas key "-"/"_" will be used to decrease the ray step.

The second and third behaviour is occured when the user select the adjusting points in transfer function by using key "/". The second behaviour is occured when the adjusting points in transfer function is selected and the adjusting points in color transfer function is selected by using key ".". In this case, the key "+"/"=" will be used to increase the position of the point selected in color transfer function whereas key "-"/"_" will be used to decrease the position of the point selected. The third behaviour is occured when adjusting points in opacity transfer function is selected instead of the color transfer function. Similarly, the key "+"/"=" will be used to increase the position of the point selected in opacity transfer function whereas key "-"/"_" will be used to decrease the position of the point selected.

5) Key "i" and "I"
These keys will only functional when the volume is rendered under iso surface method. The key "i" will be used to decrease the iso value used to extract the first iso surface by 100 whereas the key "I" is used to increase the iso value by 100.

6) Key "k" and "K"
These keys will only functional when the volume is rendered under iso surface method. The key "k" will be used to decrease the iso value used to extract the second iso surface by 100 whereas the key "K" is used to increase the iso value by 100.

7) Key "s"
The key "s" is used to alternate between two render modes, which are ray marching and iso surface methods. The key "s" allows the users to toggle between the methods used to render the volume and display the color transfer function used in each method by using a scalar widget.

Discussion:
A large number of surfaces make the image hard to comprehend as this causing difficulty for viewer to distinguish each individual surface and their relationship, which lead to confusing representation. Besides, the large number of surfaces causing surfaces are having more tendency to overlap with each other, which lead to confusion in identifying the shape of each individual surface. Another problem related with large number of surfaces which making image hard to comprehend is due to the limitations of human perception, causing the region of interest in the volume rendered hard to be identified.