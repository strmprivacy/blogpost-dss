# STRM Privacy Batch Jobs and Data Subjects API

STRM Privacy is a privacy-focused data platform. This notebook is part of the tutorial on working with STRM Privacy's Batch Jobs and Data Subjects API: https://strmprivacy.io/posts/batchjobs-and-datasubjects/

## What is what
- With *STRM Batch Jobs*, you can process data in batches according to a privacy-focused _data contract_, from and to batch destinations (mostly buckets/storage)
- With the *Data Subjects API* you can easily locate and operate on a data subject's data through its keylink (as long as that data is processed through STRM).

## Content
In this notebook you can find an example of
- Processing the UCI online retail dataset as batch job
- Setting up a data connector to read from and write into storage
- Defining a data contract and sending data according to it
- Configuring the batch job via a config JSON
- Executing the job itself
- Parsing and processing the encrypted dataset and working with the keys
- Querying the Data Subjects API to find all data related to a Data Subject

## Sounds great
It does! STRM's Batch Jobs and Data Subjects API means:
- You can process regular workloads and add privacy by design to them
- Re-process existing data (as you probably don't know how you obtained it - oopsie)
- Easily and cheaply fulfill Data Subject Request through the Data Subjects API (via an associated keylink)
- And for deletion requests (RTBF - Right to be Forgotten) you can even fulfill them by just throwing away the keys (and only keep the anonymous data)
-  
