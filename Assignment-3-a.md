Assignment 3: Introduction to Spark Structured Streaming

a) Theory

What is Structured Streaming in Spark? Explain how it differs from batch processing. Discuss its key features and real-time use cases.

Answer:

**Structured Streaming** is a scalable and fault-tolerant stream processing engine built on the Spark SQL engine. It treats a live data stream as a **table that is continuously being appended.**

* **Difference from Batch:** Batch processing handles data at rest (fixed size), while Streaming handles data in motion (infinite size).

* **Key Features:**

  * **Fault Tolerance:** Uses checkpointing and write-ahead logs to recover from failures.

  * **Event-time Processing:** Can handle data that arrives late or out of order.

* **Real-time Use Cases:** Fraud detection in banking, live website traffic monitoring, and IoT sensor alerts.
