**Chapter 4: Resiliency**

# Connection Pooling
**Problem:**

Which of the following are benefits of connection pooling?
Attempts Remaining:Correct Answer

Check all answers that apply:

- Multiple database clients can share a connection pool.
- The connection pool will persist after the client is terminated.
- **New operations can be serviced with pre-existing connections, so a new connection doesn't have to be created each time.**
- **A large influx of operations can be handled more quickly with a pool of existing connections.**

**Chapter 4: Resiliency**
# Robust Client Configuration
**Problem:**

When should you set a wtimeout?
Attempts Remaining:Correct Answer

Check all answers that apply:

- When our application is using a Read Concern more durable than "available".
- **When our application is using a Write Concern more durable than w: 1.**
- When our application is using a connection pool of 100 or more connections.
- When our application is issuing bulk operations in large batches.

**Chapter 4: Resiliency**

# Change Streams
**Problem:**

What of the following is true about Change Streams in Pymongo?
Attempts Remaining:∞Unlimited Attempts

Check all answers that apply:

- **They can be used to log changes to a MongoDB collection.**
- **They output cursors, which contain change event documents.**
- They will not log changes associated with insert operations.
- They can stay open for up to 10 minutes.
- **They accept pipelines, which can be used to filter output from the change stream.**
