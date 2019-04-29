# FOOD-101

Exercise from https://fellowship.ai/challenge.

**Goal**: train a ResNet50 classifier on the Food-101 dataset which can reach > 85% top-1 accuracy on the validation set.

**Approach**: ResNet50 trained using the fastai library based on PyTorch; used transfer learning, data augmentation, progressive resizing, one-cycle learning, test time augmentation (TTA).
