**Chapter 2: User-Facing Backend**

# Ticket: Delete Comments
**Problem:**

**User Story**

"As a user, I want to be able to delete my own comments."

**Task**

For this ticket, you'll be required to modify one method in db.py, delete_comment. Ensure the delete operation is limited so only the user can delete their own comments, but not anyone else's comments.

You can find examples of delete_one() in notebooks/deletes.ipynb.

**MFlix Functionality**

Once this ticket is completed, users will be able to delete their own comments, but they won't be able to delete anyone else's comments.

**Testing and Running the Application**

You can run all the tests for this ticket by running:

```bash
pytest -m delete_comments
```
Once the unit tests are passing, run the application with:

```bash
python run.py
```
Now proceed to the status page to run the full suite of integration tests and get your validation code.

After passing the relevant tests, what is the validation code for Delete Comments?

Attempts Remaining:Correct Answer

Enter answer here:

    5ac25c280a80ed6e67e1cecb
