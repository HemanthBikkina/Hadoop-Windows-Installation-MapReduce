# Hadoop-Windows-Installation-MapReduce
Complete guide to installing Hadoop on Windows and running a WordCount MapReduce job
# Hadoop on Windows: Installation & WordCount MapReduce

This repository demonstrates a **complete Hadoop 2.7.7 setup on Windows**, including
real-world installation challenges, configuration, architecture explanation, and a
working MapReduce WordCount job.

## 🔗 Published Article
Medium Article:
https://medium.com/@bikkinahemanth2005/hadoop-on-windows-installation-challenges-architecture-and-wordcount-mapreduce-d6afd5150ee3

## 🧩 Topics Covered
- Hadoop installation on Windows
- Common Windows-specific issues (winutils, native IO)
- Hadoop architecture (HDFS, YARN, MapReduce)
- Configuration files explanation
- WordCount MapReduce job execution

## 🏗 Hadoop Architecture
- **HDFS**: NameNode, DataNode
- **YARN**: ResourceManager, NodeManager
- **MapReduce**: Mapper, Reducer, Driver

## ⚙️ Configuration Files
All required Hadoop configuration files are available under the `configs/` directory.

## ▶️ Running WordCount
```bash
hdfs dfs -mkdir /input
hdfs dfs -put input.txt /input
hadoop jar simplewordcount.jar SimpleWordCount /input /output
# Hadoop 2.7.7 Single Node Cluster & WordCount

## Overview
Implementation of Hadoop 2.7.7 on Windows using Java 1.8
with MapReduce WordCount execution.

## Features
- Hadoop installation
- HDFS configuration
- YARN setup
- JPS verification
- WordCount MapReduce

## Research Publication
DOI: https://doi.org/10.5281/zenodo.xxxxxxx

## Author
Bikkina Hemanth
Sri Vasavi Engineering College

