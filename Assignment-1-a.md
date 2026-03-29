Assignment 1: Understanding Apache Spark and Distributed Processing

a) Theory

Explain the concept of distributed data processing. How does Apache Spark improve performance compared to traditional data processing systems? Include the role of in-memory computation.

Answer:

**Distributed Data Processing** is a method where a large dataset is broken into smaller chunks (partitions) and processed simultaneously across multiple machines (a cluster). This "divide and conquer" approach allows for handling data that is too massive for a single computer's memory or CPU.

**How Spark Improves Performance:**
Traditional systems like Hadoop MapReduce were "disk-heavy." After every step, they wrote data back to the physical hard drive. Spark revolutionized this with:

* **In-Memory Computation:** Spark keeps data in the RAM (Random Access Memory) across the cluster. Since reading from RAM is significantly faster than reading from a disk, Spark can be up to 100x faster for certain tasks.

* **DAG (Directed Acyclic Graph):** Spark builds a logical plan of all tasks. It optimizes the entire workflow before executing it, reducing redundant data passes.
