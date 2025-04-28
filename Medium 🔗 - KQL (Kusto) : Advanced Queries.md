<p align="center">April 28, 2025<br>
Hey there, fellow lifelong learner! I´m <a href="https://www.linkedin.com/in/rosanafssantos/">Rosana</a>, and I’m genuinely excited to join you on this adventure.<br>
It´s part of my $$\textcolor{#FF69B4}{\textbf{357}}$$-day-streak in  <a href="https://tryhackme.com">TryHackMe</a>.<br><br>
<img width="300px" src="" alt="Your Image Badge"><br></p>
<h1 align="center"> $$\textcolor{#3bd62d}{\textnormal{KQL (Kusto): Advanced Queries}}$$</h1>
<p align="center"><em>Learn about advanced KQL queries and how to leverage the power of Microsoft KQL.</em>.<br>
It is classified as a medium-level walkthrough.<br>
You can join it for 🆓 using your own virtual machine with openVPN or TryHackMe´s AttackBox if you are subscribed.<br>
Can be accessed clicking  <a href="https://tryhackme.com/room/kqlkustoadvancedqueries">here</a>.</p>


<p align="center"> <img width="1000px" src="h"> </p>


<br>
<br>


<h2>Task 1 . Introduction </h2>
<p>[ ... ]</p>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the question below}}$$ </h3>

<br>

> 1.1. <em>I am ready to go advanced!</em><br><a id='1.1'></a>
>> <strong><code>No answer needed</code></strong><br>
<p></p>

<br>
<br>

<h2>Task 2 . Using the Join Operator </h2>
<p>[ ... ]</p>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the questions below}}$$ </h3>

<br>

> 2.1. <em>Which join flavor returns all the records from the left table and only matching values from the right table?</em><br><a id='2.1'></a>
>> <strong><code>Kind=leftouter</code></strong><br>
<p></p>

<br>

> 2.2. <em>Which join flavor contains a row in the output for every matching row combination from both tables?</em><br><a id='2.1'></a>
>> <strong><code>Kind=inner</code></strong><br>
<p></p>

<br>
<br>

<h2>Task 3 . Using the Union Operator</h2>
<p>[ ... ]</p>

<h3>Combining Two Tables</h3>

![image](https://github.com/user-attachments/assets/c158cf56-2a02-4f7e-a703-44dc0a7500fc)


<br>

<h3>Combining Single Columns From Different Tables</h3>

![image](https://github.com/user-attachments/assets/b6e0e06b-97da-4eb7-991c-135a2519fa3f)


<br>

<h3>Combining Multiple Columns From Different Tables</h3>

![image](https://github.com/user-attachments/assets/a4d58503-6455-44df-9818-aa5fcdb7f6df)



<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the questions below}}$$ </h3>

<br>

> 3.1. <em>Can the union operator return all rows from both tables? (Yea/Nay)</em><br><a id='3.1'></a>
>> <strong><code>Yea</code></strong><br>
<p></p>

<br>

> 3.2. <em>Run the "Combining Multiple Columns From Different Tables" query and modify the time range. What is the threat status detail?</em>Hint : <em>Check the ThreatStatusDetails</em><br><a id='3.1'></a>
>> <strong><code>Threat Status is currently not supported in MDATP</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/90609c91-6c31-46d5-a0d4-ee0858ca389f)

<br>
<br>

<h2>Task 4 . Using the Project Operator</h2>
<p>[ ... ]</p>

<h3>Project Specific Columns</h3>

<br>

<h3>Using "Project-Keep" To Select What Columns To Return</h3>

<br>

<h3>Using "Project-Away" To Discard Columns From the Output</h3>
<p>The query below retrieves the SecurityEvent table for machines for the past 5 days and removes the columns defined.</p>


![image](https://github.com/user-attachments/assets/656add3f-8bb5-4ee6-8744-f457856a32df)

<br>


<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the questions below}}$$ </h3>

<br>

> 4.1. <em>Which project operator sets the column order in the resulting output?</em><br><a id='4.1'></a>
>> <strong><code>project-reorder</code></strong><br>
<p></p>

<br>

> 4.2. <em>Run the "Combining Multiple Columns From Different Tables" query and modify the time range. What is the threat status detail?</em>Hint : <em>Check the ThreatStatusDetails</em><br><a id='4.1'></a>
>> <strong><code>Yea</code></strong><br>

<br>
<br>

<h2>Task 5 . Using the Extend Operator</h2>
<h3>Extend Operator</h3>
<p>By using the extend operator, you can create newly calculated columns in a query's output. However, unlike the project operator, which can also rename and remove columns, the extend operator retains all existing columns and appends the new columns to the result.</p>

<p>[ ... ]</p>

<h3>Using Extend To Create a New Calculated Column (TimeSinceReboot)</h3>

![image](https://github.com/user-attachments/assets/56373499-4f03-42d7-bae7-33e237dadd79)

<br>

<h4>Creating a New Calculated Column With Values</h4>
<p>This query adds a new calculated column, EventCategory, and populates the eventID 4624 as logon and 4634 as logoff, while other event IDs are treated as others.</p>

![image](https://github.com/user-attachments/assets/660decf4-9790-47db-81e5-93c1f11a87de)

<br>

<h3>Using Extend To Calculate Free Disk Spaces</h3>
<p>The query below uses the extend operator to create a new calculated column called FreeSpaceinGB and input the value of the CounterValue column when converted to gigabytes by dividing its value by 1000.
</p>

![image](https://github.com/user-attachments/assets/3fe7f3ec-64fc-4236-953c-d97d38ed3d21)

<br>


<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the question below}}$$ </h3>

<br>

> 5.1. <em>Run the "Using Extend To Calculate Free Disk Spaces" query mand modify the time range. What new column is created?</em><br><a id='5.1'></a>
>> <strong><code>FreeSpaceinGB</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/3fe7f3ec-64fc-4236-953c-d97d38ed3d21)

<br>

> 5.2. <em>What is the event category for event ID 4624?</em><br><a id='5.2'></a>
>> <strong><code>FreeSpaceinGB</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/660decf4-9790-47db-81e5-93c1f11a87de)

<br>

