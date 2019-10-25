# Databricks Certification
Important Topics For Certification

I have recently completed Databricks Certified Spark Developer Certification. Here are my inputs with topics and sample questions.

![Image description](https://oiwj5g.bn.files.1drv.com/y4mT-mvyNFFDQ7EYLi4PcSfPxvLUj78dymAqC4lXjIiVONERpwxo39e8Qh8ti7TjmpocgaRJHBTp39o6Oriq_VMdhuXAx6wkVNbNpU6Uw-pa7d2-fR8Gi92LPyNs-46qDyfky78ye37-wQZnLVIPGVs0BCxrdPZ1C8if3vuuSlCi8eJwriJcPu9pq0hkrKuVFO-XWCWOM9ldK4lkEspY0_qmA?width=1132&height=839&cropmode=none)

<h2><i>The distribution of questions is as follows:</i></h2>

<b>Spark-Streaming + Structure Streaming</b> : 4 Questions(10%)

Topics: Source, Sink, Output Mode, Window Operation, ReadStream, WriteStream, Modes of output.

Questions: 

Which among below options is using window operation incorrectly.

a.) val windowedCounts = words.groupBy(
  window($"timestamp", "20 seconds", "2 seconds"),
  $"word"
).count()

b.) val windowedCounts = words.groupBy(
  window($"timestamp", "2 seconds", "5 minutes"),
  $"word"
).count()

c.) val windowedCounts = words.groupBy(
  window($"timestamp", "2 seconds", "1 seconds"),
  $"word"
).count()

d.) val windowedCounts = words.groupBy(
  window($"timestamp", "10 minutes", "5 minutes"),
  $"word"
).count()

<b>Spark-ML/Mllib</b> : 2 Questions(5%)

Topics: Parameter Grid, Pipelines, Test-Train Split, Evaluators, Estimators.

Questions:

what will happen if we use pipeline for series of ML transformers. A snippet of code will be given.

<b>GraphX + GraphFrames</b> :2 Questions(5%)

Topics: BFS, PageRank, Bi-directional graph, Subgraph.

Questions:

What will be the output of bfs if there is no edge between give source and destination vertices. A snippet of code will be given.

<b>Spark SQL+DataFrame/DataSet API+RDD API+ Saprk Core</b> : 32 Questions(80%)

Topics: Partitions, number of partitions, Acumulators, broadcast join, types of cluster Manager,difference between repartition 
and Coaleasce, All dataset/dataframe transformation/Actions, explode, joins, DataframeReader, DataFrameWriter, UDF.

Questions:

1. Which cluster Manager does not provide scaling up the nodes.
a.) Local Mode
b.) Standalone Mode
c.) Yarn
d.) Mesos

2. How many partitions should be used for best performance with respect to the number of cores.
3. what will happen if we have less number of cores and higer number of partitions.
4. Which among repartition and coaleasce are wide  and narrow transformation.
5. Choose any 4 which are dataframe/dataset transformation.
6. Choose any 4 which are dataframe/dataset Actions.

In maximum questions a code snippet will be given and we have to select the correct output.
Aspirant should have coding experience or understand the code by looking into it.

Now some of the helpful links are:

a.) <a href='https://www.linkedin.com/pulse/5-tips-cracking-databricks-apache-spark-certification-vivek-bombatkar/'>Exam Overview</a>

b.) watch this at least 2 times <a href='https://www.youtube.com/watch?v=7ooZ4S7Ay6Y'>Spark Core</a>

c.) <a href='https://github.com/vivek-bombatkar/Databricks-Apache-Spark-2X-Certified-Developer'> Very Important Notes  from Vivek Bombatkar</a>

d.) Databrciks has provided an eBook to start with introduction of each library in spark <a href='https://1drv.ms/b/s!ArN99w01iCc8iUVtD0iw-LYf25li?e=MR0h4l'> here </a>

e.) These 2 ebooks are Very important for beginners and certification aspirants <a href='https://1drv.ms/u/s!ArN99w01iCc8iUgtPqaTjx99QrR7?e=v0sfDq'>eBook</a>

If anyone need clarrification then reach out to me at <a href='https://www.linkedin.com/in/ankit-singh-92a187124/'>Ankit Singh</a>



