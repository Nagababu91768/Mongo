**Final Exam**

# Final: Question 3
**Problem:**

Suppose an instance of MongoClient is created with the following settings:

```bash
from pymongo import MongoClient

uri = "mongodb+srv://m220-user:m220-pass@m220-test.mongodb.net/test"

mongo_client = MongoClient(
  uri,
  connectTimeoutMS=50,
  retryWrites=True,
  authSource="admin"
)
```
Please find the documentation on Connection String URI Format here. The variable representing our client, mongo_client, will:

Attempts Remaining:Correct Answer

**Check all answers that apply:**

- authenticate against the test database.
- **automatically retry writes that fail.**
- **wait at most 50 milliseconds for timing out a connection.**
- allow a maximum of 50 connections in the connection pool.
