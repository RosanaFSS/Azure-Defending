<p align="center">April 15, 2025<br>
Hey there, fellow lifelong learner! I´m <a href="https://www.linkedin.com/in/rosanafssantos/">Rosana</a>, and I’m genuinely excited to join you on this adventure.<br>
It´s part of my $$\textcolor{#FF69B4}{\textbf{344}}$$-day-streak in  <a href="https://tryhackme.com">TryHackMe</a>.<br><br>
<img width="300px" src="https://github.com/user-attachments/assets/077c3a7e-c4d6-435d-a5a1-cb1cc233e817" alt="Your Image Badge"><br>
<img width="200px" src="https://github.com/user-attachments/assets/a831d20b-7256-48cf-8fe9-ad7c930d41e3"></p>
<h1 align="center"> $$\textcolor{#3bd62d}{\textnormal{MS Sentinel : Just Looking}}$$</h1>
<p align="center"><em>Microsoft Sentinel challenge for SOC analysts: incident investigation & threat hunting.</em>.<br>
It is classified as an easy walkthrough.<br>
You can join it for 🆓 using your own virtual machine with openVPN or TryHackMe´s AttackBox if you are subscribed.<br>
Can be accessed clicking  <a href="https://tryhackme.com/room/justlookingn">here</a>.</p>

<p align="center"> <img width="900px" src="https://github.com/user-attachments/assets/252d4d4c-50f6-45dd-95ff-4fd9e2e03929"> </p>

<br>
<br>

<h2>Task 1 . Deploy Microsoft Sentinel Challenge Workspace</h2>


<br>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the question below}}$$ </h3>

<br>

> 1.1. <em>I have successfully started the challenge lab and logged in to the Azure portal.</em><br><a id='1.1'></a>
>> <strong><code>No answer needed</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/ab57d530-ffd1-4926-b7b6-8b77d782d042)

<br>


![image](https://github.com/user-attachments/assets/8ee66ccc-ea65-493b-88dd-205702a20bc9)

<br>

![image](https://github.com/user-attachments/assets/7623bba0-f9a1-4508-aa4a-b8c23575185c)



<br>
<br>

<h2>Task 2 . Logs Ready, Steady, Go!</h2>

<br>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the questions below}}$$ </h3>

<br>

> 2.1. <em>What's the row count for SigninLogs_CL table?</em><br><a id='2.1'></a>
>> <strong><code>930</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/4d6daf55-108a-4488-83d7-0f80b9765e58)

<br>

> 2.2. <em>What's the row count for AuditLogs_CL table?</em><br><a id='2.2'></a>
>> <strong><code>58</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/df73a454-ace2-419c-9300-cb65c1ced125)

<br>

> 2.3. <em>Key combination for running KQL queries in Query Editor?</em><br><a id='2.3'></a>
>> <strong><code>Shift</code></strong><br>
<p></p>

<br>
<br>

<h2>Task 3 . Analytics</h2>

<br>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the questions below}}$$ </h3>

<br>

> 3.1. <em>MITRE ATT&CK sub-technique for rule: Account Created and Deleted in Short Timeframe.</em><br><a id='3.1'></a>
>> <strong><code>T1078.004</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/6b746447-5a9d-4921-a9ac-ac9f3871f250)

<br>

> 3.2. <em>Rule frequency (in hrs) for rule: Attempts to sign in to disabled accounts.</em><br><a id='3.2'></a>
>> <strong><code>1</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/0eae357b-bcd1-4e3a-bd42-2484dfe88263)

<br>

> 3.3. <em>ResultType filter in rule: Explicit MFA Deny.</em><br><a id='3.3'></a>
>> <strong><code>500121</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/6374fce5-d8c4-40a2-9381-3c71761f20e1)

<br>

> 3.4. <em>AppDisplayName filter in rule: Brute force attack against Azure Portal.</em><br><a id='3.4'></a>
>> <strong><code>Azure Portal</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/ffdba478-a8d5-44d7-84b5-89a8514d75c8)

<br>

> 3.5. <em>Category filter in rule: Privileged Role Assigned Outside PIM.</em><br><a id='3.5'></a>
>> <strong><code>RoleManagement</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/08cd53e8-f2f8-4e72-9a1c-336396fc9b5c)

<br>
<br>

<h2>Task 4 . Incident #1: Account Created and Deleted in Short Timeframe</h2>

<br>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the questions below}}$$ </h3>

<br>

> 4.1. <em>How many accounts were created and deleted in a short time frame?</em><br><a id='4.1'></a>
>> <strong><code>5</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/1e142c86-abae-444d-a79c-67bd93a9aed7)

<br>

> 4.2. <em>Which entity deleted these accounts?</em><br><a id='4.2'></a>
>> <strong><code>thmMultiTenantApp</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/74f3fb32-2b89-4e65-a222-de89a1385176)

<br>

> 4.3. <em>Tactic for this incident?</em><br><a id='4.3'></a>
>> <strong><code>Initial Access</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/cecd0427-d24d-4875-9557-5500ed08bcf6)

<br>

> 4.4. <em>Workflow Id involved in this incident?</em><br><a id='4.4'></a>
>> <strong><code>b3f33fbcc5a541dc803a9b9bb7a5105f</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/4caaadbe-2327-4348-874a-205ebf9415d5)

<br>

> 4.5. <em>UPNSuffix</em><br><a id='4.5'></a>
>> <strong><code>tryhackmelabs.onmicrosoft.com</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/d71a27e0-138d-434b-8f48-14c91c3a6753)

<br>
<br>

<h2>Task 5 . Incident #2: Attempts to Sign in to Disabled Accounts</h2>

<br>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the questions below}}$$ </h3>

<br>

> 5.1. <em>What's the IP Address involved in this incident?</em><br><a id='5.1'></a>
>> <strong><code>181.214.151.205</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/131363a6-9413-45cf-8b6c-fde710b2b7a9)

<br>

> 5.2. <em>IP Geolocation (City)</em><br><a id='5.2'></a>
>> <strong><code>Miami</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/12db6a8f-3ca6-43b0-96df-4b8e5f42161d)

<br>

> 5.3. <em>Disabled account?</em><br><a id='5.3'></a>
>> <strong><code>_______________________</code></strong><br>
<p></p>

<br>

> 5.4. <em>ResultType filter in rule?</em><br><a id='5.4'></a>
>> <strong><code>50057</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/fc0c0eec-d3af-4135-8e06-650a19c1d12f)


<br>
<br>

<h2>Task 6 . Incident #3: Explicit MFA Deny</h2>

<br>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the questions below}}$$ </h3>

<br>

> 6.1. <em>Tactic for this incident?</em><br><a id='6.1.'></a>
>> <strong><code>Credential Access</code></strong><br>
<p></p>

<br>


![image](https://github.com/user-attachments/assets/7d8d5a3a-b605-4297-8eb6-7c8f6fb92919)

<br>

> 6.2. <em>How about its technique?</em><br><a id='6.2.'></a>
>> <strong><code>Brute Force</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/fcc2f5eb-2fcb-487f-b299-c5c045d17cda)

<br>

> 6.3. <em>What's the error code when MFA is denied?</em><br><a id='6.3.'></a>
>> <strong><code>__________________________</code></strong><br>
<p></p>

<br>

> 6.4. <em>What's the name of the Access Policy that triggered this MFA during authentication?</em><br><a id='6.4.'></a>
>> <strong><code>__________________________</code></strong><br>
<p></p>

<br>

> 6.5. <em>Which authentication method was used for this MFA?</em><br><a id='6.5.'></a>
>> <strong><code>__________________________</code></strong><br>
<p></p>

<br>

> 6.6. <em>Browser version of the device initiated this authentication?</em><br><a id='6.6.'></a>
>> <strong><code>__________________________</code></strong><br>
<p></p>

<br>

> 6.7. <em>How many entities are mapped in this incident?</em><br><a id='6.7.'></a>
>> <strong><code></code></strong><br>
<p></p>

<br>
<br>

<h2>Task 7 . Incident #4: Privileged Role Assigned Outside PIM</h2>

<br>

<h3 align="left"> $$\textcolor{#f00c17}{\textnormal{Answer the questions below}}$$ </h3>

<br>

> 7.1. <em>Tactic for this incident?</em><br><a id='7.1.'></a>
>> <strong><code>breakglass@tryhackmelabs.onmicrosoft.com</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/e38e425f-4284-433a-b1f7-a0e1b39379c7)

<br>

> 7.2. <em>Which privileged role has been assigned to Marcus?</em><br><a id='7.2.'></a>
>> <strong><code>_________________________________</code></strong><br>
<p></p>

<br>

> 7.3. <em>In which source table has this privilege escalation been logged?</em><br><a id='7.3.'></a>
>> <strong><code>_________________________________</code></strong><br>
<p></p>

<br>

> 7.4. <em>Which other user has been a target?</em><br><a id='7.4.'></a>
>> <strong><code>usr-24052103@tryhackmelabs.onmicrosoft.com</code></strong><br>
<p></p>

<br>


![image](https://github.com/user-attachments/assets/95aaaed5-b2cf-46a7-b665-4b9c3f311588)

<br>

> 7.5. <em>What's the initiating IP Address?</em><br><a id='7.5.'></a>
>> <strong><code>2.59.157.197</code></strong><br>
<p></p>

<br>

![image](https://github.com/user-attachments/assets/91198674-dd43-4f48-b8cd-2073df031253)



<br>
<br>




![image](https://github.com/user-attachments/assets/eff9e255-2dbb-45e4-a900-3fea581620a2)

<br>

![image](https://github.com/user-attachments/assets/faceda52-d89c-4765-90ba-872ae9fed4ae)




<br>
<br>





<br>
<br>

<h1 align="center"> $$\textcolor{#3bd62d}{\textnormal{Room Completed}}$$</h1>
<br>
<p align="center">
<img width="900px" src=""><br>
<img width="900px" src=""></p>


<br>

<h1 align="center"> $$\textcolor{#3bd62d}{\textnormal{My TryHackMe Journey}}$$ </h1>
<br>


<div align="center">

| Date              | Streak   | All Time     | All Time     | Monthly     | Monthly    | Points   | Rooms     | Badges    |
| :---------------: | :------: | :----------: | :----------: | :---------: | :--------: | :------  | :-------: | :-------: |
|                   |          |    Global    |    Brazil    |    Global   |   Brazil   |          | Completed |           |
|   April 15, 2025  |   344    |     279ᵗʰ    |      6ᵗʰ     |     241ˢᵗ   |     2ⁿᵈ    |  94,505  |    666    |   59      |

</div>

<br>

![image](https://github.com/user-attachments/assets/04a9e8d7-7404-4d56-82d0-a437793e1a12)


<p align="center"> Global All Time: 279ᵗʰ<br><br><img width="900px" src="https://github.com/user-attachments/assets/06c4b800-b074-490a-a9b1-40ea694ad503"> </p>

<p align="center"> Brazil All Time: 6ᵗʰ<br><br><img width="900px" src="https://github.com/user-attachments/assets/d874adad-c932-47fd-96dd-aebb76822443"> </p>

<p align="center"> Global monthly: 241ˢᵗ<br><br><img width="900px" src="https://github.com/user-attachments/assets/fff190a0-2031-4c51-9763-40033b36cb71"> </p>

<p align="center"> Brazil monthly: 2ⁿᵈ<br><br><img width="900px" src="https://github.com/user-attachments/assets/04a9e8d7-7404-4d56-82d0-a437793e1a12"> </p>


<br>


<p align="center">Weekly League: 2ⁿᵈ Silver<br><br><img width="300px" src="image](https://github.com/user-attachments/assets/52593b8c-82af-4429-9c0a-89c96d29a23d"> </p>

<br>

<h1 align="center">$$\textcolor{#3bd62d}{\textnormal{Thanks for coming!!!}}$$</h1>

<p align="center">Follow me on <a href="https://medium.com/@RosanaFS">Medium</a>, here on <a href="https://github.com/RosanaFSS/TryHackMe">GitHub</a>, and on <a href="https://www.linkedin.com/in/rosanafssantos/">LinkedIN</a>.</p> 

<br>

<h1 align="center">$$\textcolor{#3bd62d}{\textnormal{Thank you}}$$</h1>
<p align="center"><a href="https://tryhackme.com/p/tryhackme">tryhackme</a>, <a href="https://tryhackme.com/p/zieglers">zieglers</a> and <a href="https://tryhackme.com/p/huamanejard">huamanejard</a> for investing your time and effort to develop this challenge so that I could sharpen my skills!</p>
