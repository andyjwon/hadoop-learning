hadoop-learning
===============

Playground for learning how to do a Hadoop query.

To run a sample locally:

First run:

    mvn package

Then from the root directory of the project, run:

    hadoop jar hadoop-learning.jar edu.lmu.cs.hadoop.MaxTemperatureDriver -conf conf/hadoop-local.xml input max-temp


