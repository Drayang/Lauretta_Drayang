## Using TorchReid and Yolo model for real time person reidentification

I implemented “TorchReid”, which is a deep learning person re-identification approach in PyTorch developed by Zhou Kai Yang and his team for ICCV’19, [Omni-Scale Feature Learning for Person Re-Identification ](https://arxiv.org/abs/1905.00953). Torchreid is a library for deep-learning person re-identification, written in [PyTorch ](https://pytorch.org/).

Besides, I tried to implement YOLOv3 for object detection to perform a complete real time person re-identification application. The YOLOv3 object detection is refer to this [YOLO Object Detection with OpenCV](https://github.com/yash42828/YOLO-object-detection-with-OpenCV).

## Discussion
The complete discussion on code and result is written in the [Discussion.pdf](https://github.com/Drayang/Lauretta_Drayang/blob/master/Discussion.pdf).

## Citation

If you use this code or the models in your research, please give credit to the following papers:

.. code-block:: bash

    @article{torchreid,
      title={Torchreid: A Library for Deep Learning Person Re-Identification in Pytorch},
      author={Zhou, Kaiyang and Xiang, Tao},
      journal={arXiv preprint arXiv:1910.10093},
      year={2019}
    }
    
    @inproceedings{zhou2019osnet,
      title={Omni-Scale Feature Learning for Person Re-Identification},
      author={Zhou, Kaiyang and Yang, Yongxin and Cavallaro, Andrea and Xiang, Tao},
      booktitle={ICCV},
      year={2019}
    }

    @article{zhou2021osnet,
      title={Learning Generalisable Omni-Scale Representations for Person Re-Identification},
      author={Zhou, Kaiyang and Yang, Yongxin and Cavallaro, Andrea and Xiang, Tao},
      journal={TPAMI},
      year={2021}
    }
