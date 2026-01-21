# Pioneering-Video-Semantic-Segmentation-with-Light-Field-Imaging-and-Spatial-Angular-Temporal-Fusion

<img width="1387" height="757" alt="image" src="https://github.com/user-attachments/assets/eda7aa02-6ff9-4af9-a7cb-e800ee2c2c51" />


Abstract

Video semantic segmentation aims to assign a semantic label to each pixel in a video by jointly exploiting spatial context and temporal coherence, and it is essential for applications such as autonomous perception and intelligent surveillance. However, conventional RGB videos lack plenoptic cues, making segmentation unreliable in visually complex conditions, including occlusion, low-light environments, and transparent surfaces. Light field imaging captures both spatial and angular information via a micro-lens array, providing multi-view geometric cues that can enhance scene representation and improve segmentation robustness. Motivated by these advantages, we investigate light field video semantic segmentation and propose the Light Field Spatial-Angular Complementary Network (LFCNet) for precise and efficient segmentation under challenging visual settings. LFCNet first employs an efficient pooling strategy to extract multi-scale macro-pixel spatial context features, and then introduces the Angular Modeling Module (AMM) and Context Change Module (CCM) to capture angular cues and handle view-dependent contextual variations. Furthermore, we design a Temporal-Channel Correlation Module (TCCM) to enhance temporal feature consistency by selectively refining channel-wise representations across frames. To support training and evaluation, we construct a light field video dataset based on macro-pixel representations as a benchmark for this task. Extensive experiments on four datasets demonstrate that LFCNet achieves superior segmentation accuracy and competitive efficiency.
Results 

Results

<img width="671" height="262" alt="image" src="https://github.com/user-attachments/assets/074bfe3e-bd2d-4f3a-a38a-4e9a1b093507" />

Installation

python3.7 CUDA 10.1 pytorch 1.7.1 pip install opencv-python 4.5.1.48

the code will be relased

This manuscript is under review.

Contact

Any questions, please contact the email at jiachen@email.tjut.edu.cn or chenjia@ieee.org
