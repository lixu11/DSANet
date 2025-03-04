# DSANet:Deep Surrounding-Aware Network for Concealed Object Detection via Cross-Refinement Mirror Strategy
"Peng Chen","Xu Li" and "Xiaosheng Yu"

Abstract—Camouflaged objects commonly exhibit a striking visual resemblance to their surroundings, causing standard RGB images to be confounded by background, texture, and color variations. This often yields incomplete or absent target segmentation, thereby degrading overall accuracy. To address this issue, we present a Deep Surrounding-Awareness Mirror Network (DSANet) for camouflaged object detection, leveraging depth information to expose objects incongruent with their environment and thus facilitate more accurate localization.First, a Convolutional Spatial Gating Module processes batched RGB and depth inputs, suppressing extraneous background noise while isolating fine-grained segmentation and structural features, and unifying channel representation. Subsequently, a Deep Surrounding-Awareness Localization Module and a Contour-Guided Integrity Aggregation Module collaboratively refine and merge multi-level features—focusing on the global form of camouflaged objects while iteratively enhancing segmentation detail. Finally, a Guided Residual Channel Attention Module further refines low-layer structural cues. Extensive experiments on ten challenging benchmark datasets demonstrate the superior performance of our method across four widely used evaluation metrics, outperforming 33 state-of-the-art methods. The results further demonstrate the versatility of our model. 

**Qualitative Comparison**

![图8](https://github.com/user-attachments/assets/22d03036-f842-415f-bc84-951bf601a0bb)
**Fig 8**


![1-9](https://github.com/user-attachments/assets/4c1496fb-1bee-4cf6-ae24-eebf1b4ba25e)

**Fig 9**

![10](https://github.com/user-attachments/assets/69841bda-6f25-4711-89ff-444486fb0c36)

**Fig 10**
