# KafkaSparkStreaming
Basic Kafka Spark Streaming Appplication in python

In the streaming application code, import KafkaUtils and create an input DStream calling the createStream function. Handle the returned stream as a normal RDD:

** Should specify the spark-streaming-kafka jar path in the spark-submit command 

spark-submit --jars C:\work\Anaconda3\Lib\site-packages\pyspark\jars\spark-streaming-kafka-0-8-assembly_2.11-2.2.0.jar  practice\Consumer.py


