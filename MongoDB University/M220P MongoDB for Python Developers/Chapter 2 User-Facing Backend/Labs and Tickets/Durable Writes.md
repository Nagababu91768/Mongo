**Chapter 2: User-Facing Backend**

# Ticket: Durable Writes
**Problem:**

**Task**

For this ticket, you'll be required to increase the durability of the add_user method from the default write concern of w: 1.

When a new user registers for MFlix, their information must be added to the database before they can do anything else on the site. For this reason, we want to make sure that the data written by the add_user method will not be rolled back.

We can completely eliminate the chances of a rollback by increasing the write durability of the add_user method. To use a non-default write concern with a database operation, use Pymongo's with_options flag when issuing the query.

You can find examples of write concerns in **notebooks/write_concerns.ipynb.**

**Testing and Running the Application**

There are no unit or integration tests for this lab.

Please complete the multiple choice question below, and then implement the correct write concern in the add_user method.

The implementation of this task will not be tested, but using the default of w: 1 might result in a rollback of your users' account data!

Which of the following write concerns are more durable than the default?

Attempts Remaining:Correct Answer

Check all answers that apply:

- w: 1
- w: 0
- **w: 2**
- **w: "majority"**
