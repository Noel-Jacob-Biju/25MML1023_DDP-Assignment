Assignment 2: Spark DataFrames and Transformations

a) Theory

Differentiate between transformations and actions in Spark. Provide at least 3 examples for each and explain their significance in execution planning.

Answer:

Spark uses Lazy Evaluation. This means Spark doesn't process data immediately when you write code; it waits until an Action is called.

**Feature** | **Transformations** | **Actions** |
|---|---|---|
**Definition** | Operations that create a new dataset from an existing one. | Operations that trigger computation and return a result.
**Behavior** | Lazy (nothing happens immediately). | Eager (triggers the execution).
**Examples** | map(), filter(), groupBy() | show(), count(), collect()
