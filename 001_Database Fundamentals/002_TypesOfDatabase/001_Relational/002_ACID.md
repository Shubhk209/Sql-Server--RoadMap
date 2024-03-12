# ACID

```mermaid

flowchart LR

A(ACID)
A --> B(A = Atomicty)
A --> C(C = Consistency)
A --> D(I = Isolation)
A --> E(D = Durability)

B --> F[The entire transaction takes place at once or doesn't happen at all.]

C --> G[The database must consistent before and after the transaction]
D --> H[Multiple transactions occur independently without interference.]
E --> I[The changes of a successful transacion occures even if the system failure occurs.]

```

**The ACID properties is a set of principles designed to ensure the reliability of database transactions.**

## Atomicity

Atomicity guarantees that **_all operations within a transaction are completed successfully or none at all_**, which means **_either the entire transaction succeeds or it fails, and the database is left unchanged_**.

![Atomcity](/003_Database%20Fundamentals/000_images/atomicity.webp)

## Consistency

It ensures that every transaction brings the database from one valid state to another, maintaining all predefined rules.

![Atomcity](/003_Database%20Fundamentals/000_images/consistency.webp)

## Isolation

It ensures that the concurrent execution of transactions results in a system state that would be obtained if transactions were executed serially.

## Durability

It guarantees that once a transaction has been committed, it will remain so, even in the event of a system crash​​​​.

![Atomcity](/003_Database%20Fundamentals/000_images/isolation.webp)

# Trade-offs

1. **Performance and Scalability**: Ensuring ACID properties can lead to performance bottlenecks, particularly in distributed systems where the **_overhead of maintaining consistency_** and **_isolation can be high_**.

2. **Complexity**: Implementing and maintaining ACID properties can add complexity to database management, requiring more resources to ensure data integrity and reliability​​.
