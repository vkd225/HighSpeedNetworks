
Project Review
=====================================================


## Overview

1) Briefly summarize the experiment in this project.
The experiment is designed to compare and contrast the performance of TCP and UDT (UDP based Data Transfer) by taking into account the metrics,
namely, throughput, bandwidth and packet drop. The project is carried out in three parts:
    Part 1: TCP vs. UDP for different bandwidth capacities of a link, in the presence and absence of link delay and loss.
    Part 2: TCP vs UDP in the case of concurrent flows
    Part 3: FTP and UDT Comparison.
The performance is compared for each metric and plotted on rstudio and a conclusion is obtained for each metric.


2) Does the project generally follow the guidelines and parameters we have
learned in class?

Yes, the project follows the guidelines and parameters learnt in the class.


## Experiment design

1) What is the goal of this experiment? Is it a focused, specific goal?
Is it useful and likely to have interesting results?

The goal of the experiment is,

The goal of the experiment is to compare and contrast the performance of TCP and UDT (UDP based Data Transfer) by taking into account the metrics,
namely, throughput, bandwidth and packet drop. The performance of TCP and UDT is compared for each and every metric based on a graph plot generated
on rstudio and an appropriate conclusion can be obtained for each metric.

The goal is very much specific and focused. It could have been better if they did mention the range of the parameters.
Overall it’s a very good goal.

2) Are the metric(s) and parameters chosen appropriate for this
experiment goal? Does the experiment design clearly support the experiment goal?

the metrics and parameters chosen are appropriate.
the metrics include:
    1. Throughput
    2. Bandwidth

the parameters include:
    1. Delay of 50ms
    2. Bandwidth of 100Mb/s, 500Mb/s and 1000Mb/s
    3. Packet loss of 0.1%

Bandwidth is mentioned both as a parameter and a metric.
But bandwidth is only used a parameter to calculate the throughput.

regarding the delay and loss, they considerations made are:
    1. no packet loss and no delay
    2. packet loss and no delay
    3. no packet loss and delay
But they do not consider a case where there is both packet loss as well as delay.
Considering this case would have made the results more interesting.

Also, they do a data transfer comparison of FTP vs UDT. It is mentioned in the report that this
is done inorder to do a bandwidth utilization comparison. But only one case is considered where
there is a bandwidth of 100M without any loss or delay.
More trails were needed to make a conclusion.

3) Is the experiment well designed to obtain maximum information with the
minimum number of trials?

The experiment has a lot of trials. All in all there are around 30 trials required with
a considerable amount of changes between them.
The experiment design requires that many trails due to the parameters and ranges chosen.

4) Are the metrics selected for study the *right* metrics? Are they clear,
unambiguous, and likely to lead to correct conclusions? Are there other
metrics that might have been better suited for this experiment?

The metric they have considered is the throughput. (even though the mention bandwidth as a metric)
Since they are measuring TCP vs UDP, throughput is a very good metric.
They could have considered Data transfer rate as a metric, the result would be more appealing.

5) Are the parameters of the experiment meaningful? Are the ranges
over which parameters vary meaningful and representative?

The parameters chosen are meaningful.

But, in terms of range, the parameters packet loss and delay should have been varied.
they have considered only 2 cases for each.
Also they have not considered one important scenario when there is both packet loss and delay.

6) Have the authors sufficiently addressed the possibility of interactions
between parameters?

Yes, the authors sufficiently address the possibility of interaction between parameters.
they have measured throughput by varying the parameters appropriately.


7) Are comparisons made reasonably? Is the baseline selected for comparison appropriate
and realistic?

Yes, the comparsions are reasonable. they have measured throughput with varying bandwidth,
packet loss rate and delay.


## Communicating results


1) Do the authors report the quantitative results of their experiment?

Yes, authors report the throughput performance of the experiment.

2) Is there information given about the variation and/or distribution of
experimental results?

The variation and distribution is specified. The exact range is specified.

3) Do the authors practice *data integrity* - telling the truth about their data,
avoiding ratio games and other practices to artificially make their results seem better?

Yes, the author practices data integrity. Correct and necessary information is provided
in a very clear way. No false information is provided.

4) Is the data presented in a clear and effective way? If the data is presented in
graphical form, is the type of graph selected appropriate for the "story" that
the data is telling?

The result is communicated in an effective way.
The graphs are appropriate and supplement what the data reads.
The choice of the graph type also makes their more lucid and straight forward.

5) Are the conclusions drawn by the authors sufficiently supported by the
experiment results?

Yes, the conclusions drawn by the authors sufficiently supported by the experimental results.

## Reproducible research


1) Did the authors include instructions for reproducing the experiment in 3 ways (Raw data -> Results,
Existing experiment setup -> Data, and Set up experiment)? Are the instructions clear
and easy to understand?

1. Raw data -> Results: The raw data and the results were provided by the authors.
2. Existing experiment setup -> Data: No guest login is being provided to their resources.  
3. Set up experiment -> the RSpec file is provided to reserve the resources and conduct the experiments.
the instructions given are also very clear. Although,
The order in which the instructions were given for the experiment to be conducted should have been better.

2) Were you able to successfully produce experiment results?

Yes, the experiment was successfully reproduced.

3) How long did it take you to run this experiment, from start to finish?

the experiment took around 5 hours from start to finish, including the plots.

4) Did you need to make any changes or do any additional steps beyond the documentation in order to successfully complete this experiment? Describe *in detail*. How long did these extra steps or changes take to figure out?

No additional steps were required. Although it took some time to understand the instructions, as they were not well ordered.

5) In the [lecture on reproducible experiments](http://witestlab.poly.edu/~ffund/el6383/files/Reproducible+experiments.pdf), we mentioned six degrees of reproducibility. How would you characterize this experiment - where does it fall on the six degrees of reproducibility?

4: The results can be easily reproduced by an independent researcher with at most 15 minutes of user effort, requiring some proprietary source packages.
The experiment is very simple. I could not give it a 5 only because of the time required. even though, it is easy to reproduce the experiment it is quite lengthy.


## Other comments to authors

Please write any other comments that you think might help the authors
of this project improve their experiment.

I feel that they should have considered the case in which both Delay and Loss were present. That would have
given more interesting result. Without the trial, it feels incomplete.
Also, FTP vs UDT transfer is conducted for one trial. It required more trials, with combinations of delay and loss trials.
