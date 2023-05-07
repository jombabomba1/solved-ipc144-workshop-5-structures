Download Link: https://assignmentchef.com/product/solved-ipc144-workshop-5-structures
<br>
In this workshop, you will code a C-language program with an object of structure type.




<strong>LEARNING OUTCOMES </strong>

Upon successful completion of this workshop, you will have demonstrated the abilities:

<ul>

 <li>to store data of different types using a structure type</li>

 <li>to declare an object of structure type</li>

 <li>to access the members of an object of structure type</li>

 <li>to describe to your instructor what you have learned in completing this workshop</li>

</ul>

<strong>Late submission penalties</strong>:

<ul>

 <li>In-lab portion submitted late, with at-home portion: 0 for in-lab. Maximum of 70/70 for at-home and reflection</li>

 <li>If any of in-lab, at-home or reflection portions is missing the mark will be <u></u></li>

</ul>

<h2>IN-LAB:</h2>

Download or clone workshop 5 (<strong>WS05</strong>) from <a href="https://github.com/Seneca-144100/IPC-Workshops"><strong>https://github.com/Seneca</strong></a><a href="https://github.com/Seneca-144100/IPC-Workshops"><strong>–</strong></a><a href="https://github.com/Seneca-144100/IPC-Workshops"><strong>144100/IPC</strong></a><a href="https://github.com/Seneca-144100/IPC-Workshops"><strong>–</strong></a><a href="https://github.com/Seneca-144100/IPC-Workshops"><strong>Workshops</strong></a> <strong> </strong>

Write your code for this segment in the <strong>emp_inlab.c</strong> file provided with the Visual Studio template project inside the <strong>in-lab</strong> folder.




In this workshop segment, you will implement, Add and Display employee data functionality using C structs and arrays.

<h2>OVERVIEW</h2>

The <strong>emp_inlab.c</strong> <strong>template file</strong> has the following already implemented instructions:

<ul>

 <li>Display a menu list as shown in the following inside a do-while loop construct:</li>

</ul>




<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>            Exit</li>

</ol>

<ul>

 <li>Capture user input for the above options. Store to an <strong>int </strong>variable named “option”</li>

</ul>







<ul>

 <li>Ability to iterate multiple menu choices (until 0 is entered) with required selection construct to direct process flow to the required logic/functionality (using switch). Refer to the comments for each case to identify the functionality required.</li>

</ul>







<ul>

 <li>Display an error message for invalid menu option selections in the <strong>default</strong> case</li>

 <li>Initial output information for menu options 1 and 2 is provided with the relevant formatting.</li>

</ul>










You are required to complete the following.




<ul>

 <li>Define the number of employees <strong>SIZE</strong> to be 2 using the #<strong>define</strong> directive and inserting it between the library directive and the main function definition (you will increase this value later)</li>

 <li>Declare a struct to represent employee data, which has the following information o An identification number stored in an <strong>int</strong> o Age stored in an <strong>int</strong>  o Salary stored in a <strong>double</strong></li>

 <li>Declare an array of Employee <strong>struct</strong>’s named <strong>emp</strong> that can hold <strong>SIZE</strong></li>

</ul>

Initialize all of the elements and their member variables to be 0. (Hint: You can assign    <strong>{ {0} }</strong> to <strong>emp</strong> at the time of declaration).

<h3>IMPLEMENT EXIT PROGRAM FUNCTIONALITY IN CASE 0</h3>

Print the exiting message.




&gt; Exiting Employee Data Program. Good Bye!!! &lt;

<h3>IMPLEMENT DISPLAY FUNCTIONALITY IN CASE 1</h3>

<ul>

 <li>Display the elements of the <strong>struct</strong> <strong>emp</strong> Only display the <strong>valid</strong> employee data</li>

</ul>

(“<em>Employee ID, Employee Age</em> and<em> Employee Salary</em>”).  Do not display any other data. <strong>Hint:</strong> If the identification number is positive, then it is <strong>valid</strong> employee data.  Use the following formatting in a <strong>printf</strong> statement:




%6d%9d%11.2lf   ß→  (<em>Employee ID, Employee Age</em> and<em> Employee Salary</em>)




<ul>

 <li>After completing the display, enter a newline using a <strong>printf</strong></li>

</ul>

<h3>IMPLEMENT ADD EMPLOYEE FUNCTIONALITY IN CASE 2</h3>

<ul>

 <li>Keep track of the number of valid employees using an <strong>int</strong></li>

 <li>Check if the <strong>struct</strong> <strong>emp</strong> array is full.</li>

 <li>If the array is full, display the following error message.</li>

</ul>




<h4>&gt; ERROR!!! Maximum Number of Employees Reached &lt;</h4>




<ul>

 <li>If the array is not full, accept new employee data (“<em>Employee ID, Employee Age</em> and<em> Employee Salary</em>”) as per the program output listed below and store that data in an empty element of the <strong>struct</strong><strong> emp</strong> array. Increment the number of valid employees as required.</li>

</ul>

<h3><u>PROGRAM COMPLETION</u></h3>

Your program is complete if your output matches the following output. Red numbers show the user’s input.




—=== EMPLOYEE DATA ===—




<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>2</strong>




Adding Employee

===============

Enter Employee ID: <strong>111</strong>

Enter Employee Age: <strong>34</strong>

Enter Employee Salary: <strong>78980.88</strong>

<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>2</strong>




Adding Employee

===============

Enter Employee ID: <strong>112</strong>

Enter Employee Age: <strong>41</strong>

Enter Employee Salary: <strong>65000</strong>




<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>2</strong>




Adding Employee

=============== ERROR!!! Maximum Number of Employees Reached




<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>1</strong>




EMP ID  EMP AGE EMP SALARY

======  ======= ==========

<ul>

 <li>34 88</li>

 <li>41 00</li>

</ul>




<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>0</strong>




Exiting Employee Data Program. Good Bye!!!

<strong>IN_LAB SUBMISSION:</strong>

To test and demonstrate execution of your program use the same data as the output example above or any information needed.

If not on matrix already, upload your <strong>emp_inlab.c</strong> to your matrix account. Compile and run your code and make sure everything works properly.

Then run the following script from your account and follow the instructions (replace profname.proflastname with your professors Seneca userid and <u>replace</u> <strong>NAA</strong> with <u>your</u> section):

<strong> </strong>

<strong>~profname.proflastname/submit 144w5/NAA_lab &lt;ENTER&gt;  </strong>




<h1>Please Note</h1>

<ul>

 <li>A successful submission does not guarantee full credit for this workshop.</li>

 <li>If the professor is not satisfied with your implementation, your professor may ask you to resubmit. Resubmissions will attract a penalty.</li>

</ul>




<h2>AT_HOME: (30%)</h2>

Copy all of the in-lab code into the “<strong>emp_athome.c</strong>” file, which you will find in the <strong>at-home</strong> folder. Implement the following cases to <strong>emp_athome.c</strong> file.

<ul>

 <li>Change the value of <strong>SIZE</strong> to 4.</li>

 <li>Expand the menu list (printing) to include options 3 &amp; 4 after option 2 with the following</li>

</ul>




<ul>

 <li>Update Employee Salary</li>

 <li>Remove Employee</li>

</ul>




<ul>

 <li>Create two switch-cases for option 3 &amp; 4 after case 2. Do not forget to include <strong>break;</strong> statements at the end of each case.</li>

</ul>

<h3>IMPLEMENT UPDATE EMPLOYEE DATA FUNCTIONALITY IN CASE 3</h3>




<ul>

 <li>Display the following initially</li>

</ul>




<h4>&gt; Update Employee Salary &lt;    &gt; ====================== &lt;</h4>

<ul>

 <li>Prompt the user for the employee identification number using a <strong>do-while</strong> While the number is not found in the employee array, keep prompting the user.</li>

 <li>Once the number is found, display the current salary for the employee with that identification number and prompt the user to input the new salary. Replace the old salary with the input value.</li>

</ul>

<h3>IMPLEMENT REMOVE EMPLOYEE FUNCTIONALITY IN CASE 4</h3>

<ul>

 <li>Display the following initially</li>

</ul>




<h4>&gt; Remove Employee &lt;    &gt; =============== &lt;</h4>




<ul>

 <li>Copy and paste from case 3 the <strong>do-while</strong> loop that prompts the user for the employee identification number.</li>

 <li>Once the number is found, display the following message and ONLY change the employee identification number to indicate an empty slot (or invalid record).</li>

</ul>




<h4>&gt; Employee [REPLACE WITH EMP ID] will be removed &lt;</h4>




<ul>

 <li>Decrement the valid employee count by one</li>

 <li><strong>DO <u>NOT</u> REORDER</strong> the items in the array!</li>

</ul>

<h3><u>PROGRAM COMPLETION</u></h3>

Your program is complete, if your output matches the following output. Red numbers show the user’s input.




—=== EMPLOYEE DATA ===—




<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Update Employee Salary</li>

 <li>Remove Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>5</strong>




ERROR: Incorrect Option: Try Again




<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Update Employee Salary</li>

 <li>Remove Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>1</strong>




EMP ID  EMP AGE EMP SALARY

======  ======= ==========




<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Update Employee Salary</li>

 <li>Remove Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>2</strong>




Adding Employee

===============

Enter Employee ID: <strong>222</strong>

Enter Employee Age: <strong>22</strong>

Enter Employee Salary: <strong>22222.22</strong>




<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Update Employee Salary</li>

 <li>Remove Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>2</strong>




Adding Employee

===============

Enter Employee ID: <strong>333</strong>

Enter Employee Age: <strong>33</strong>

Enter Employee Salary: <strong>33333.33</strong>




<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Update Employee Salary</li>

 <li>Remove Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>2</strong>




Adding Employee

===============

Enter Employee ID: <strong>444</strong>

Enter Employee Age: <strong>44</strong>

Enter Employee Salary: <strong>44444.44</strong>

<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Update Employee Salary</li>

 <li>Remove Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>2 </strong>




Adding Employee

===============

Enter Employee ID: <strong>555</strong>

Enter Employee Age: <strong>55</strong>

Enter Employee Salary: <strong>55555.55 </strong>

<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Update Employee Salary</li>

 <li>Remove Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>2</strong>




Adding Employee

=============== ERROR!!! Maximum Number of Employees Reached




<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Update Employee Salary</li>

 <li>Remove Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>1 </strong>




EMP ID  EMP AGE EMP SALARY

======  ======= ==========

222       22   22222.22

333       33   33333.33

444       44   44444.44

555       55   55555.55




<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Update Employee Salary</li>

 <li>Remove Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>3</strong>




Update Employee Salary

======================

Enter Employee ID: <strong>123</strong>

*** ERROR: Employee ID not found! ***

Enter Employee ID: <strong>321</strong>

*** ERROR: Employee ID not found! ***

Enter Employee ID: <strong>333</strong>

The current salary is 33333.33

Enter Employee New Salary: <strong>99999.99</strong>




<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Update Employee Salary</li>

 <li>Remove Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>1 </strong>




EMP ID  EMP AGE EMP SALARY

======  ======= ==========

222       22   22222.22

333       33   99999.99

444       44   44444.44

555       55   55555.55




<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Update Employee Salary</li>

 <li>Remove Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>4 </strong>




Remove Employee

===============

Enter Employee ID: <strong>789</strong>

*** ERROR: Employee ID not found! ***

Enter Employee ID: <strong>987</strong>

*** ERROR: Employee ID not found! *** Enter Employee ID: <strong>333</strong>

Employee 333 will be removed




<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Update Employee Salary</li>

 <li>Remove Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>1 </strong>




EMP ID  EMP AGE EMP SALARY

======  ======= ==========

222       22   22222.22

444       44   44444.44

555       55   55555.55




<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Update Employee Salary</li>

 <li>Remove Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>2</strong>




Adding Employee

===============

Enter Employee ID: <strong>666</strong>

Enter Employee Age: <strong>66</strong>

Enter Employee Salary: <strong>66666.66</strong>




<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Update Employee Salary</li>

 <li>Remove Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>1</strong>




EMP ID  EMP AGE EMP SALARY

======  ======= ==========

222       22   22222.22

666       66   66666.66

444       44   44444.44

555       55   55555.55




<ol>

 <li>Display Employee Information</li>

 <li>Add Employee</li>

 <li>Update Employee Salary</li>

 <li>Remove Employee</li>

 <li>Exit</li>

</ol>




Please select from the above options: <strong>0 </strong>




Exiting Employee Data Program. Good Bye!!!

<h2>AT-HOME REFLECTION (40%)</h2>

Please provide answers to the following in a text file named <strong>reflect.txt.</strong>

In three or more paragraphs and a <strong><u>minimum</u> of 150 words</strong>, explain what you learned while doing this workshop. In <u>addition</u> to what you have learned, <strong>y</strong><strong>our answer should <u>at least</u> <u>include the following</u></strong>:

<ul>

 <li>Using examples from this workshop to justify your point of view, discuss the advantages of using an array of structs versus parallel arrays when dealing with related data.</li>

 <li>In this workshop, the Employee struct is declared in the emp_athome.c file. Where else could it have been declared and what advantages might it have [<strong>Hint</strong>: this is explained in the notes]?</li>

</ul>

<strong>Reflections will be graded based on the published rubric (</strong><a href="https://github.com/Seneca-144100/IPC-Workshops/tree/master/WS05/Reflection%20Rubric.pdf">https://github.com/Seneca</a><a href="https://github.com/Seneca-144100/IPC-Workshops/tree/master/WS05/Reflection%20Rubric.pdf">144100/IPC</a><a href="https://github.com/Seneca-144100/IPC-Workshops/tree/master/WS05/Reflection%20Rubric.pdf">–</a><a href="https://github.com/Seneca-144100/IPC-Workshops/tree/master/WS05/Reflection%20Rubric.pdf">Workshops/tree/master/WS05/Reflection Rubric.pdf</a><a href="https://github.com/Seneca-144100/IPC-Workshops/tree/master/WS05/Reflection%20Rubric.pdf"><strong>)</strong></a><strong>.</strong>

<strong><u>Example</u></strong><strong>:  </strong>

<strong>An example reflection answer for <u>Workshop #2</u> is available demonstrating the minimum criteria: </strong><a href="https://github.com/Seneca-144100/IPC-Workshops/tree/master/WS05/Example%20Reflection-WS_2.pdf"><strong>https://github.com/Seneca</strong></a><a href="https://github.com/Seneca-144100/IPC-Workshops/tree/master/WS05/Example%20Reflection-WS_2.pdf"><strong>–</strong></a><a href="https://github.com/Seneca-144100/IPC-Workshops/tree/master/WS05/Example%20Reflection-WS_2.pdf"><strong>144100/IPC</strong></a><a href="https://github.com/Seneca-144100/IPC-Workshops/tree/master/WS05/Example%20Reflection-WS_2.pdf"><strong>–</strong></a><a href="https://github.com/Seneca-144100/IPC-Workshops/tree/master/WS05/Example%20Reflection-WS_2.pdf"><strong>Workshops/tree/master/WS05/Example Reflection</strong></a><a href="https://github.com/Seneca-144100/IPC-Workshops/tree/master/WS05/Example%20Reflection-WS_2.pdf"><strong>–</strong></a><a href="https://github.com/Seneca-144100/IPC-Workshops/tree/master/WS05/Example%20Reflection-WS_2.pdf"><strong>WS_2.pdf</strong></a>




<strong>AT_HOME SUBMISSION:</strong>

To test and demonstrate execution of your program use the same data as the output example above.

If not on matrix already, upload your <strong>emp_athome.c</strong><strong> and</strong> <strong>reflect.txt </strong>to your matrix account. Compile and run your code and make sure everything works properly.

Then run the following script from your account and follow the instructions (replace profname.proflastname with your professors Seneca userid and <u>replace</u> <strong>NAA</strong> with <u>your</u> section):

<strong> </strong>

<strong>~profname.proflastname/submit 144w5/NAA_home &lt;ENTER&gt;  </strong>