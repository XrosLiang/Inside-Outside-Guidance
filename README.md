# Inside-Outside-Guidance (IOG)
This project hosts the code for the IOG algorithms for interactive segmentation.
> [Interactive Object Segmentation with Inside-Outside Guidance](http://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_Interactive_Object_Segmentation_With_Inside-Outside_Guidance_CVPR_2020_paper.pdf)  
> Shiyin Zhang, Jun Hao Liew, Yunchao Wei, Shikui Wei1, Yao Zhao
The code will be released soon. Please stay tuned.
### Abstract
This paper explores how to harvest precise object segmentation masks while minimizing the human interaction cost. To achieve this, we propose an Inside-Outside Guidance (IOG) approach in this work. Concretely, we leverage an inside point that is clicked near the object center and two outside points at the symmetrical corner locations (top-left and bottom-right or top-right and bottom-left) of a tight bounding box that encloses the target object. This results in a total of one foreground click and four background clicks for segmentation. Our IOG not only achieves state-of-the-art performance on several popular benchmarks, but also demonstrates strong generalization capability across different domains such as street scenes, aerial imagery and medical images, without fine-tuning. In addition, we also propose a simple two-stage solution that enables our IOG to produce high quality instance segmentation masks from existing datasets with off-the-shelf bounding boxes such as ImageNet and Open Images, demonstrating the superiority of our IOG as an annotation tool.
![img](https://github.com/shiyinzhang/Inside-Outside-Guidance/blob/master/ims/ims.jpg "img")
### Dataset
With the annotated bounding boxes (∼0.615M) of ILSVRCLOC, we apply our IOG to collect their pixel-level annotations, named Pixel-ImageNet, which are publicly available at https://github.com/shiyinzhang/Pixel-ImageNet.
