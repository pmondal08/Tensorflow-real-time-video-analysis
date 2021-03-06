# Real-time video analysis with Tensorflow


##Data sources:
Microsoft COCO image caption generation, object segmentation and dataset for training the inception architecture. 

Flickr30k image Dataset for training and testing the generated image captions.

##Tools: 
Tensorflow

Google Protobuf

NumPy

Keras

OpenCV

scikit-image 

## Input/Output
Training the model requires significant GPU computing power. After training the model for some time on my local machine, the results are not that good. There are pre-trained models available on the same Flickr 30k dataset, I tested my input images on one of such [model](https://drive.google.com/file/d/0B5o40yxdA9PqeW4wY0wwZXhrZkE/view) made available by the user Taeksoo Kim [@jazzsaxmafia](https://github.com/jazzsaxmafia).  

###Input

![](https://cloud.githubusercontent.com/assets/16812117/18818788/faeca41a-8348-11e6-8a2c-de4ae38dce4b.jpg)

###Output

Testing the model on the same image multiple times, results in different output each time.

![](https://cloud.githubusercontent.com/assets/16812117/18818772/75147110-8348-11e6-92d4-9bff09fa2bbe.PNG)

![](https://cloud.githubusercontent.com/assets/16812117/18818848/26f287d6-834a-11e6-9cd0-8d66a1e4c2d4.PNG)


As the model is not fully trained, it wrongly predicted university sign-board as a man in blue shirt.



##References:
[1]. Vinyals, Oriol, et al. "Show and Tell: Lessons learned from the 2015 MSCOCO Image Captioning Challenge." (2016).

[2]. He, Kaiming, et al. "Deep residual learning for image recognition." arXiv preprint arXiv:1512.03385 (2015).

[3]. https://github.com/tensorflow/tensorflow

[4]. Donahue, Jeffrey, et al. "Long-term recurrent convolutional networks for visual recognition and description." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2015.

[5]. Cho, Kyunghyun, Aaron Courville, and Yoshua Bengio. "Describing multimedia content using attention-based encoder-decoder networks." IEEE Transactions on Multimedia 17.11 (2015): 1875-1886.

[6].  https://research.googleblog.com/

[7]. https://github.com/tensorflow/models/tree/master/im2txt#a-note-on-hardware-and-training-time

[8]. https://github.com/jazzsaxmafia/show_and_tell.tensorflow

[9]. http://mscoco.org/

[10]. http://shannon.cs.illinois.edu/DenotationGraph/

[11]. Data Reference - https://board.um.umsystem.edu/October%2023%202014%20Board%20of%20Curators%20Meeting/Governance,%20Resources%20and%20Planning/ACTION%201%20-%202014%20Campus%20Master%20Plan%20Update%20-%20UMKC.pdf
