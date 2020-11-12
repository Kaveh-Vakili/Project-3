# Project-3

Week 1:
Theodore Melcher is my partner

Week 2:
I created a readFile where in this function I open the userlog file. Once I opened the file, I used the .read method to read the file and print all the content of the file to the screen. This function is a good beginning to the project, as it gives me the ability to see what is consisted within this function. 

Week 3:
In the beginning I had truble understanding what I needed each function to do, and how to call each function in order to perform that function. When creating the irresponsibleBehavior, I understood that the efficiency of creating this project would be much smoother if I incorporated parameters. The contents of the log file that the program was reading, I was able to put that in an array for each function. This helped make the understanding of this project much easier. Another challenge I had when creating this project was understanding the number of times the user logged in and logged out. Through constant experimentation, I eventually used a for loop which virtualy simplified this whole process of reading the number of times a user logged in and logged out. Understanding this porcess helped me greatly to complete this project because much of this porject had different functions that consisted of for loops. Finally, understanding different features within python is etrmeely curicial in knwoing whoch one to use in a particular situation when creating this program. Before, I was not as familirized with the .append() method in order to add to a list, then I have till now. Wheather it be for adding to a list of irresponsible behvaior commited by users or adding to a list where the system finds a gitch, or adding and and reporting th enumber of people for each domain. All of which the .append() methd became very useful, and being able to fully undertsnad the functions of what it can do, was challenging in the beginning, but very useful at the end. When trying to run my program, I also faced the chalnege of not having the program running, due to the fact thta I didnt understand that I needed to call my readFile() function. This project has taught me to be meticulous in the code I choose to write. 

 




PROBLEM STATEMENT

So your task is to write code to parse this log file (userlog.logPreview the document) and generate automated reports.
Reading the log file is similar to reading any other text file in python. The ".log" extension does not change the way you read the input file in python.


The report must mention the following insights:

1. Suspicious activities (suspicious_report.txt)

If any user logs into any of the systems more than 5 times in a single day, or if the user logs into any of the systems even once between 12:00 am to 5:00 am, it is marked as suspicious behavior. 

You must report the total count of suspicious activities.
Suspicious behavior for a user on one day accounts for a total count of 1.
Hence, total cases will be a sum of all the suspicious days for all the users.
The total number of cases for each individual user will be the number of all the suspicious days for that user.
All the time, activity, and server information for the particular days for each user must be listed in the ascending order, sorted on the basis of time.

Sample report file: sample_report.txtPreview the document

2. Irresponsible behavior (irresponsible_report.txt)

The user is expected to logout every time he/she logs in to any of the systems. So if the user forgets to logout after logging in, it is considered an irresponsible behavior. To keep it simple, you can check if the number of logins is more than the number of logouts for a particular user on a given day, it can be tagged as an irresponsible activity.

You must report the total count of irresponsible activities.
Irresponsible activities for a user on one day account for a total count of 1.
Hence, total cases will be a sum of all the days when any user was irresponsible.
The total number of cases for each individual user will be the number of days when that particular user was irresponsible.
All the time, activity, and server information for the particular days for each user must be listed in the ascending order, sorted on the basis of time.

Sample report file: sample_report.txtPreview the document

3. System glitch (glitch_report.txt)

On the contrary to the previous behavior, if the system records more number of logouts than the number of logins for any user, we flag it as a system glitch as this is not practically possible.

You must report the total count of the system glitches.
Glitches for a user on one day account for a total count of 1.
Hence, total cases will be a sum of all the days when there was a glitch for any user.
The total number of cases for each individual user will be the number of days when that particular user faced a glitch.
All the time, activity, and server information for the particular days for each user must be listed in the ascending order, sorted on the basis of time.

Sample report file: sample_report.txtPreview the document

4. Domain count (domain_report.txt)

A list of all the unique domains and the number of users registered within each domain.
NOTE: The domain name of a particular user can be found by checking the second part of their email-id.
NOTE: "Unique domains" mean that each domain name should occur only once in this list.

Example:

Email-ID:          sample.user@domain.abc
Name:              sample.user
Domain name: domain.abc

Sample report file: sample_domain_report.txtPreview the document
