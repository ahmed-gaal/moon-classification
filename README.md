# Moon Classification Case Study using Amazon AWS SageMaker

# Introduction


In this project, we will build and deploy a **custom model** in SageMaker.
Specifically, we'll define and train a custom, PyTorch neural network to
create a binary classifier for data that is separated into two classes; the
data looks like two moon shapes when it is displayed, and is often referred
to as **moon data**.

The machine learning workflow will be contained in the notebook, while
project utility modules will be contained in the source folder.

The project notebook will be broken down into a few steps:
*  Generating the moon data
*  Loading it into an S3 bucket
*  Defining a PyTorch binary classifier
*  Completing a training script
*  Training and deploying the custom model
*  Evaluating its performance


---