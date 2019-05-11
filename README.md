# AWS MIT Workshop

## Set-Up
1. Follow the instructions given by your instructor to log into your AWS Demo Account, and to create an Amazon SageMaker Notebook Instance.
2. Select **Git repositories**, under **Repository** select "Clone a public Git repository to this notebook instance only".
3. Under **Git repository URL** paste `https://github.com/kenstler/aws_ml_workshop.git`.
4. Click **Create Notebook Instance**.

Once your Amazon SageMaker NoteBook Instance is ready, please click **Open Jupyter**.

## Lab 1: AWS CLI & AMI

In this lab, we will walk through examples on how to use AWS CLI to create, list, and terminate Amazon EC2 Instances. We will also learn how to create Amazon Machine Images (AMI) that have all our installed dependencies, so we can quickly create instances from them in the future.

1. Once you're in the Jupyter Console, click on **Lab1** and then **AWS CLI & AMI Lab.ipynb**.
2. Follow the instructions in the notebook.

## Lab 2

In this lab, we will go over up to 4 SageMaker examples, covering:
* 1P algorithms on Amazon SageMaker
* Train custom models using "Bring-your-own-script" and PyTorch
* Distributed training simplified with "Bring-your-own-script", Keras, and Horovod
* Reinforcement learning for Mountain Car with Intel Coach

To access these examples, please go to your Jupyter Notebook Console and:
* Select **SageMaker Examples**
Go through the following examples:
1. **object_detection_recordio_format.ipynb** under **Introduction to Amazon Algorithms**
2. **pytorch_rnn.ipynb** under **Sagemaker Python Sdk**
3. **tensorflow_script_mode_horovod.ipynb** under **Sagemaker Python Sdk**
4. **rl_mountain_car_coach_gymEnv.ipynb** under **Reinforcement Learning**
