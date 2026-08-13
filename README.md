# Hadoop MapReduce WordCount

A simple MapReduce project built with Java and Apache Hadoop 3.4.2, running on Ubuntu through WSL 2.

## Architecture

```text
Local Input
    ↓
HDFS
    ↓
YARN
    ↓
Mapper
    ↓
Shuffle
    ↓
Reducer
    ↓
HDFS Output
