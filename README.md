# 🖥️ Execution Unit
<div align="center">
<img   width= 350px height =350px src="https://user-images.githubusercontent.com/71986226/156400559-7b798b35-b67c-4f05-b371-671a39abe75e.png">
</div>

<hr style="background-color: #4b4c60"></hr>

## 📝 Table of Contents

- <a href ="#about"> 📙 About</a>
- <a href ="#use"> 💻 Get Started</a>
- <a href ="#Screenshots"> 📷 Demo Screenshots</a>
- <a href ="#Contributors"> ✨ Contributors</a>
<hr style="background-color: #4b4c60"></hr>


## 📙 About <a id = "about"></a>

<p>Using the simulation program (Altera Quartus), it is required to make an execution unit that
able to do the following commands:
<ul>
<li> Move Value to Register</li>
<li> Move Register to Register</li>
<li> Add Value to Register</li>
<li> Add Register to Register</li>
<li> AND Value to Register</li>
<li> AND Register to Register</li>
</ul>
</p>

<hr style="background-color: #4b4c60"></hr>

## 🚀 How use the application  <a id ="use"></a>

<ol>
<li> Clone the repository

```
git clone https://github.com/EslamAsHhraf/Execution_Unit
```

</li>
<hr>
<li> Main File is 

```
Execution_Unit/Execution Unit/ExecutionUnit.bdf
```
</li>
<hr>
<li>
How many commands does the execution unit have?
<p>
<b>6 commands:</b>
<br>
<ul>
    <li> Move Value to Register</li>
    <li> Move Register to Register</li>
    <li> Add Value to Register</li>
    <li> Add Register to Register</li>
    <li> AND Value to Register</li>
    <li> AND Register to Register</li>
</p>
</li>
</ul>
<hr>
<li>
How many bits are required for the user input command?
<p>
<b>10 bits:</b>

<table>
<tr><th>1.&ensp; [1..0] destination (00,01,10)</th> </tr>
<tr><th>2.&ensp; [3..2] source (00 A, 01 B, 10 C, 11 input)</th></tr>
<tr><th>3.&ensp; [5..4] operation (00 MOV ,10 ADD ,11 AND)</th></tr>
<tr><th>4. &ensp;[9..6] input</th></tr>
</table>
</p>
</li>
<hr>
<li>
How many forbidden input commands do execution unit have?
<p>
<table>
<tr><th>1. &ensp;[1..0]= `11` the input can’t be destination</th> </tr>
<tr><th>2. &ensp;[5..4]=`01` there is no operation</th></tr>
</table>
<b>EX:</b>&ensp; 1111010011 (invalid)
</p>
</li>
</ol>

<hr style="background-color: #4b4c60"></hr>


## 📸 Demo Screenshots <a id ="Screenshots"></a>

![image](https://user-images.githubusercontent.com/71986226/154477737-3ee9f702-c7d7-48b3-a7c9-81a4404fc420.png)

<hr>

![image](https://user-images.githubusercontent.com/71986226/154478022-cb72d049-a85b-4603-a0e1-936d51d89008.png)
<hr>

![image](https://user-images.githubusercontent.com/71986226/154478143-8ce3937b-8c9c-4f77-a769-9c5b7a4951b1.png)
<hr>

![image](https://user-images.githubusercontent.com/71986226/154477592-60f76602-c47a-4303-ae18-a0dd0b056865.png)


<hr style="background-color: #4b4c60"></hr>

## 👑 Contributors <a id ="Contributors"></a>

<table >
  <tr>
     <td align="center"><a href="https://github.com/EslamAsHhraf"><img src="https://avatars.githubusercontent.com/u/71986226?v=4" width="150px;" alt=""/><br /><sub><b>Eslam Ashraf</b></sub></a><br /></td>
  </tr>
</table>
