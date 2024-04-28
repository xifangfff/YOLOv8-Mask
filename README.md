### Venue Crowd Recognition in Dense Smoke Environment: A Recognition Method Based on Attention Mechanism Fusion Segmentation Instances


Abstract:

The occurrence of fires poses a significant threat to pedestrian safety in densely populated venues, presenting a major challenge in enhancing pedestrian evacuation speed and rescue efficiency. This paper proposes a computer vision approach by augmenting target pedestrian recognition with a Mask branch on top of object detection algorithms, utilizing channel attention mechanisms to enhance target pedestrians in the environment while reducing the weighting of the environment in images. We introduce a YOLOv8-Mask model which effectively enhances pedestrian recognition in hazy scenes typical of fire-smoke environments, facilitating efficient rescue operations for trapped individuals. Finally, comparative experiments conducted on self-collected datasets with five established object detection models demonstrate the superiority, robustness, and effectiveness of our proposed model in crowd recognition under such hazy conditions and real-world scenarios. The research outcomes presented herein contribute to assisting rescue efforts in densely populated venues amidst fire-smoke conditions, thereby providing technological support for the development of resilient cities.

File retrieval

Due to the large size of the files involved in this model, we have uploaded the model to Baidu Cloud for sharing. Our sharing link is: https://pan.baidu.com/s/1mWHnjYymdQTtRRTA6PLfGw The extraction code is: bcaz, you can obtain our model through this link

Used

Our model contains a weight file with the suffix pt, which is improved based on YOLOv8. If you want to use our model to train your dataset, please download Ultratics for use. The download link for Ultratics is: https://github.com/ultralytics/ultralytics In this link, you will be able to download UltraAnalytics, a highly powerful project.
If you want to use our model, you need to place the "YOLOv8 Mask, pt" file we include in the root directory of the Ultratics project, where you can use our model
The method to be used requires the following inputs:

```bash
yolo predict model=YOLOv8-Mask.pt source='You need to test the root directory of the dataset'
```
