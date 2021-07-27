# Library-Management-System using SQL Queries and PL/SQL Block
Mini project to handle the operations of Library Management System using SQL queries and PL/ SQL (use the concept of Cursor, Trigger, Procedure/ function, Package and Exception Handling).

## Explanation of the Project
I have created library management system 📚. This system contains the information about members, books, transaction about books and transaction_history. I have used the concept like cursor, trigger, exception handling and procedure.

1. The library has 3 kinds of members:<br>
   i.   Monthly this member can borrow 4 books <br>
   ii.  Yearly this member can borrow 2 books <br>
   iii. Lifetime this member can be borrow 6 books

2. The same kind of a book cannot be borrowed by a member at one instance.

3. The fine amount should be calculated basing on the issue date ,return date and due date.

4. The fine amount can be 5/- per day.

5. When a book is issued automatically it should reflect in the book table.

## Modules in the Project
-   Issue Book Section
-   Return Book Section
-   Trigger to automatically increment and decrement the no. of books
-   Trigger to move the data from the transaction to transaction history table upon deletion

## Note
Sorry, I'm not able to upload source code on GitHub :octocat: because I've performed the project in Oracle Live SQL. But, you'll find all the code in [Document](https://github.com/iamdhrutipatel/Library-Management-System/blob/main/Library%20Management%20System.pdf).
Thank You!


## Facing any issues???
Feel free to [open an issue](https://github.com/iamdhrutipatel/Library-Management-System/issues/new?assignees=&labels=Query&title=Query). I'll be glad to help you.❤️

