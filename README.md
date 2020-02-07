# Crime-Statistics-with-Spark-Streaming
#### Q. How did changing values on the SparkSession property parameters affect the throughput and latency of the data? <br />
A. By checking `processedRowsPerSecond`<br />
#### Q. What were the 2-3 most efficient SparkSession property key/value pairs? Through testing multiple variations on values, how can you tell these were the most optimal?  <br />
A.
- spark.streaming.kafka.maxRatePerPartition
- spark.sql.shuffle.partitions
- spark.default.parallelism
