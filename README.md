# Zero-Shot-Video-Segmentation-with-Static-Images

Convolutional neural networks have shown exemplary results
in all domains of computer vision, with the availability of large datasets
which are annotated. This method is highly effort taking when it comes
to dealing with annotating videos, pixel wise and using it for training.
With video object segmentation methods becoming more in number and
ubiquitous in most of the light devices such as mobile phones and microcontrollers, it is essential to build a segmentation architecture that does
not rely on temporal continuity on propagation of masks. Existing models with Spatio temporal correlations tend to increase the computational
complexity on light devices. To serve the above-mentioned purpose, we
built a model that does video object segmentation considering each frame
as a static image. We make the model work on smaller datasets with the
transfer learning approach. Our method can be described as a Zero Shot
Video Object Segmentation with Static images using transfer learning

###U-net Architecture 
![Screenshot](./images/U_net.png)

###Performance of U_net
![Screenshot](./images/performance_unet.png)

###Inception ResnetV2 Architecture
![Screenshot](./images/Ins_resnet.png)

###Performance of U_net
![Screenshot](./images/performance_ins_res.png)


By exploiting offline
training with image annotations only, our approach is able to produce accurate
video object segmentation.Different from current popular supervised VOS solutions requiring extensive amounts of elaborately annotated training samples,
our model attains good results with only offline training.

###References:

1. Khoreva, A., Perazzi, F., Benenson, R., Schiele, B., Sorkine-Hornung, A.: Learning
video object segmentation from static images. CoRR abs/1612.02646 (2016), http:
//arxiv.org/abs/1612.02646


2. Lu, X., Wang, W., Shen, J., Tai, Y., Crandall, D.J., Hoi, S.C.H.: Learning video
object segmentation from unlabeled videos. CoRR abs/2003.05020 (2020), https:
//arxiv.org/abs/2003.05020


3. Ronneberger, O., Fischer, P., Brox, T.: U-net: Convolutional networks for biomedical
image segmentation. CoRR abs/1505.04597 (2015), http://arxiv.org/abs/1505.
04597


4. Szegedy, C., Ioffe, S., Vanhoucke, V.: Inception-v4, inception-resnet and the impact
of residual connections on learning. CoRR abs/1602.07261 (2016), http://arxiv.
org/abs/1602.07261

This project was done in colaboration with Mohammed Maqsood
Shaik GowthamKrishna Addluri