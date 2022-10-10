# Eyeglasses Detection Exercise
I created this coding exercise to evaluate applicants for a junior AI engineer position. An excellent junior AI engineer is expected to require 6-8 hours (**a work day**) to finish this exercise. In this project, the applicant will be asked to create a binary eyeglasses detector. This exercise is based on the [CelebA dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html). This dataset includes face attributes, one of these attributes indicates whether the person is wearing eyeglasses or not. This repository includes both a jupyter-notebook coding exercise **eyeglass_detection_excercise.ipynb** and the model solution: **solution.ipynb**.


### Evaluated Skills
This exercise tests the applicant's ability to:
1. Clone and install/set-up a GitHub repository.
2. Go over the documentation of a GitHub repository and use a pre-trained model for inference.
3. Create a custom Pytorch Dataset class for the given task.
4. Build and train a model from scratch.
5. conduct a proper evaluation of the trained model.
6. finish the task in a timely manner.


### Guideline
The applicant is asked to go over the following steps:
1. Install face detector [DSFDDetector](https://github.com/hukkelas/DSFD-Pytorch-Inference).
2. Crop faces using the face detector.
3. Separate faces with eyeglasses and those without eyeglasses using the attributes.
4. Build a train-dataloader and a test-dataloader (with 2 classes: `eyeglasses` `no-eyeglasses`).
5. Build and train the model.
6. Evaluate the model. <br /> **Bonus Steps:**
7. Create visualization of the training (tensorboard is recommended).
8. Run hyperparameter search (grid search).




[PyTorch](https://pytorch.org/) is the preferred framework.

### Evaluation Criteria
Evaluation will be based on:
- Code is functional (it works).
- Time required to solve the task.
- Code organization.
- Solving the bonus tasks.
