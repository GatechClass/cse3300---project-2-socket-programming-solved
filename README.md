# cse3300---project-2-socket-programming-solved
**TO GET THIS SOLUTION VISIT:** [CSE3300 – Project 2: Socket Programming Solved](https://mantutor.com/product/cse3300-project-2-socket-programming-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116155&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE3300 - Project 2: Socket Programming Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
100 with up to 20 extra points for CSE3300 students (will be treated with 100 as full score in final grade calculation); 120 for CSE5299 students (will be treated with 120 as full score in final grade calculation).

1 Purpose of Assignment

In this assignment, you will practice TCP socket programming. In the first part of the assignment, you will write a client and a single-threaded server. In the second part of the assignment, you will extend the server to a multi-threaded server. While you can use any programming language that you are comfortable with, I would highly encourage you to use python since the program in Python is conceptually simple and the sample code, we covered in class is written in python. In addition, the sample multi-threaded server program that you are given in this assignment is in Python (see Section 3).

2 Basic Assignment

In the basic assignment, you will implement a client that queries for English words that are stored in a word list at a server. The program needs to be done using TCP socket programming since we would like reliability that is guaranteed by TCP.

Application Protocol. Design and describe your application-level protocol, which specifies the format of the messages (queries and responses) and actions that the server and client need to take. Your implementation should follow the application-level protocol you design. It’s a good idea to consider special cases, e.g., no queries found. You can design action code, e.g., “200 OK” or “404 not found” as in HTTP.

3 Multi-threaded Server

Now leave a copy of your basic server and client programs aside (please submit the code of both the basic and multi-threaded version for this assignment). Our next step is to extend both the server and the client. Specifically, (i) you are going to make your server to be multi-threaded so that it can serve multiple clients simultaneously, and (ii) you will also extend your client to allow it to send multiple queries; each query is input by you through the keyboard. When you enter “quit”, the client will terminate.

To help you write the multi-threaded server program, we provide a sample source code (called thread-server.py) to you. The code is taken from the book “Programming Python” (by Mark Lutz). It has detailed documentation in the source code. In particular, read dispatcher function, which delegates a client to a newly created thread that runs handleCient function. As a result, the server can serve multiple clients simultaneously.

Test your code and make sure the server can serve multiple players simultaneously. To do this, you can (i) run the server in one terminal, (ii) open another terminal to run one client (do not terminate the client), and (iii) open yet another terminal to run the second client.

4 What to Turn In

When you hand in your programming assignment, please include the following (please submit to HuskyCT):

• A program listing containing in-line documentation. Uncommented code will be heavily penalized. Submit both the versions for the basic server and client, as well as the multi- threaded version of the server and client.

• A separate (typed) document describing the overall program design, a verbal description of how it works”, application-level protocol between the server and client, and design tradeoffs considered and made. Also describe possible improvements and extensions to your program (and sketch how they might be made). You only need to provide the design document for the multi-threaded version of the server and client. The format of the description file should be as follows (If your turn-in does not follow the above format, you’ll get 10 points off automatically):

– Description: describe the overall program design, “how it works”, and your application protocol. You can use the application protocols that we have learned (e.g., HTTP, DNS, SMTP) as examples.

– Tradeoffs: discuss the design tradeoffs you considered and made.

– Extensions: describe possible improvements and extensions to your program and describe briefly how to achieve them.

– Test cases: describe the test cases that you ran to convince yourself (and us) that it is indeed correct. Also describe any cases for which your program is known not to work correctly. Please use screenshots to show the results.

5 Grading policy (Total: 100 points)

• Program Listing works correctly: 50 points (shown by testing results) in-line documentation: 10 points quality of design: 10 points

• Design Document

description: 5 points tradeoffs discussion: 5points extensions discussion: 5 points

• Thoroughness of test cases: 15 points

Notes: A full 10 points for quality of design will only be given to well-designed, thorough programs. A correctly working, documented and tested program will not necessarily receive these 10 points.

6 For CSE5299 students; Extra credits for CSE3300 students (20 points)

This is mandatory for CSE5299 students and will give up to 20 extra points for CSE3300 students. Please mark in your submission whether you are in CSE5299 or CSE3300 in your submission. If

you did not mark, your submission will be treated as a CSE3300 submission.

Continue your work on the multi-threaded server and multiple query client. In this part,

1) your server is expected to support queries that contain any number of wildcard(s) and print out the total number of words each response contains,

2) your client is expected to print out the entire response as well as the total number of words contained in the response from the server before making another query.

– e.g. if the client sends just one wildcard (question mark), your client should receive and print out the entire wordlist as well as the total number of words before you make another query.

Grading Policy:

Your program with in-line documentation: 5 points

Thoroughness of your test cases (screenshots for both client side and server side): 5 points

Server prints out the correct number of words contained in each response for all test cases: 5 points.

Client receives the entire response and prints out the correct number of words for all test cases: 5 points

7 A Few Words About Borrowing Code…

As many of you probably already know, there is a wealth of sample socket programming code out on the Web and in books that you can use in your projects. Often learning from sample codes is the best way to learn. I have no problem with your borrowing code as long as you follow some guidelines:

• You must acknowledge the source of any borrowed code. This means providing a reference to a book or URL where the code appears (you don’t need to provide reference for the code that was given to you).

• In your design document, you must identify which portions of your code were borrowed and which were written by yourself. This means explaining any modifications and extensions you made to the code you borrowed. You should also use comments in your source code to distinguish borrowed code from code you wrote yourself.

• You should only use code that is freely available in the public domain.
