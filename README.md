# HAET-2021-competition-baseline-code
This code can be used as a baseline to sumbit a lite training method to the [Hardware Aware Efficient Training ICLR workshop competition](https://haet2021.github.io/cfp). 

The code above contains a training file where a model will be trained and saved and a test file where the trained model will be loaded and tested.

## Competition

In parallel with the workshop, we organize a competition. It is not required to participate in the competition to have a paper accepted at the workshop.

# Main Guidelines

The aim of the competition is to achieve the best possible accuracy in a classification task given a limited training time. The best three teams will receive awards and will be invited to present their solution during the workshop.

In more details, the training will be performed on an Nvidia V100 GPU running with an Intel(R) Xeon(R) Gold 6230 CPU @ 2.10GHz processor, with 12GB of memory, with an allowed training time of 10 minutes.

The competition will be preceded by an open trial phase where participants can stress their methods using a publicly available dataset. But the final dataset used for ranking the submissions will remain secret.

To participate, the candidates must send a pdf describing their method with their code as supplementary material (more details in the next section). The description can be short (1 page is enough).

# Details and important dates

During the trial phase, participants can download all needed code from [here](https://github.com/eghouti/HAET-2021-competition-baseline-code). For this phase, contestants can use the provided code and should try to achieve the best possible accuracy using limited training time. 

Once the participants have their submission ready, they can submit it using the [CMT](https://cmt3.research.microsoft.com/HAET2021/Submission/Manage) link. Before the workshop, submissions will be evaluated using a different dataset (unknown to the participants). The submissions will be evaluated by running the code for a duration of 10 minutes. The task consists in classifying 10 classes with inputs made of 32 by 32 RGB images. 500 inputs per class are available during training and 100 per class for evaluation.

As the purpose of the competition is to evaluate the ability to quickly train systems, it is forbidden to rely on pretrained models or additional data. Ranked submissions will be checked and discarded if they do so.

Note that during evaluation, we will kill the running process after 10 minutes of training. So participants are advised to save their model regularly to avoid missing the deadline.

Methods will be ranked according to the accuracy they achieve after 10 minutes of training.

# Dates

- Competition submission deadline: 1 March 2021.
- Evaluations will be performed by: 1 April 2021.
- Workshop: 8 May 2021.


Ranking for the best teams will be displayed online. The best 3 teams will be invited to present their solution during the workshop (few minutes talk) and will receive an award.



You may contact us on ghouthi.bouklihacene@imt-atlantique.fr\bouklihg@mila.quebec if you need further details.


