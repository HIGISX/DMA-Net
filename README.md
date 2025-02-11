# DMA-Net
DMA-Net: Dynamic Morphology-Aware Segmentation Network for Remote Sensing Images  

The objective of semantic segmentation is to categorize each pixel in a remote sensing image. Given the considerable size of high-resolution images and the limitations of computing resources, it is common practice to divide them into multiple sub-images during the data preprocessing stage. This necessitates that the segmentation model possess robust capabilities for capturing both local and global information. The deployment of lightweight remote sensing segmentation models is advantageous due to their ease of implementation and rapid computation speeds, which facilitate real-time target recognition and tracking in video stream segmentation scenarios. In this study, we propose the Dynamic Morphology-Aware Segmentation Network (DMA-Net), which employs the Multi-Axis Vision Transformer (MaxViT) as an encoder. MaxViT efficiently captures both local and global information through its unique multi-axis self-attention mechanism, thereby facilitating improved scalability and parallelism. Additionally, we introduce a novel decoder, the Hierarchy Attention Decoder , which leverages Hierarchy Convolution Groups to accurately capture detailed features in remote sensing images and precisely restore missing details in feature maps. Moreover, DMA-Net incorporates the Squeeze-Extraction-Cascade-Bridge to bridge the semantic gap between the encoder and decoder. Finally, DMA-Net represents an advanced network, achieving Dice coefficient scores of 76.11\% and 76.03\% on the Potsdam and Vaihingen datasets, respectively.


![f1](https://github.com/user-attachments/assets/ef0eb989-86e3-4949-860d-9457a7cf6e73)


![f3](https://github.com/user-attachments/assets/a4d55de0-5dfe-4f92-a111-af30aa5f143f)


![f4](https://github.com/user-attachments/assets/4c175c22-1a68-41bc-bc13-dffdfca115b0)


![f5](https://github.com/user-attachments/assets/caa9fa16-4151-428e-a271-21e0c8892f69)


![f6](https://github.com/user-attachments/assets/49e0dfaf-cf95-46f8-ae1b-f3039dd694ae)


![f8](https://github.com/user-attachments/assets/da0a4547-e28d-476b-b1ff-4ea15a1a6107)


![f9](https://github.com/user-attachments/assets/05ab727a-f4b1-42d5-8d83-6b38aaed409b)


![f10](https://github.com/user-attachments/assets/ed69ff46-8903-4178-a7d1-0e7058c8783f)


![f15](https://github.com/user-attachments/assets/48514e41-1250-417d-b3e0-cbf5efcef2c9)
