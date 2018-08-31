# semantic_segmentation

Information regarding semantic segmentation in Autonomous Driving 

Here few data labeling tools that helps to label the data for semantic segmentation.

**Data Labeling Tools**

*	[Labelbox](https://github.com/Labelbox/Labelbox)
*	[Labelme](http://labelme.csail.mit.edu/Release3.0/)
*	[more....](https://en.wikipedia.org/wiki/List_of_manual_image_annotation_tools)

There are few pixel wise annotated labeled datasets are avilable publicly.

**Publicly available datasets for urban driving scenes (Autonomous Driving)**

|            |Number of Labelled Images|	Classes |	Multiple Cities |	Environment |
| --- | --- | --- | --- | --- |
|[KITTI](http://arxiv.org/abs/1708.01566)       |	200|	34|	No|	Daylight|
|[Cityscapes](http://arxiv.org/abs/1604.01685)  |	3478|	34|	Yes|	Daylight|
|[Mapillary](https://research.mapillary.com/img/publications/ICCV17a.pdf)   |	20k|	66|	Yes|	Daylight, rain, snow, fog, haze, dawn, dusk and night|
|[Apollo Scape](http://arxiv.org/abs/1803.06184)|	147k|	36|	No|	Daylight, snow, rain, foggy|
|[BDD100K](http://arxiv.org/abs/1805.04687)     |	8000|	19|	Yes|	Daylight, rain, snow, fog, haze, dawn, dusk and night|

For detailed information https://autonomous-driving.org/2018/07/15/semantic-segmentation-datasets-for-urban-driving-scenes/

**Pre-trained semantic segmentation network on the Cityscape dataset**

* ICnet - https://github.com/hellochick/semantic-segmentation-tensorflow
* DeepLab - https://github.com/tensorflow/models
* PSPNet - https://github.com/Vladkryvoruchko/PSPNet-Keras-tensorflow
* DilatedNet - https://github.com/ndrplz/dilation-tensorflow
