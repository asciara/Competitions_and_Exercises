Exercise from https://fellowship.ai/challenge.

**Goal**: create an automatic portrait segmentation model and apply it to the CelebA dataset.

**Approach**: U-Net segmentation model trained on an auxiliary portrait segmentation dataset (from the Paper "Deep Automatic Portrait Matting", available at this [link](http://xiaoyongshen.me/webpages/webpage_automatting/)) using the fastai library based on PyTorch; 

**Final result**: 97.6% Intersection-over-Union accuracy on the portrait segmentation dataset validation set; see notebook for results on CelebA dataset.
