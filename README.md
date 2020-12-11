# DL-Paper-List

## Description

A collection of various deep learning architectures, models .  If you are a beginner just entering the field of deep learning , you can start reading from the following papers.

| Model        | Download                                                     | Code                                                         | Dataset     | Top-1 err | Top-5 err | FLOPs | Published in |
| ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ----------- | --------- | --------- | ----- | ------------ |
| AlexNet      | <a href="http://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf">Paper</a> |                                                              | ILSVRC-2012 | 36.7%     | 15.3%     |       | NIPs 2012    |
| VGG          | <a href="https://arxiv.org/pdf/1409.1556.pdf">Paper</a>      |                                                              | ILSVRC-2014 | 25.5%     | 8.0%      |       | ICLR 2015    |
| GoogLeNet    | <a href="https://arxiv.org/pdf/1409.4842.pdf">Paper</a>      |                                                              | ILSVRC-2014 | -         | 6.67%     |       | CVPR 2015    |
| InceptionV2  | <a href="https://arxiv.org/pdf/1502.03167.pdf">Paper</a>     |                                                              | ILSVRC-2014 | 20.1%     | 4.9%      |       | arxiv 2015   |
| ResNet       | <a href="https://arxiv.org/pdf/1512.03385.pdf">Paper</a>     |                                                              | ILSVRC-2015 | 19.38%    | 4.49%     |       | arxiv 2015   |
| InceptionV3  | <a href="https://arxiv.org/pdf/1512.00567.pdf">Paper</a>     |                                                              | ILSVRC 2012 | 17.3%     | 3.5%      |       | CVPR 2016    |
| ResNeXt      | <a href="https://arxiv.org/pdf/1611.05431.pdf">Paper</a>     | <a href="https://github.com/facebookresearch/ResNeXt">Code</a> | ILSVRC 2016 | 17.7%     | 3.7%      |       | CVPR 2017    |
| DenseNet     | <a href="https://arxiv.org/pdf/1608.06993.pdf">Paper</a>     | <a href="https://github.com/liuzhuang13/DenseNet">Code</a>   | ILSVRC 2012 | 20.8%     | 5.29%     |       | CVPR 2017    |
| MobileNetV1  | <a href="https://arxiv.org/pdf/1704.04861.pdf">Paper</a>     | <a href="https://github.com/tensorflow/models/blob/master/research/slim/nets/mobilenet_v1.md">Code</a> | ILSVRC 2012 | 29.4%     | 10.1%     |       | CVPR 2017    |
| ShuffleNetV1 | <a href="https://arxiv.org/pdf/1707.01083.pdf">Paper</a>     | <a href="https://github.com/MG2033/ShuffleNet">Code</a>      | ILSVRC 2016 |           |           |       | arxiv 2017   |
| MobileNetV2  | <a href="https://arxiv.org/pdf/1801.04381.pdf">Paper</a>     | <a href="https://github.com/tensorflow/models/blob/master/research/slim/nets/mobilenet/README.md">Code</a> | ILSVRC      | 25%       | 7.5%      |       | CVPR 2018    |
| SEnet        | <a href="http://openaccess.thecvf.com/content_cvpr_2018/papers/Hu_Squeeze-and-Excitation_Networks_CVPR_2018_paper.pdf">Paper</a> | <a href="https://github.com/hujie-frank/SENet">Code</a>      | ILSVRC 2017 |           |           |       | CVPR 2018    |
| MobileNetV3  | <a href="https://arxiv.org/pdf/1905.02244.pdf">Paper</a>     | <a href="https://github.com/tensorflow/models/blob/master/research/slim/nets/mobilenet/README.md">Code</a> | ILSVRC      |           |           |       | ICCV 2019    |
| EfficientNet | <a href="https://arxiv.org/pdf/1905.11946.pdf">Paper</a>     | <a href="https://github.com/qubvel/efficientnet">Code</a>    | ILSVRC      | 15.6%     | 2.9%      |       | ICML 2019    |
| Res2Net      | <a href="https://arxiv.org/pdf/1904.01169.pdf">Paper</a>     |                                                              |             |           |           |       | CVPR 2019    |



## Object Detection

Description:   There is a paper list of object detection using deep learning.

| Detector        | Download                                                     | Code                                                         | VOC07        | COCO(mAP@.5:0.95) | FPS  | Published In |
| --------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ----------------- | ---- | ------------ |
| R-CNN           | <a href="https://arxiv.org/pdf/1311.2524.pdf">Paper</a>      | <a href="https://github.com/rbgirshick/rcnn">Code</a>        | 58.5         | -                 |      | CVPR14       |
| Fast R-CNN      | <a href="https://arxiv.org/pdf/1504.08083.pdf">Paper</a>     | <a href="https://github.com/rbgirshick/fast-rcnn">Code</a>   | 70.0 (07+12) | 19.7              |      | ICCV15       |
| Faster R-CNN    | <a href="https://papers.nips.cc/paper/5638-faster-r-cnn-towards-real-time-object-detection-with-region-proposal-networks.pdf">Paper</a> | <a href="https://github.com/rbgirshick/py-faster-rcnn">Code</a> | 73.2 (07+12) | 21.9              |      | NIPS  15     |
| YOLO v1         | <a href="https://arxiv.org/pdf/1506.02640.pdf">Paper</a>     | <a href="https://pjreddie.com/darknet/yolo/">Code</a>        | 66.4 (07+12) | -                 |      | CVPR16       |
| SSD             | <a href="https://arxiv.org/pdf/1512.02325.pdf">Paper</a>     | <a href="https://github.com/weiliu89/caffe/tree/ssd">Code</a> | 79.8         |                   |      | ECCV16       |
| YOLOv2          | <a href="https://arxiv.org/pdf/1612.08242">Paper</a>         |                                                              | 78.6         |                   |      | CVPR17       |
| FPN             | <a href="https://arxiv.org/pdf/1612.03144.pdf">Paper</a>     |                                                              |              |                   |      | CVPR17       |
| RetinaNet       | <a href="https://arxiv.org/pdf/1708.02002.pdf">Paper</a>     | <a href="https://github.com/facebookresearch/Detectron">Code</a> |              | 40.8              |      | ICCV17       |
| CascadeRCNN     | <a href="http://www.svcl.ucsd.edu/publications/conference/2018/cvpr/cascade-rcnn.pdf">Paper</a> | <a href="https://github.com/zhaoweicai/cascade-rcnn">Code</a> | 79.6(07+12)  | 42.7              |      | CVPR18       |
| YOLO v3         | <a href="https://pjreddie.com/media/files/papers/YOLOv3.pdf">Paper</a> | <a href="https://pjreddie.com/darknet/yolo/">Code</a>        | -            | 33.0              |      | arXiv18      |
| CornerNet       | <a href="https://arxiv.org/pdf/1808.01244.pdf">Paper</a>     | <a href="https://github.com/princeton-vl/CornerNet">Code</a> |              | 42.2              |      | ECCV18       |
| CenterNet       | <a href="https://arxiv.org/pdf/1904.07850.pdf">Paper</a>     | <a href="https://github.com/xingyizhou/CenterNet">Code</a>   |              | 45.1              |      | arxiv19      |
| FCOS            | <a href="https://arxiv.org/pdf/1904.01355.pdf">Paper</a>     | <a href="https://github.com/tianzhi0549/FCOS">Code</a>       |              | 46.6              |      | ICCV19       |
| TridentNet      |                                                              |                                                              |              | 48.4              |      | ICCV19       |
| OneNet          | <a href="https://arxiv.org/pdf/2012.05780.pdf">Paper</a>     | <a href="https://github.com/PeizeSun/OneNet">Code</a>        |              |                   |      | arXiv20      |
| AutoAssign      | <a href="https://arxiv.org/abs/2007.03496">Paper</a>         | <a href="https://github.com/Megvii-BaseDetection/AutoAssign">Code</a> |              | 52.1              |      |              |
| DeFCN           | <a href="https://arxiv.org/pdf/2012.03544.pdf">Paper</a>     | <a href="https://github.com/Megvii-BaseDetection/DeFCN">Code</a> |              | 41.5              |      |              |
| YOLOv4          | <a href="https://arxiv.org/abs/2004.10934">Paper</a>         | <a href="https://github.com/AlexeyAB/darknet">Code</a>       |              | 43.5              |      | arXiv20      |
| DETR            | <a href="https://scontent-hkg4-2.xx.fbcdn.net/v/t39.8562-6/101177000_245125840263462_1160672288488554496_n.pdf?_nc_cat=104&ccb=2&_nc_sid=ae5e01&_nc_ohc=4No88GPznaEAX-rkbxP&_nc_ht=scontent-hkg4-2.xx&oh=fb906592c8754af844fc4135a267dd20&oe=5FF80AC7">Paper</a> | <a href="https://github.com/facebookresearch/detr">Code</a>  |              | 44.9              |      | ECCV20       |
| Deformable DETR | <a href="https://arxiv.org/pdf/2010.04159.pdf">Paper</a>     | <a href="https://github.com/fundamentalvision/Deformable-DETR">Code</a> |              |                   |      |              |
| SparseR-CNN     | <a href="https://msc.berkeley.edu/research/autonomous-vehicle/sparse_rcnn.pdf">Paper</a> | <a href="https://github.com/PeizeSun/SparseR-CNN">Code</a>   |              | 46.4              |      | arXiv20      |
| CBNet           |                                                              |                                                              |              | 53.3              |      | AAAI20       |
| DetectoRS       | <a href="https://arxiv.org/pdf/2006.02334">Paper</a>         | <a href="https://github.com/joe-siyuan-qiao/DetectoRS">Code</a> |              | 54.7              |      | arXiv20      |
| EfficitentDet   | <a href="https://arxiv.org/pdf/1911.09070.pdf">Paper</a>     | <a href="https://github.com/google/automl/tree/master/efficientdet">Code</a> |              | **55.1**          |      | CVPR20       |

