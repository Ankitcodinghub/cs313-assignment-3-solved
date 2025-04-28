# cs313-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CS313 Assignment 3 Solved](https://www.ankitcodinghub.com/product/cs-313-databases-and-information-systems-laboratory-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117356&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS313&nbsp;Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
&nbsp;

1. Create User and Database called lab3 10 Points

(instructions for creating user and database are given at the last section of this page)

2. Create the following tables. The attributes with id mentioned are keys for the respective Tables.:

● part – part-no ( id ), part-name, color, weight 5 Points

● supplier – supplier-no ( id ), sup-name, city, bank 5 Points

(Shipment contains data about parts supplied by various suppliers) 5 Points

3. Add one tuple in each table interactively using the mysql insert statement. 6 Points

4. Create a .sql file to load more data in these tables so that they have at least 3 parts, 2 suppliers, and 4 shipments for each part. (instructions for creating .sql file are given at the last section of this document)

There are two tasks to be done here:

i. Create a .sql file with relevant insert statements,ii. Use the sql file to reflect the changes (i.e., insert query related changes) in the respective tables.

Please submit the .sql file which you have created. 14 Points

5. Write the SQL queries for the following questions. (Please write the same in the report)

a. List suppliers who have supplied red parts. 5 Points

b. Get the total cost of shipments for all suppliers for making payments to them. 10 Points

c. List suppliers who have supplied all parts. 15 Points

6. Demonstration of working commands and queries

NOTE:

2. What to submit?

a. You need to submit two .sql files 5 Points

i. .sql(&lt;roll_number&gt;_1.sql) which contains all the commands/queries related to

Q1, Q2, Q3 and Q5.

ii. .sql&lt;roll_number&gt;_2.sql) for Q4 which contains insert statements.

b. output(screenshot) of all the questions must be put in a document(.pdf).

3. Submit the .pdf and .sql files named with your &lt;roll_number&gt;.pdf and &lt;roll_number&gt;_&lt;1/2&gt;.sql respectively.

4. Mode of submission is moodle.

Instructions

● Creating the user:

mysql&gt; create user ‘UserName’@’localhost’ identified by ‘Password’;

● Grant the privileges to the user

mysql&gt; grant all privileges on db_name.* to ‘UserName’@’localhost’; ● To login with a new user

$ mysql -u UserName -p Enter password:

● Creating the database:

mysql&gt; create database db_name;

● Connecting to database

mysql&gt; use db_name;

● Instructions for creating .sql file

1. Use any text editor and create a file(such as gedit or sublime etc.) 2. Include all the relevant commands and queries in the .sql file as it is.

3. Save the file with extension as .sql

● Running .sql file in mysql terminal

mysql&gt; source &lt;path to file&gt;&lt;filename.sql&gt;
