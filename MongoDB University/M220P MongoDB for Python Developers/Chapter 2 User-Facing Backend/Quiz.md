**Chapter 2: User-Facing Backend**

# Cursor Methods and Aggregation Equivalents
**Problem:**

Which of the following aggregation stages have equivalent cursor methods?
Attempts Remaining:Correct Answer

Check all answers that apply:

- $out
- **$sort**
- $sortByCount
- **$skip**
- **$limit**


**Chapter 2: User-Facing Backend**

# Basic Writes
**Problem:**

Which of the following is true about InsertOneResult?
Attempts Remaining:Correct Answer

Check all answers that apply:

- **It can tell us whether the operation was acknowledged by the server.**
- **It contains the _id of an inserted document.**
- It is a cursor.
- It contains a copy of the inserted document.


**Chapter 2: User-Facing Backend**
# Write Concerns
**Problem:**

Which of the following Write Concerns are valid in a 3-node replica set?
Attempts Remaining:Correct Answer

Check all answers that apply:

- **w: 0**
- **w: 1**
- w: 4
- w: 5
- **w: majority**

**Chapter 2: User-Facing Backend**
# Basic Updates
**Problem:**

Which of the following are valid update operators in Pymongo?
Attempts Remaining:Correct Answer

Check all answers that apply:

- **$push**
- $update
- **$set**
- **$inc**
- $remove


**Chapter 2: User-Facing Backend**

#Basic Joins
**Problem:**

Why did we use a let expression with expressive $lookup, when joining the comments and the movies collection?
Attempts Remaining:Correct Answer

Choose the best answer:

- To count the number of comments documents.
- To use fields from the comments documents in the pipeline.
- **To use fields from the movies documents in the pipeline.**
- To store the output of the pipeline in the movie_comments field.


**Chapter 2: User-Facing Backend**

# Basic Deletes
**Problem:**

Which of the following is true about deleting documents in Pymongo?
Attempts Remaining:Correct Answer

Check all answers that apply:

- Pymongo can only delete one document at a time.
- **delete_one() can only delete one document.**
- delete_one() will not return a DeleteResult object.
- **delete_many() can delete any number of documents.**
- **DeleteResult objects contain the number of deleted documents.**
