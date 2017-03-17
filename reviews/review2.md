
Project Review
=====================================================

## Overview

1) Briefly summarize the experiment in this project.
The topic is related to Data Transfer in TCP and UDP. The goal of the experiment
is to compare and contrast the performance of TCP and UDT (UDP based Data Transfer)
by taking into account the metrics, namely, throughput, bandwidth and packet drop.
The performance of TCP and UDT is compared for each and every metric based on a graph
plot generated on rstudio and an appropriate conclusion can be obtained for each metric.

2) Does the project generally follow the guidelines and parameters we have
learned in class?
Yes, this project is not quite difficult and it can generally follow the guidelines
and parameters we have learned in class.  

## Experiment design

1) What is the goal of this experiment? Is it a focused, specific goal?
Is it useful and likely to have interesting results?

The goal of this experiment is to compare the performance of TCP and UDT
(UDP based Data Transfer) by taking into account the metrics.
It is a focused, specific goal.It is also useful and likely to have interesting
results. The performance of TCP and UDT is compared for every metric based
on a graph plot generated on rstudio. An appropriate conclusion can be obtained
for each metric.

2) Are the metric(s) and parameters chosen appropriate for this
experiment goal? Does the experiment design clearly support the experiment goal?

Yes, the metrics are throughput and bandwidth. The parameters to be varied are
delay, packet drop rate and bandwidth. The range in which they will be varied are:
delay in the range of 0 to 50ms , packet drop rate in the range of 0 to 0.01 and
Bandwidth in th range of 10Mbps to 1Gbps. For this experiment goal the metrics and
parameters are chosen appropriate.
Yes, the experiment design clearly support the experiment goal. The services they
study are "TCP based file transfer", "UDP based data transfer", "Bandwidth comparision
under different network conditions", "Bandwidth utilization in concurrent flows for
TCP and UDP". Then the project is carried out in three parts: First, TCP vs. UDP for
different bandwidth capacities of a link, in the presence and absence of link delay
and loss. Second, TCP vs UDP in the case of concurrent flows. Third, FTP and UDT Comparison.

3) Is the experiment well designed to obtain maximum information with the
minimum number of trials?
Yes, this project is carried out in three parts: First, TCP vs. UDP for different bandwidth
capacities of a link, in the presence and absence of link delay and loss. Second, TCP vs UDP
in the case of concurrent flows. Third, FTP and UDT Comparison. The experiment is well designed
to obtain maximum information with the minimum number of trials.

4) Are the metrics selected for study the *right* metrics? Are they clear,
unambiguous, and likely to lead to correct conclusions? Are there other
metrics that might have been better suited for this experiment?
The metrics that be measured are Throughput and Bandwidth. They are clear and likely to lead to
correct conclusions.

5) Are the parameters of the experiment meaningful? Are the ranges
over which parameters vary meaningful and representative?
The parameters to be varied are delay, packet drop rate and bandwidth. The parameters of this experiment
are meaningful.
The ranges over which they will be varied are: delay in the range of 0 to 50ms,
packet drop rate in the range of 0 to 0.01 and Bandwidth in th range of 10Mbps to 1Gbps. They are meaningful
and representative.

6) Have the authors sufficiently addressed the possibility of interactions
between parameters?
They use Rstudio to plot the throughput and time for both TCP and UDP, to observe any interactions between
the parameters. But I don't think the authors have sufficiently addressed the possibility of interactions.
They can explain more specifically about the possibility of interactions between parameters.

7) Are comparisons made reasonably? Is the baseline selected for comparison appropriate
and realistic?
The comparisions are made reasonably but there is no baseline selected for compatison appropriate and realistic.

## Communicating results


1) Do the authors report the quantitative results of their experiment?
Yes. They use graphs to report the quantitative results of their experiment.

2) Is there information given about the variation and/or distribution of
experimental results?
Yes. They use box plots and histogram to show the experimental results.

3) Do the authors practice *data integrity* - telling the truth about their data,
avoiding ratio games and other practices to artificially make their results seem better?
Yes. They tell the truth about their data avoiding ratio games and other practices to
arificially make their results semm better. But some graph lacks of units.

4) Is the data presented in a clear and effective way? If the data is presented in
graphical form, is the type of graph selected appropriate for the "story" that
the data is telling?
The data is presented in a clear and effective way and the type of graph is selected appropriate.
They select box plots and histogram to show the experimental results. I think it could be better
if the units can be more precise.

5) Are the conclusions drawn by the authors sufficiently supported by the
experiment results?
Yes. Obviously, the conclusions are sufficiently supported by the experiment results.

## Reproducible research



1) Did the authors include instructions for reproducing the experiment in 3 ways (Raw data -> Results,
Existing experiment setup -> Data, and Set up experiment)? Are the instructions clear
and easy to understand?
Yes, the instructions were included and they were clear and easy to understand.

2) Were you able to successfully produce experiment results?
Yes, I was able to successfully produce experiment results.

3) How long did it take you to run this experiment, from start to finish?
About 1 hour.

4) Did you need to make any changes or do any additional steps beyond the documentation in order to successfully complete this experiment? Describe *in detail*. How long did these extra steps or changes take to figure out?
No, I didn't need to make any changes or do any additional steps.

5) In the [lecture on reproducible experiments](http://witestlab.poly.edu/~ffund/el6383/files/Reproducible+experiments.pdf), we mentioned six degrees of reproducibility. How would you characterize this experiment - where does it fall on the six degrees of reproducibility?
3


## Other comments to authors

Please write any other comments that you think might help the authors
of this project improve their experiment.
In my opinion, the topic can be more challenging and we can prove more results through the experiment.
In other hand, the instructions authors provide are as good as the ones form instructor if they can
express more specifically. Whats more, the units should be more clear in the graphs.
