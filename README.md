# HAET-2021-competition-baseline-code
This code can be used as a baseline to sumbit a lite training method to the [Hardware Aware Efficient Training ICLR workshop competition](https://haet2021.github.io/cfp). 

The code above contains a training file where a model will be trained and saved, a test file where the trained model will be loaded and tested and an evaluation script that runs training programme during 10 minutes, and then runs test.

# Competition Rules

The competition consists of two steps. An open step where contestants can train and test their methods on a public dataset such as CIFAR10/CIFAR100, and an evaluation step where we will test proposed methods on a nonpublic dataset. Contestants should propose a lite training solution that accelerates the training process while reaching a good accuracy. The evaluation will be performed on a 10 classes nonpublic dataset composed of 32 by 32 RGB 500 training images and 100 testing images per class (it is not CIFAR10 or CIFAR100). Contestants are invited to use CIFAR10/CIFAR100 to test their methods. We provide a code that contains a dataloader, training and test program and a script that stops training after 10 minutes and performs the test.

To evaluate different submissions, we run each code on an Nvidia V100 using a nonpublic dataset during 10 minutes, and then use the training model to classify test dataset. Methods will be classed according to the accuracy they achieve after 10 minutes training. To explain their methods, the authors can either provide a description of the method and the obtained results, or submit a 4 pages paper if they want to present their work at the workshop session as well. Note that submitting the code is mandatory for the competition, and to do so, we invite authors to submit their code as supplementary material. The three best methods will be awarded.


You may contact us on ghouthi.bouklihacene@imt-atlantique.fr\bouklihg@mila.quebec if you need further details.


