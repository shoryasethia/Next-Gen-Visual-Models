### Implement the same diffusion model as in the above video.

1. Produce results with 2 sets of hyperparameters - varying learning rate, noising schedule (beta), number of denoising steps.
   Attach loss curves for both trainings. Justify your choice of parameters and comment on how your observations vary/agree with what you expected
2. Produce one sample from each class (10 classes) in the CIFAR-10 dataset

### Instead of starting with complete Gaussian Noise (conventional method), start with a partially noised sample (noisy sample) and denoise it. Do this exercise for a sample that has been noised for:

1. 50 iterations
2. 10 iterations
3. 5 iterations
   Comment on the level to which the model is able to denoise your noisy sample and identify any new features/shapes it has added to the image while denoising it.
