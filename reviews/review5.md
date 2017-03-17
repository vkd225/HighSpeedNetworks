
Project Review
=====================================================

## Experiment design

There are several independent experiments here. It's not clear how these relate to one another, and the first two do not clearly support the experiment goal. If you want to study file transfer protocols (as stated in the experiment goal), you should use file transfer protocols for all parts of the experiment.

The first two parts did not yield meaningful results (see "Other comments" section.)

## Reproducibility

The instructions are provided with a good level of detail and the data and data analysis scripts are also provided.

For part 3, the data was recorded manually and put in the R script. You should have recorded the output of the commands to a file at the very least, and ideally parsed that to get a machine-readable file that could go directly into R. (See e.g. http://groups.geni.net/geni/wiki/GENIExperimenter/Tutorials/SIGCSE13Tutorial/RunExampleAssignment#a2b.UDTvsFTPExperiment )

## Communicating experiment results

The plots titled "Boxplot" are not actually boxplots.

The results of multiple experiments seem to be inappropriately agggregated and connected by lines, which is why your plots have those weird jagged patterns.

It appears that some, but not all, of the experiments are run twice.  You should run every experiment multiple times, aggregate the results, and also show some measure of variation like standard error or confidence intervals.

Each of the plots are missing units in the title of one axis or both.


## Other comments

You describe UDP as having a lower, but more consistent, throughput, in part 1 and part 2. This is the result of an experiment error on your part. In `iperf`, when you send UDP traffic, you should specify your desired sending rate - because unlike TCP, the UDP protocol does not attempt to adjust the sending rate. In `iperf`, if you send UDP traffic without specifying a sending rate, it will default to 1.05 Mbps (as you have measured). This doesn't say anything about the link or the network, it's just the behavior of the tool you are using (if you don't understand that you need to specify that parameter).


Finally, but most importantly, a lot of this experiment clearly comes from http://groups.geni.net/geni/wiki/GENIExperimenter/Tutorials/SIGCSE13Tutorial/RunExampleAssignment and/or http://groups.geni.net/geni/wiki/UDTExampleExperiment but you did not credit the source. This is a **very serious** issue.
