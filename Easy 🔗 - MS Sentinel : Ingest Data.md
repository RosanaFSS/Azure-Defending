<p align="center">April 16, 2025<br>
Hey there, fellow lifelong learner! I´m <a href="https://www.linkedin.com/in/rosanafssantos/">Rosana</a>, and I’m genuinely excited to join you on this adventure.<br>
It´s part of my $$\textcolor{#FF69B4}{\textbf{345}}$$-day-streak in  <a href="https://tryhackme.com">TryHackMe</a>.<br><br>
<img width="300px" src="" alt="Your Image Badge"><br>
<h1 align="center"> $$\textcolor{#3bd62d}{\textnormal{MS Sentinel: Ingest Data}}$$</h1>
<p align="center"><em>No logs, no correlation, no analysis, no action. Where is my log data?</em>.<br>
It is classified as an easy-level walkthrough.<br>
It is a premium room: only for subscribers.<br>
Can be accessed clicking  <a href="https://tryhackme.com/room/sentinelingestdata">here</a>.</p>



<p align="center"> <img width="900px" src="https://tryhackme.com/room/sentinelingestdata"> </p>

<br>
<br>

<h2>Task 1 . Getting Ready To Ingest Data</h2>

<p>In the previous <a href="https://github.com/RosanaFSS/Azure-Defending/blob/1.Microsoft-Sentinel/Easy%20%F0%9F%94%97%20-%20MS%20Sentinel%20%3A%20Deploy.md">MS Sentinel: Deploy</a> room, we deployed an instance of Microsoft Sentinel. The next logical phase is to plan and execute the log data ingestion process. In Microsoft Sentinel, logs are sent to Log Analytics workspaces via data connectors.<br><br>

As a Microsoft Security Analyst, it is essential to know how to connect log data from different sources. The organization may have data from Microsoft and non-Microsoft resources as well as on-premise and network appliances.</p>

<h3>Learning Objectives</h3>
<p>In this room, we will look into the options for ingesting data and how to connect them so that Microsoft Sentinel starts to analyze and correlate logs. The main parts of this room will be:<br>

- <code>Data connectors</code><br>
- <code>Content hub</code> solutions<br>
- How to <code>install</code> Content hub solutions<br>
- How to <code>connect</code> data connectors<br><br>

Let's dive in!</p>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the question below}}$$ </h3>

<br>

> 1.1. <em>What is used to ingest log data into Microsoft Sentinel?</em><br><a id='1.1'></a>
>> <strong><code>data connectors</code></strong><br>
<p></p>

<br>
<br>

<h2>Task 2 . Data Connectors Introduction</h2>
<h3>Data Sources and Data Connectors</h3>
<p>...</p>

<br>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the questions below}}$$ </h3>

<br>

> 2.1. <em>Are data connectors specific to each data source? (Yea/Nay)</em><br><a id='2.1'></a>
>> <strong><code>Yea</code></strong><br>
<p></p>

<br>

> 2.2. <em>Data connectors are available in how many ways?</em><br><a id='2.2'></a>
>> <strong><code>2</code></strong><br>
<p></p>

<br>
<br>

<h2>Task 3 . Content Hub Introduction</h2>

<p>...</p>

<br>

<h3>Content Source: Standalone vs. Solutions</h3>

<p>...</p>

<br>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the questions below}}$$ </h3>

<br>

> 3.1. <em>What are bundles of data connectors, workbooks, analytic rules, and playbooks called in Microsoft Sentinel?</em><br><a id='3.1'></a>
>> <strong><code>solutions</code></strong><br>
<p></p>

<br>

> 3.2. <em>Content source can either be a Solution or?</em><br><a id='3.2'></a>
>> <strong><code>standalone</code></strong><br>
<p></p>

<br>
<br>

<h2>Task 4 . Lab Instructions</h2>
<p>...</p>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the question below}}$$ </h3>

<br>

> 4.1. <em>I now know how to connect to the lab environment.</em><br><a id='4.1'></a>
>> <strong><code>No answer needed</code></strong><br>
<p></p>

<br>
<br>

<h2>Task 5 . Lab-02: Install Content Hub Solutions</h2>
<p><code>Context</code>: Your company recently deployed Microsoft Sentinel. However, no Content hub solutions have been installed yet.<br><br>

<code>Role</code>: You are logged in as:<br>

- Microsoft Sentinel Contributor<br>
- Log Analytics Contributor</p>

<br>


<p><code>Lab scenario</code>: Following the initial deployment of Microsoft Sentinel, you are tasked with <code>installing a Content hub solution</code>.<br>

- First, make sure <code>Sentinel is enabled for the workspace</code>.<br>
- Then, you will install a <code>Content hub solution</code><br>
- Finally, you will <code>review</code> the results</code></p>

<br>

<p>Access your lab by clicking the <code>Cloud Details</code> button below in conjunction with the lab instructions from Task 4:</p>

<p>[ Cloud Details ]</p>

<br>

<p>...</p>

<br>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the questions below}}$$ </h3>

<br>

> 5.1. <em>What Content source type is Microsoft Entra ID?</em><br><a id='5.1'></a>
>> <strong><code>Solution</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/8a5ed47d-92c6-4620-a541-3f2ba2cb7a6e)


<br>

> 5.2. <em>What category is the Microsoft Entra ID?</em><br><a id='5.2.'></a>
>> <strong><code>Identity, Security - Automation (SOAR)</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/29c87b79-0734-4fb3-8d05-f0c77216bf79)

<br>


> 5.3. <em>I have installed the Content hub solution Microsoft Entra ID.</em><br><a id='5.3.'></a>
>> <strong><code>No answer needed</code></strong><br>
<p></p>

<br>


![image](https://github.com/user-attachments/assets/6bfe0414-f27e-4bec-b88d-009f710c6282)

<br>

![image](https://github.com/user-attachments/assets/774fe06c-bfa3-4fc1-8c4b-72b8f2a260a9)

<br>

![image](https://github.com/user-attachments/assets/36f12199-185c-46c4-a30e-ff9d150fc74b)


<br>

![image](https://github.com/user-attachments/assets/f577c211-5589-4e57-859e-b2b21d26c5fa)

<br>

![image](https://github.com/user-attachments/assets/2c4421e6-8a65-4a4e-bbf2-825e3a1e8388)

<br>
<br>

<h2>Task 6 . Conencting Data Connectors</h2>
<p>...</p>


<br>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the questions below}}$$ </h3>

<br>

> 6.1. <em>Where can you find all the details about a connector?</em><br><a id='6.1'></a>
>> <strong><code>connector page</code></strong><br>
<p></p>

<br>

> 6.2. <em>In order to configure the Microsoft Entra ID data connector, what permissions are required on the Log Analytics workspace?</em>Hint : <em>Check the prerequisites on the connector page</em><br><a id='6.2.'></a>
>> <strong><code>Microsoft Sentinel Contributor</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/61c34e57-0803-42b8-a6b6-d34141a4d1d9)

<br>

![image](https://github.com/user-attachments/assets/26b903a2-031a-4869-8117-cd397aade976)



<br>
<br>

<h2>Task 7 . Lab-03: Connect and Configure a Data Connector</h2>

<p>...</p>

<br>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the questions below}}$$ </h3>

<br>

> 7.1. <em>What does the Microsoft Defender Threat Intelligence (MDTI) connector import?</em><br><a id='7.1'></a>
>> <strong><code>2</code></strong><br>
<p></p>

<br>

> 7.2. <em>Can threat indicators include IP addresses and domains? (Yea/Nay)</em><br><a id='7.2.'></a>
>> <strong><code>Yea</code></strong><br>
<p></p>

<br>

> 7.3. <em>Let the log data flow!</em><br><a id='7.3.'></a>
>> <strong><code>No answer needed/code></strong><br>
<p></p>

<br>
<br>

<h2>Task 8 . Conclusion</h2>

<p>...</p>

<br>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the question below}}$$ </h3>

<br>

> 8.1. <em>Finally, some logs are flowing into Microsoft Sentinel. Time to put on the SOC Analyst hat!</em><br><a id='8.1'></a>
>> <strong><code>No answer needed</code></strong><br>
<p></p>


<br>
<br>

<h1 align="center"> $$\textcolor{#3bd62d}{\textnormal{Room Completed}}$$</h1>
<br>
<p align="center">
<img width="900px" src="https://github.com/user-attachments/assets/59341d27-9f82-4826-9693-a98175cf2837"><br>
<img width="900px" src="https://github.com/user-attachments/assets/c39d3657-f231-455c-8dda-8e42741a318c"></p>


<br>

<h1 align="center"> $$\textcolor{#3bd62d}{\textnormal{My TryHackMe Journey}}$$ </h1>
<br>


<div align="center">

| Date              | Streak   | All Time     | All Time     | Monthly     | Monthly    | Points   | Rooms     | Badges    |
| :---------------: | :------: | :----------: | :----------: | :---------: | :--------: | :------  | :-------: | :-------: |
|                   |          |    Global    |    Brazil    |    Global   |   Brazil   |          | Completed |           |
|   April 16, 2025  |   345    |     277ᵗʰ    |      6ᵗʰ     |     80ᵗʰ    |     2ⁿᵈ    |  94,835  |    668   |   59      |

</div>

<br>


<p align="center"> Global All Time: 277ᵗʰ<br><br><img width="1000px" src="https://github.com/user-attachments/assets/e5fcaee3-a6d6-4bcd-af39-0b8c54d92caf"> </p>

<p align="center"> Brazil All Time:   6ᵗʰ<br><br><img width="1000px" src="https://github.com/user-attachments/assets/8d69d8df-e5a0-4d0d-ae51-6be78950c941"> </p>

<p align="center"> Global monthly:   80ᵗʰ<br><br><img width="1000px" src="https://github.com/user-attachments/assets/8ad28120-50fd-41f1-8971-0b706a3c41e2"> </p>

<p align="center"> Brazil monthly:     2ⁿᵈ<br><br><img width="1000px" src="https://github.com/user-attachments/assets/567a82aa-682a-4911-8877-d3c26a55a6dd"> </p>



<br>


<p align="center">Weekly League: 2ⁿᵈ Silver<br><br><img width="1000px" src="https://github.com/user-attachments/assets/5e92f57e-f3f1-403a-b89b-1a9e6b5313ce"> </p>

<br>

<br>

<h1 align="center">$$\textcolor{#3bd62d}{\textnormal{Thanks for coming!!!}}$$</h1>
<p align="center">Follow me on <a href="https://medium.com/@RosanaFS">Medium</a>, here on <a href="https://github.com/RosanaFSS/TryHackMe">GitHub</a>, and on <a href="https://www.linkedin.com/in/rosanafssantos/">LinkedIN</a>.</p> 

<br>

<h1 align="center">$$\textcolor{#3bd62d}{\textnormal{Thank you}}$$</h1>
<p align="center"><a href="https://tryhackme.com/p/tryhackme">tryhackme</a>, <a href="https://tryhackme.com/p/zieglers">zieglers</a> and <a href="https://tryhackme.com/p/huamanejard">huamanejard</a> for investing your time and effort to develop this challenge so that I could sharpen my skills!</p>
