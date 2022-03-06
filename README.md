# resisc45
RESISC45 dataset is a publicly available benchmark for Remote Sensing Image Scene Classification (RESISC), created by Northwestern Polytechnical University (NWPU). This dataset contains 31,500 images, covering 45 scene classes with 700 images in each class.

## About Data 

* [orginal image]:(https://github.com/MegaCreater/resisc45/blob/main/watermarks.zip): Contains orginal images (1400 images) of airplane and airport class from [RESISC45](http://www.escience.cn/people/JunweiHan/NWPU-RESISC45.html) dataset. 
* [quantize images](https://github.com/MegaCreater/resisc45/blob/main/qWatermarks.zip): Contains grayscaled (1400 images of size 128x128) quantize (to 64 values) images of airplane and airport class from [RESISC45](http://www.escience.cn/people/JunweiHan/NWPU-RESISC45.html) dataset. 

## About Orginal Data 
Homepage: http://www.escience.cn/people/JunweiHan/NWPU-RESISC45.html

Source code: [tfds.image_classification.Resisc45](https://github.com/tensorflow/datasets/tree/master/tensorflow_datasets/image_classification/resisc45.py)

Versions:

3.0.0 (default): No release notes.
Download size: Unknown size

Dataset size: Unknown size

Manual download instructions: This dataset requires you to download the source data manually into download_config.manual_dir (defaults to ~/tensorflow_datasets/downloads/manual/):
Dataset can be downloaded from OneDrive: https://1drv.ms/u/s!AmgKYzARBl5ca3HNaHIlzp_IXjs After downloading the rar file, please extract it to the manual_dir.

Auto-cached [(documentation)](https://www.tensorflow.org/datasets/performances#auto-caching)

For More Look: https://www.tensorflow.org/datasets/catalog/resisc45 
