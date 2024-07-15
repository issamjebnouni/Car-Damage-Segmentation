# Car-Damage-Segmentation

During my end-of-studies project on car damage segmentation, we decided to collect our own custom dataset due to the uniqueness of our use case. However, I wanted to share some key insights from my exploration of publicly available datasets.

One of the most prominent datasets I found was CarDD, but it presented several challenges. To streamline our implementation and leverage pretrained models, I needed to choose an appropriate framework. Although Detectron2 is well-known for its comprehensive documentation and debugging tools, I opted for MMDetection. MMDetection offers a larger model zoo with many SOTA models and provides more visualization and evaluation tools, which are crucial for assessing our work.

However, transitioning from MMDetection version 2 to 3 revealed issues. Many tutorials became obsolete, and compatibility problems arose with the mmengine and mmcv libraries. Setting up the environment and configuring models required significant debugging time. After overcoming these hurdles, I created a comprehensive guide to implementing a car damage segmentation model with MMDetection, yielding impressive results. I believe this guide will be valuable for researchers who want to experiment with SOTA models, given the lack of updated MMDetection tutorials.

I wrote a [Medium article](https://medium.com/@issam.jebnouni/guide-to-implement-a-car-damage-segmentation-model-using-mmdetection-8eb039a13190) guiding you through the process.

And you can find a [Kaggle notebook](https://www.kaggle.com/code/issamjebnouni/car-damage-segmentation) containing the detailed implementation and the dataset attached, so you can experiment for yourself.
