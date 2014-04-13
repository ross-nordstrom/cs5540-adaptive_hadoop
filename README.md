# Adaptive and Heterogeneous Hadoop MapReduce
    Aaron Burkhart, Ross Nordstrom
    University of Colorado - Colorado Springs
    CS 5540 - Datacenters and Cloud Computing

## Abstract
> Hadoop is a commonly used Apache implementation of MapReduce, a technique for
parallel processing in distributed systems. One weakness of Hadoop is it does
not assign tasks based on the computers’ computational capabilities. By scaling
how much work is sent to a given computer based on its capabilities, we can
redce the difference in task completion time across the system, and thus improve
the overall performance of Hadoop. We call such a system – with computers of
varying capabilities – a heterogeneous environment. This research aims to develop
a task scheduling and assignment algorithm for Hadoop MapReduce that is sensitive 
to both the hardware configurations of the nodes in the cluster and interference
from other non-cluster nodes running on the same hardware as cluster node.


## Contents

The major contribution of this repository is the `/proposal` folder, containing our project proposal and some LaTex scripting for generating it.
