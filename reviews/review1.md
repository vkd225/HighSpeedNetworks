
Project Review
=====================================================

## Overview

1) Briefly summarize the experiment in this project.
>>The experiment is to compare the performance of TCP and UDP using their throughputs and bandwidth data under varying link parameters like bandwidth, delay and packet loss. For this purpose we connect 2 virtual machines using the Rspec specified in the folder. Change the link parameters on the delay node. For every changed parameter i.e. under different cases we measure the throughput using the iperf data by running iperf both on the client and server machines. These data files generated are further used in the Rstudio to generate graphs in order to compare the TCP and UDP performance.  
Also the analysis is performed for 3 concurrent flows. There is one more case considered where the data rates achieved by FTP and UDT are compared.


2) Does the project generally follow the guidelines and parameters we have
learned in class?
>>Yes, the project follows the guidelines and parameters we have learned in class. It has a specific and well defined goal which clearly states the motto of the experiment. Also, the metrics (throughput, bandwidth) measured and the parameters (bandwidth, delay, loss) varied here are meaningful and necessary for comparison.



## Experiment design

1) What is the goal of this experiment? Is it a focused, specific goal?
Is it useful and likely to have interesting results?
>>The goal of the experiment is “The goal of the experiment is to compare and contrast the performance of TCP and UDT (UDP based Data Transfer) by taking into account the metrics, namely, throughput, bandwidth and packet drop. The performance of TCP and UDT is compared for each and every metric based on a graph plot generated on rstudio and an appropriate conclusion can be obtained for each metric.”
The goal mentioned is specific and clearly states the mission of the experiment. It is complete in the sense that it mentions the various parameters to be used and also the use and implementation of those to get meaningful results.


2) Are the metric(s) and parameters chosen appropriate for this
experiment goal? Does the experiment design clearly support the experiment goal?
>>The metrics measured here are sufficient to carry out the performance comparison of TCP and UDP to draw meaningful results. Hence, they satisfy the experiment goal.
The experiment design or the procedure described in the report is a little confusing and complex. It is not clear enough. All the steps are well specified. But the order is jumbled and some cases are repeated. The parameters meet the goal properly, just the framing of the report should have been a little more clear. Also, there were a few mistakes in the commands to be executed.

3) Is the experiment well designed to obtain maximum information with the
minimum number of trials?
>>Yes, the experiment goal and the procedure can actually generate maximum information with minimum trials. But the way it is framed in the report is quite misguiding at times. The report should have been framed more clearly and a simplified version should have been presented. In some cases it is confusing.


4) Are the metrics selected for study the *right* metrics? Are they clear,
unambiguous, and likely to lead to correct conclusions? Are there other
metrics that might have been better suited for this experiment?
>>The metrics selected for the study are right metrics according to me. They generate meaningful results. They are very clearly stated. The results can be easily generated using these metrics which make the comparison of TCP and UDP easier to understand.


5) Are the parameters of the experiment meaningful? Are the ranges
over which parameters vary meaningful and representative?
>>According to me, meaningful parameters are used for the experiment. The range in which the parameters are to be varied is clearly specified. Also, the range specified is valid and leads to meaningful and comparable results. Hence, I can say the parameters chosen are meaningful and representative.


6) Have the authors sufficiently addressed the possibility of interactions
between parameters?
>>Yes, the authors have sufficiently addressed the possibility of interactions between the parameters. Hence, they have varied the parameters under certain range and specified cases are specified by the authors.



7) Are comparisons made reasonably? Is the baseline selected for comparison appropriate
and realistic?
>>The comparison made here is between TCP and UDP using different cases. Firstly they have compared its performance under standard cases. Then they have introduced delay and packet loss and then measured for such specific cases. The major changes in the behavior was noticed and plotted in the line graphs.



## Communicating results


1) Do the authors report the quantitative results of their experiment?
>>The results for this experiment are quantitatively plotted in line plots and confidence intervals where it can be compared and relevant conclusion can be drawn.


2) Is there information given about the variation and/or distribution of
experimental results?
>>No.


3) Do the authors practice *data integrity* - telling the truth about their data,
avoiding ratio games and other practices to artificially make their results seem better?
>>Yes, the authors have practiced data integrity by using genuine data generated from the experiment in specific cases with no ratio games.


4) Is the data presented in a clear and effective way? If the data is presented in
graphical form, is the type of graph selected appropriate for the "story" that
the data is telling?
>>I think appropriate graphs are chosen for the representation of the data. They chose line plots to show individual comparison of TCP and UDP throughput performance under variation of parameters. Confidence interval box plots were used for the comparison of FTP and UDT which clearly displays the difference in the data rates and makes the graphs look comparable in order to deduce meaningful results.


5) Are the conclusions drawn by the authors sufficiently supported by the
experiment results?
>>Yes, I think the conclusions drawn are supported by the results of this experiment.

## Reproducible research



1) Did the authors include instructions for reproducing the experiment in 3 ways (Raw data -> Results,
Existing experiment setup -> Data, and Set up experiment)? Are the instructions clear
and easy to understand?
>>The steps are mentioned from step to step. But at few places there are mistakes in the command (iperf -c 192.168.1.2 --reportstyle C -i 1 | tcp_0delay_100mBW-1.txt) format. There was a little confusion created while writing the steps that makes u create few repetitive files. Otherwise, it is nicely separated in different cases and makes easy to understand and perform.


2) Were you able to successfully produce experiment results?
>>Yes, I could successfully reproduce the experiment results.

3) How long did it take you to run this experiment, from start to finish?
>>It took me more than two hours to run this experiment from start to finish.


4) Did you need to make any changes or do any additional steps beyond the documentation in order to successfully complete this experiment? Describe *in detail*. How long did these extra steps or changes take to figure out?
>>As specified above, due to some confusion few files were overwritten. Which took me around 30 minutes to understand. Otherwise, I didn’t have to perform extra steps to complete the experiment.


5) In the [lecture on reproducible experiments](http://witestlab.poly.edu/~ffund/el6383/files/Reproducible+experiments.pdf), we mentioned six degrees of reproducibility. How would you characterize this experiment - where does it fall on the six degrees of reproducibility?
>>I feel the degree of reproducibility of this experiment is 5 as it does not require any additionaltools or softwares. Sufficient knowledge of Rstudio and git is required to reproduce it.



## Other comments to authors

Please write any other comments that you think might help the authors
of this project improve their experiment.
