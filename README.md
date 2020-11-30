#### Assignment 7: Deep learning with TensorFlow

##### Due: Dec 11, at 11:59pm.

####70 points.

In this assignment, you'll get some exposure to setting up and solving basic deep learning problems using TensorFlow. This assignment is less about writing your own code and more about working through tutorials, figuring out how to get things running, and making modifications. Please prepare a short document, as a PDF, that describes the results of each experiment.

TensorFlow can be run completely within the browser using CoLab. This is ok for small problems, but you may find that you want to run the code locally (or in the cloud) for greater efficiency.

For submission, please add either Python files or a Jupyter notebook to your repository in this directory. 
<ol>
<li> 20 points. Basics of TensorFlow. To begin, work through the Basic image classification tutorial here:
(https://www.tensorflow.org/tutorials/keras/classification)

a. Replace the Fashion dataset with the Digits Classification dataset. (https://keras.io/api/datasets/mnist/). Retrain your network and compare the performance on this dataset. Do you notice any anomalies? Does the change in training set affect performance?

b. Add a second fully-connected Dense layer.  How does that change your network's performance? How does it affect the training time?
</li>
<li> 20 points. Next, work through the basic text classification tutorial here:
https://www.tensorflow.org/tutorials/keras/text_classification

Then, complete the exercise at the bottom to run on StackOverflow.

How does this approach to text classification compare to the others we've studied, such as Naive Bayes or cosine similarity? How might you integrate some of the ideas from Assignment 3 (NTLK) into this net?
</li>
<li> 30 points. Work through the CNN tutorial here: 
https://www.tensorflow.org/tutorials/images/cnn

This should produce approximately 70% accuracy on the CIFAR10 dataset.

Use some of the techniques in the image classification tutorial (https://www.tensorflow.org/tutorials/images/classification) to try to improve your performance. Describe the  changes you implemented, and any effects they had.
</li>
</ol>

<b>Bonus task (20 points)</b>: You may apply the score from this to either a previous assignment or to the final exam. (Please indicate in the assignment which one you prefer.)

a. Work through the Deep Q-network tutorial. 
https://www.tensorflow.org/agents/tutorials/1_dqn_tutorial

Modify this code to solve one of the Atari games provided as part of the Gym package.  (there are many examples of this on the web to draw from.) Show how your network performs by preparing a short video of it playing the game. 
