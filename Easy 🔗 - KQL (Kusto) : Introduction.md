<p align="center">April 15, 2025<br>
Hey there, fellow lifelong learner! I´m <a href="https://www.linkedin.com/in/rosanafssantos/">Rosana</a>, and I’m genuinely excited to join you on this adventure.<br>
It´s part of my $$\textcolor{#FF69B4}{\textbf{344}}$$-day-streak in  <a href="https://tryhackme.com">TryHackMe</a>.<br><br>
<img width="300px" src="" alt="Your Image Badge"><br>
<img width="200px" src="https://github.com/user-attachments/assets/a831d20b-7256-48cf-8fe9-ad7c930d41e3"></p>
<h1 align="center"> $$\textcolor{#3bd62d}{\textnormal{KQL (Kusto): Introduction}}$$</h1>
<p align="center"><em>This room introduces you to Kusto Query Language and provides an overview of Microsoft Sentinel.</em>.<br>
It is classified as an easy walkthrough.<br>
You can join it for 🆓 using your own virtual machine with openVPN or TryHackMe´s AttackBox if you are subscribed.<br>
Can be accessed clicking  <a href="https://tryhackme.com/room/kqlkustointroduction">here</a>.</p>

<p align="center"> <img width="900px" src="https://github.com/user-attachments/assets/8c473b43-224e-4c60-9727-df8c51d761fa"> </p>

<br>
<br>

<h2>Task 1 . Introduction</h2>

<p>This room introduces you to the analysis of security logs with Microsoft Sentinel KQL. As security engineers, we think of security logs as treasures because they can help us discover the hidden activities within our infrastructure. A quick background intro: Microsoft Sentinel is a cloud-native security information and event management (SIEM) product that utilizes ingested logs to provide better visibility into your environment. On the other hand, Kusto Query Language (KQL) is the tool used to proactively reveal the hidden secrets within those logs if you are the curious and hands-on type.<br><br>

Imagine being able to:<br>

- Track down rogue user activities accurately and identify potential breaches before they happen.<br>
- Unravel complex security incidents by correlating events and figuring out every attacker's moves.<br>
- Automating repeated tasks to focus on more serious threats and investigations.</p>

<br>
<p>The focus of this room is Kusto Query Language (KQL), which empowers you, the security analyst/engineer, to become a security sleuth, proactively hunting for threats to ensure your organization's digital infrastructure is safe from attackers. Let's dive into the world of KQL to discover the power of security logs analysis.</p>

<br>

<h3>Learning Objectives</h3>
<p>This room aims to provide you with the fundamental knowledge and skills necessary to use Kusto Query Language (KQL) for security analysis within MS Sentinel Log Analytics workspace. Upon completion, you will be able to:<br>

- Better understand the core concepts and functionalities of Microsoft Sentinel as a Security Information and Event Management (SIEM) solution.<br>
- Easily understand the benefits of using Kusto Query Language (KQL) in Microsoft Sentinel for day-to-day security operations.<br>
- Understand how KQL interacts with data stored within MS Sentinel Log Analytics workspaces and its uses in querying and analyzing them.</p>

<br>


<h3>Prerequisites</h3>
<p>- Having completed the Microsoft Sentinel module.</p>



<br>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the question below}}$$ </h3>

<br>

> 1.1. <em>Let's go!</em><br><a id='1.1'></a>
>> <strong><code>No answer needed</code></strong><br>
<p></p>



<br>
<br>

<h2>Task 2 . Overview of Microsoft Sentinel</h2>

<br>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the questions below}}$$ </h3>

<br>

> 2.1. <em>In addition to being a SIEM solution, what else is Microsoft Sentinel? (use the abbreviation)</em><br><a id='2.1'></a>
>> <strong><code>SOAR</code></strong><br>
<p></p>

<br>

> 2.2. <em>How does MS Sentinel support other security solutions that are not included in the built-in connectors? </em><br><a id='2.2'></a>
>> <strong><code>REST API integration</code></strong><br>
<p></p>

<br>
<br>

<h2>Task 3 . What is KQL</h2>

<br>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the questions below}}$$ </h3>

<br>

> 3.1. <em>What initial service was KQL created for?</em><br><a id='3.1'></a>
>> <strong><code> Azure Data Explorer</code></strong><br>
<p></p>

<br>

> 3.2. <em>Analyze the example query from the task. How many computers will the query return?</em><br><a id='3.2'></a>
>> <strong><code>10</code></strong><br>
<p></p>

<br>

> 3.3. <em>What table is the example query retrieving its data from?</em><br><a id='3.3'></a>
>> <strong><code>Heartbeat</code></strong><br>
<p></p>

<br>
<br>

<h2>Task 4 . KQL Concepts in Microsoft Sentinel</h2>

<br>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the questions below}}$$ </h3>

<br>

> 4.1. <em>What operator can be used to output results in graphical form?</em><br><a id='4.1'></a>
>> <strong><code>render</code></strong><br>
<p></p>

<br>

> 4.2. <em>What operator can be used to filter a specified table based on specified conditions?</em><br><a id='4.2'></a>
>> <strong><code>where</code></strong><br>
<p></p>

<br>

> 4.3. <em>What user account name was queried in our second example query above?</em><br><a id='4.3'></a>
>> <strong><code>JBOX00$</code></strong><br>
<p></p>


<br>
<br>

<h2>Task 5 . KQL Statement Structure</h2>

<br>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the questions below}}$$ </h3>

<br>

> 5.1. <em>What is the name of the table queried in our example query?</em><br><a id='5.1'></a>
>> <strong><code>SecurityEvent</code></strong><br>
<p></p>

<br>

> 5.2. <em>Analyze the example query from the task. What does the query aggregate per computer?</em><br><a id='5.2'></a>
>> <strong><code>EventCount</code></strong><br>
<p></p>

<br>
<br>

<h2>Task 6 . KQL Use Cases</h2>

<p>Congratulations! You did it. I am confident that you now understand the concept and structure of KQL queries. Let's explore real-world scenarios to see how KQL can support you, the security analyst, in gaining deeper insights into your security logs.</p>

<br>

<h3>Real-Life Example</h3>

<br>
<br>

<h2>Task 7 . Conclusion</h2>

<h3>Summary</h3>
<p>Let's summarise what we have learned so far:<br><br>

We discussed MS Sentinel as a robust SIEM solution that enables organizations to easily identify, investigate, and respond to security threats. KQL, on the other hand, is an effective method of querying and analyzing security logs. When combined, they form a holistic security operations tool for securing modern digital infrastructure.<br><br>

As we continue to explore KQL, you'll discover its extensive capabilities for enhancing your organization's overall security posture.</p>

<br><br>

<h3>Learning Curve</h3>
<p>To become a skilled security analyst and threat hunter, here are some pointers to get you going:<br>

- Start simple: Begin with basic queries to identify core security events, and gradually progress to more complex ones as you gain confidence.<br>
- Practice makes perfect: The more you practice writing KQL queries, the more comfortable and proficient you'll become.<br>
- Unlock potential: As your KQL proficiency grows, you can delve into advanced concepts like joins, parse, and user-defined functions. These offer even greater capabilities for complex data analysis and threat-hunting scenarios.</p>

<br>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the question below}}$$ </h3>

<br>

> 7.1. <em>I am ready to learn more about KQL in the KQL (Kusto): Basic Queries room.</em><br><a id='7.1'></a>
>> <strong><code>No answer needed</code></strong><br>
<p></p>

<br>
<br>
