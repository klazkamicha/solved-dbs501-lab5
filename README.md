Download Link: https://assignmentchef.com/product/solved-dbs501-lab5
<br>
<ul>

 <li>Write the code for the Function called <strong>Get_Descr</strong> that will for a provided Section Id return its Course DESCRIPTION. Test your Function for a Valid and Invalid input by using BIND variables. Show both tests with Bind variables as well.        <u>Here are the outputs:</u></li>

</ul>




If you test with 150 then:




Course Description for Section Id 150 is Intro to Java Programming

<table width="68%">

 <tbody>

  <tr>

   <td colspan="2"></td>

  </tr>

  <tr>

   <td colspan="2"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

If you test with 999 then:

<table width="61%">

 <tbody>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

 </tbody>

</table>

There is NO such Section id: 999

<u> </u>

<ol start="2">

 <li>Write the code for procedure called <strong>show_bizdays</strong> that will display what business days (NOT Saturday, Sunday) are ahead (present day will be included). It will accept two arguments – start date (it may be any day) and how many business days are needed to show. It will store each date into PL/SQL table. Both arguments will have default values – TODAY and 21 days.</li>

</ol>

Use WHILE LOOP to scan for desired number of business days.

<strong>                                    </strong><u>Here are the outputs  (</u>SYSDATE here is 20-NOV-11)




SQL&gt;  <strong>execute show_bizdays</strong>




The index is : 1 and the table value is: 21-NOV-11

The index is : 2 and the table value is: 22-NOV-11

The index is : 3 and the table value is: 23-NOV-11

The index is : 4 and the table value is: 24-NOV-11

The index is : 5 and the table value is: 25-NOV-11

The index is : 6 and the table value is: 28-NOV-11

The index is : 7 and the table value is: 29-NOV-11

The index is : 8 and the table value is: 30-NOV-11

The index is : 9 and the table value is: 01-DEC-11

The index is : 10 and the table value is: 02-DEC-11

The index is : 11 and the table value is: 05-DEC-11

The index is : 12 and the table value is: 06-DEC-11

The index is : 13 and the table value is: 07-DEC-11

The index is : 14 and the table value is: 08-DEC-11

The index is : 15 and the table value is: 09-DEC-11

The index is : 16 and the table value is: 12-DEC-11

The index is : 17 and the table value is: 13-DEC-11

The index is : 18 and the table value is: 14-DEC-11

The index is : 19 and the table value is: 15-DEC-11

The index is : 20 and the table value is: 16-DEC-11

The index is : 21 and the table value is: 19-DEC-11




PL/SQL procedure successfully completed.




SQL&gt; <strong>execute show_bizdays(sysdate+7,10)</strong>




The index is : 1 and the table value is: 28-NOV-11

The index is : 2 and the table value is: 29-NOV-11

The index is : 3 and the table value is: 30-NOV-11

The index is : 4 and the table value is: 01-DEC-11

The index is : 5 and the table value is: 02-DEC-11

The index is : 6 and the table value is: 05-DEC-11

The index is : 7 and the table value is: 06-DEC-11

The index is : 8 and the table value is: 07-DEC-11

The index is : 9 and the table value is: 08-DEC-11

The index is : 10 and the table value is: 09-DEC-11




PL/SQL procedure successfully completed.

<strong> </strong>

<strong> </strong>

3)   A) Write the Package specification called <strong>Lab5</strong> for the Procedure and Function created for this Lab

<ol>

 <li>B) Then write the Package Body and compile without warnings.</li>

 <li>C) Test your Package by providing input as for Question 2)</li>

</ol>




4)   A) Now OVERLOAD your Package with NEW variation of Procedure <strong>show_bizdays</strong>

that will accept only ONE input parameter – Start Date and will prompt user to enter how many days are needed to show.

<ol>

 <li>B) Compile your package specification and body without warnings</li>

 <li>C) Test your OVERLOADED Procedure (like for Q2 examples) by using your Package</li>

</ol>

<strong> </strong>