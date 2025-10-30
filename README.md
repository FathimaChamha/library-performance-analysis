# library-performance-analysis
Library Book Borrowing and Return System - Performance Analysis for EEX5362
FATHIMA CHAMHA 
REG NO: 121434875 
STUDENT NO: S92074875 

1.	The System We Are Studying
What is this System? 
This is a public library where people come to borrow books and return them. When library members visit, they:
  •	Search for books they want to read
  •	Wait in line to borrow books at the counter
  •	Take books home (for 2 weeks usually)
  •	 Come back to return books at the counter or drop box
  •	May need to pay late fees if books are returned late
Why is this System complex?
  •	Many people want to borrow books at the same time (especially weekends)
  •	Some books are very popular and have waiting lists
  •	 Books can be borrowed, returned, or renewed
  •	 Staff must check books in and out, scan them, and update records
  •	 Some books get lost or damaged
  •	 Limited number of staff members at the counter
  •	The system must track thousands of books and hundreds of members
What can we measure?
  •	How long people wait in line to borrow or return books
  •	How many books are borrowed each day
  •	 How busy the library staff are
  •	 Which times of day are busiest
  •	 How many books are overdue
  •	 How long it takes to process each book transaction




2.	What We Want to Improve (Performance Objectives)
Main Goal:
  Make the library work faster so people don’t wait long and more books can be borrow and return quickly.
A.	Reduce Waiting Time in Line
  What: How long people stand in line at the counter
  Now: Around 8 minutes waiting
  Target: Make it 3 minutes or less
  Why it matter: People don’t like waiting too long and maybe they go without borrowing
B.	Increase Book Transactions Per Day
  What: How many books borrow and return each day
  Now: About 400 books per day
  Target: Around 500 books per day (25% more)
  Why it matter: More members can use the library fast and easy
C.	Find the Bottlenecks
  What: See which part of the process is slow
  Example:
  •	Maybe book searching take too long?
  •	Maybe checkout counter is slow?
  •	Or not enough staff at busy time?
  Why it matter: If we fix the biggest slow part first, we get best results
D.	Improve Staff Utilization
  What: Make sure staff working well (not too busy or too free)
  Target: Staff work busy around 60–75% of the time
  Why it matter: Use staff and money smart, and no one get tired too much
E.	Reduce Book Processing Time
  What: How long to check or return one book
  Now: About 2 minutes per book
  Target: Around 1 minute per book
  Why it matter: Faster work means shorter lines and happy members
F.	Minimize Overdue Books
  What: How many books come back late
  Now: 15% of books are late
  Target: Make it under 8%
  Why it matter: More books available for others to borrow sooner

3.	The Data We Will Collect
Time Period: January 2024 – December 2024 (whole year)
We will collect data about every borrow and return that happen in the library.

What We Collect for Each Transaction: 
      Data Item	                     What It Means	                                  Example
Transaction ID	             Unique number for each borrow/return                    	T-00001
Member ID       	           Code for each library member	                            M-12345
Book ID	                     Code for each book	                                      B-89456
Book Title	                 Name of the book	                                Harry Potter and the...
Book Category	               Type of book (Fiction, Non-fiction, etc.)	              Fiction
Transaction Type	           Borrow or Return	                                        Borrow
Date             	           The date of the transaction                            	3/15/2024
Time	                       Time of the transaction                                	10:30 AM
Day of Week	                 Which day it happen	                                    Saturday
Counter Wait Time	           How long people wait in line	                            5 minutes
Processing Time	             Time to scan and complete the work	                      2 minutes
Staff Member ID	             Who handled the transaction	                            Staff-03
Number of Staff on Duty	     Total staff working that time	                          3 people
Due Date	                   When book must be returned	                              3/29/2024
Return Status	               On time or late	                                         On time

Extra Data We Collect:
Data Type	                   What It Tracks	                            Example
Peak Hour Data	        Busiest times in the day	          3–5 PM weekdays, 10 AM–2 PM Saturdays
Queue Length	          How many people waiting in line	              8 people
Popular Books           Which books are borrowed most	          List of top 50 books
Member Activity	        How often members visit	             2 times per month average

Sample Data Size:
  •	Around 120,000 transactions in one year
  •	Around 330 transactions per day
  •	Around 5,000 active library members
  •	Around 15,000 books in library
  4.	How We Will Analyze Performance
Steps:
Find average waiting times
  •	For different times in a day
  •	For different days of week
  •	For borrow vs. return
Find bottlenecks
  •	Which time has longest lines?
  •	Which day is busiest?
  •	Do some book types take more time?
Check staff efficiency
  •	How many transactions each staff do per hour?
  •	Are some staff faster than others?
  •	Do we need more staff at some times?
Study book movement
  •	Which books are most borrowed?
  •	How long people keep them?
  •	When are books mostly returned?
Test new improvement ideas
  •	What if we add self-checkout machine?
  •	What if one more staff work in busy time?
  •	What if we give 3 weeks borrowing time?
Success Measures:
  	People wait less than 3 minutes in line
  	Process at least 500 books per day
  	Staff busy 60–75% of time (not too much, not too little)
  	Each transaction take 1 minute or less
  	Less than 8% of books are late
  	No more than 5 people in line anytime
5.	Expected Results
We will learn:
  •	When the library is most busy
  •	Which steps are slow
  •	If more staff is needed and when
  •	If self-checkout can help
  •	How to make lines shorter
We can improve by:
  •	Better staff timing during busy hours
  •	Faster checkout steps
  •	Maybe add self-checkout machines
  •	Put popular books in easy-to-find places
  •	Send reminders to reduce late returns
Benefits:
  •	People happy (less waiting)
  •	More books borrowed
  •	Staff less stressed
•	Library work smoother and faster
•	Less overdue books
