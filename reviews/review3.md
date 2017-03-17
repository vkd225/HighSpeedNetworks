
Project Review
=====================================================


## Overview

1) Briefly summarize the experiment in this project.
This experiment


2) Does the project generally follow the guidelines and parameters we have
learned in class?




## Experiment design

1) What is the goal of this experiment? Is it a focused, specific goal?
Is it useful and likely to have interesting results?


The goal of this experiment to compare and contrast the performance of TCP and UDT (UDP based Data Transfer) by taking into account the metrics, namely, throughput, bandwidth and packet drop.

it is a focused goal since it introduce the specific goal of this experiment and the parameters it used.

I think it may not have interesting results because from the plot of this experiment, the result does not show much difference .




2) Are the metric(s) and parameters chosen appropriate for this
experiment goal? Does the experiment design clearly support the experiment goal?


This experiment choose the throughtput as the metric and choose the bandwidth, packet drop rate and the delay as the parameters.
It seems appropriate for this experiment since from the change of parameters choosed, we can see the change of result in different
situation.

The design of this experiment is roughly support the experiment goal. It show differences of the bandwidth and the case of concurrent flows between
TCP and UDP, it also compare the FTP  and UDP.




3) Is the experiment well designed to obtain maximum information with the
minimum number of trials?


Yes, this experiment use the relatively less number of trials to obtain maximum information.The range of parameter is that:
delay in the range of 0 to 50ms , packet drop rate in the range of 0 to 0.01 and Bandwidth in th range of 10Mbps to 1Gbps.
This experiment choose the appropriate span of this parameter so it use less number. For example, they choose 100Mbps, 500Mbps
and 100Mbps to test in the trials.




4) Are the metrics selected for study the *right* metrics? Are they clear,
unambiguous, and likely to lead to correct conclusions? Are there other
metrics that might have been better suited for this experiment?


I think the metrics are right for this experiment. From the change of parameter bandwidth, delay and packet drop rate,
we can see how these parameters influence the throughtput. The throughput change a lot in TCP rather than in UDP.




5) Are the parameters of the experiment meaningful? Are the ranges
over which parameters vary meaningful and representative?


From the plot of result, we may conclude that in udp no mater how parameter change, the throughtput barely changed.
And in TCP, the throughput only show lots of differences when bandwidth is changed. So I think the parameters and its ranges may be not much meaningful.




6) Have the authors sufficiently addressed the possibility of interactions
between parameters?


Although the authors use lots of comparisons to show the experiment result, I think it is not enough to show the interaction between parameters.
The parameter mainly show the influences to the throughput.It did not addressed the possiblty of interactions between parameters sufficiently.




7) Are comparisons made reasonably? Is the baseline selected for comparison appropriate
and realistic?


I think the comparison is roughly reasonably. since the authors use differnet range of parameter in comparisons bandwidth,delay and packet drop rate,
which can clearly show the goal of the experiment. It is the baseline selected because these parameter can directly have affect on the result.




## Communicating results


1) Do the authors report the quantitative results of their experiment?

Yes, the authors show the result through the plot from the number in experiment.




2) Is there information given about the variation and/or distribution of
experimental results?

The authors use the plot to show the variation and the distribution about the parameter and the result.



3) Do the authors practice *data integrity* - telling the truth about their data,
avoiding ratio games and other practices to artificially make their results seem better?

I think the authors did not artificially make their results seem better.




4) Is the data presented in a clear and effective way? If the data is presented in
graphical form, is the type of graph selected appropriate for the "story" that
the data is telling?

The authors use plots to present the data in this experiment. They use the boxplot to show the comparison between TCP and UDP.
They also use the bar plot to show the comparison between FTP and UDP.

I think these graph were selected appropriate since they clearly show the change of result except some situation in UDP.




5) Are the conclusions drawn by the authors sufficiently supported by the
experiment results?

No, since the authors do not show the interaction between parameter, so we do not know whether these interaction could influence
the result of experiment.


## Reproducible research



1) Did the authors include instructions for reproducing the experiment in 3 ways (Raw data -> Results,
Existing experiment setup -> Data, and Set up experiment)? Are the instructions clear
and easy to understand?

yes, the report is clear to understand.



2) Were you able to successfully produce experiment results?

Although the report has some mistakes, I can successfully produce the experiment results after I correct some of faults.




3) How long did it take you to run this experiment, from start to finish?

It takes me about 12 hours from start to finish to run this experiment.




4) Did you need to make any changes or do any additional steps beyond the documentation in order to successfully complete this experiment? Describe *in detail*. How long did these extra steps or changes take to figure out?

In order to finish this experiment, I correct some faults of this experiment.



5) In the [lecture on reproducible experiments](http://witestlab.poly.edu/~ffund/el6383/files/Reproducible+experiments.pdf), we mentioned six degrees of reproducibility. How would you characterize this experiment - where does it fall on the six degrees of reproducibility?

I think is number three degree


## Other comments to authors

Please write any other comments that you think might help the authors
of this project improve their experiment.
