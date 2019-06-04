Exercise from https://fellowship.ai/challenge.

**Goal**: create an automatic portrait segmentation model and apply it to the CelebA dataset.

**Approach**: U-Net segmentation model trained on an auxiliary portrait segmentation dataset () using the fastai library based on PyTorch; 

**Final result**: 97.6% Intersection-over-Union accuracy on the portrait segmentation dataset validation set; see notebook for results on CelebA dataset.
