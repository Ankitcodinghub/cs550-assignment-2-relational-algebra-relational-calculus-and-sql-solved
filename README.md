# cs550-assignment-2-relational-algebra-relational-calculus-and-sql-solved
**TO GET THIS SOLUTION VISIT:** [CS550 Assignment 2-Relational Algebra, Relational Calculus, and SQL Solved](https://www.ankitcodinghub.com/product/cs550-home-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117958&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS550 Assignment 2-Relational Algebra, Relational Calculus, and SQL Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (4 votes)    </div>
    </div>
Queries: Relational Algebra, Relational Calculus, and SQL

Relational Schemas Meaning and additional information

department (dcode, dname, chair) Department identified by dcode is named dname and has department chair with ssn chair (this ssn must appear in the table faculty below)

course (dcode, cno, title, units) Course identified by (dcode,cno) has title

and units (e.g., 3 units/credits) . (dcode must appear in the table department)

prereq (dcode, cno, pcode, pno) Course (dcode, cno) has a prerequisite course (pcode, pno). Both pairs of courses must appear in the table course.

faculty (ssn, name, dcode, rank) Faculty identified by ssn has a name and rank, and belongs to department dcode (which must appear in the table department)

student (ssn, name, major, status) Student identified by ssn has a name, major and status.

enrollment (class, ssn) Student identified by ssn is enrolled in the class identified by class no (ssn must appear in the table student, and class must appear in the table class)

transcript (dcode, cno, ssn, grade) Student identified by ssn took the course identified by (dcode, cno) and received the grade. Assume that the only grades available are A, B, C and F. (ssn must appear in the table student; dcode and cno must appear in the table course.

Implement the following queries using:

A. Relational calculus, in the file ha2lib_calculus.py in the folder solution_calculus. Create initial template of ha2lib_calculus.py by duplicating ha2lib_calculus_template.py

B. Relational algebra, in the file ha2lib_algebra.py in the folder solution_algebra. Create initial template of ha2lib_algebra.py by duplicating ha2lib_algebra_template.py

C. SQL, in the file sql_views.sql in the folder solution_sql. Create initial template of

sql_views.sql by duplicating sql_views_template.sql

a. Find students (ssn, name, major, status) who have taken the course “cs530” (must be in transcripts). Order the result by ssn.

b. Find students (ssn, name, major, status) named “John” (i.e., name = “John” in student)

who have taken the course “CS 530” (must be in transcripts). Order the result byssn.

c. Find students (ssn, name, major, status) who satisfied all prerequisites of each class they are enrolled in. Order the result byssn.

d. Find students (ssn, name, major, status) who are enrolled in a class forwhich they have not satisfied all its prerequisites. To satisfy the prerequisite, the student needs to have obtained grade “B” or higher. Order the result byssn.

e. Find students (ssn, name, major, status) named “John” who are enrolled in a class for which they have not satisfied all its prerequisites. To satisfy the prerequisite, the student needs to have obtained the grade “B” or higher.Order the result byssn.

f. Find courses (dcode, cno) that do not have prerequisites. Order the resultby dcode, cno.

g. Find courses (dcode, cno) that do have some prerequisites. Order the resultby dcode, cno.

h. Find classes (class, dcode, cno, instr) that are offered this semester and haveprerequisites. Order the result byclass.

i. Find students (ssn, name, major, status) who received only the grades “A”or “B” in every course they have taken (must appear in Transcripts). Order the results byssn.

k. Find students (ssn) from the enrollment table who are enrolled in allclasses. Order the result byssn.

l. Find CS students (ssn) from the enrollment table who are enrolled in allmath classes (dcode = “MTH”). Order the result byssn.

Instructions for coding algebra, calculus and SQL queries:

1. Download and unpack archive cs450_550_ha2_univ_db_template.zip. It has a number of files and folders. If you use ATOM studio (which I recommend), under

“File”, choose “Add Project Folder” and select folder cs450_550_ha2_univ_db_template (the root folder). If you don’t use ATOM studio, you can use any IDE that has syntax binding for SQL, JSON (Java Script Object Notation) and Python.

2. As described in “ha2_instructions.txt”, install:

a. Python 3.5 or higher

b. cx_oracle python module

c. cx_oracle client

d. recommended: ATOM studio (alternatively you can use any other IDE which has syntax binding for SQL, JSON and Python

3. Assume a JSON database of the form as given in the file

“testDBs/sampleUnivDB.json” (see file in the root folder). The meaning of the stored info is self-explanatory. For the purpose of queries below, assume that the possible grades are A, B, C and F; and that to satisfy a prerequisite for a class/course means to have taken the prerequisite courses (in transcript) with the grade of B or better.

4. Create the file “credentials.py” by duplicating the file “credentials_template.py which is in the solution_sql folder. Fill it with your Oracle DBMS credentials.

5. Implement the queries in by filling out the templates in the following files (note: see examples described in 8). Create the files by duplicating and renaming the files ending with “…_template.py”.

a. Relational algebra: solution_algebra/ha2lib_algebra.py

b. Tuple relational calculus: solution_calculus/ha2lib_calculus.py

c. SQL: solution_sql/sql_views.sql

6. To check your queries, you need to use your command line and change your current working directory to the respective folder. For example: change your working directory to solution_algebra for algebra queries.

7. To check the syntax of your queries and make it for the sample database, use the following (note: it only prints the output):

a. Relational algebra: ha2_test_algebra.py

b. Tuple relational calculus: ha2_test_calculus.py

c. SQL: ha2_test_sql.py

→ E.g., for algebra go to folder solution_algebra in command line.

→ Run in command line:

&gt;&gt;&gt; python3 ha2_test_algebra.py &gt; out.json

8. Example of the queries discussed in class has been provided for all 3 types of

queries in their respective folder. The query files have the format class_example_&lt;type&gt;.py To see the outputs these files produce, you can use class_example_main_&lt;type&gt;.py. E.g., for algebra, run &gt;&gt;&gt; python class_example_main_algebra.py &gt; out.json and see the results in out.json file.

9. Note that the file testDBs/correct_answers.json contains the correct answer to queries. You can use it for debugging your queries.

10. The folder testDBs also contains JSON files db1.json, db2.json, … which are the databases against which your queries are being tested at the end. So, you can also view these (do not edit anything inside these) to debug your quries.

11. To check your queries, run

&gt;&gt;&gt; python3 ha2_produce_answers_main_&lt;type&gt;.py

in the respective folder. This will print some status about what is being executed

and finally at the end the output as well. Finally, this will also save your output in answers.json in the same folder. You can also view this for debugging purposes as this contains exactly what output your script is generating for the corresponding databases.

→ E.g., for sql go to folder solution_sql in command line.

→ Run in command line:

&gt;&gt;&gt; python3 ha2_produce_answers_main_sql.py

12. Finally, to get the report of your generated answer, run &gt;&gt;&gt; python3 report_unordered.py

in the command line of the respective folder. This will generate (or update) the file report.json which contains the report.

13. Open report.json in Atom (or your other preferred IDE): you can see how many correct queries you have out of total queries, and it gives you a per query report, including for which test databases it produced correct vs. incorrect answer. It is convenient to prettify report.json, and collapse it before you open the relevant parts.

14. Also, do not forget to go through the ha2_instructions.txt thoroughly before you start to write your queries.
