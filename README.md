Download Link: https://assignmentchef.com/product/solved-csce240-project-3-pointer-arraylist
<br>
<strong>Topics Covered</strong>​:

<ul>

 <li>Master the use of functions in C++.</li>

 <li>Utilize call-by-value and call-by-reference implementation of functions.</li>

 <li>Demonstrate mastery of pointer arrays.</li>

 <li>Become familiar with dynamic memory allocation using pointers.</li>

 <li>Basic use of header file.</li>

</ul>

<strong>Description:  </strong>

Develop a program that mimics some of the functionalities of an ArrayList in Java. Your program should maintain a pointer array of doubles and be able to perform the following functions:

<ol>

 <li>void insert(int index, double num, double *&amp;arr, int &amp;size)

  <ol>

   <li>Adds an element (​num​) to the array (​arr​) at a given position (​index​) and updates the size.</li>

   <li>You may allow the user to add to the immediate end of the array (at position n for an array of n elements) but not past. You should print an error message if they try to print beyond these bounds.</li>

  </ol></li>

 <li>void remove(int index, double *&amp;arr, int &amp;size)

  <ol>

   <li>Removes an element from the array (​arr​) at a given position (​index​) and updates the size.</li>

   <li>If index is out of the bounds of the arr then an error message should be printed.</li>

  </ol></li>

 <li>int get(int index, double *arr, int size)

  <ol>

   <li>Returns the element at the given position (​index​).</li>

   <li>Should check if the index given is outside the bounds of the array. If it is out of bounds an error message should be printed.</li>

  </ol></li>

 <li>void clear(double *&amp;arr, int &amp;size)

  <ol>

   <li>Clears all elements of the array (​arr​) and updates the size (​size​) to be 0.</li>

  </ol></li>

 <li>int find(double num, double *arr, int size)

  <ol>

   <li>Returns the first index in which a given element (​num​) is found in the array (​arr​).</li>

  </ol></li>

</ol>

If not found -1 is returned.

<ol start="6">

 <li>bool equals(double *arr1, int size1, double *arr2, int size2)

  <ol>

   <li>Returns true if the contents of the two arrays are equal and false if they are not equal.</li>

  </ol></li>

 <li>void init(double *arr, int size)

  <ol>

   <li>Populates the elements of the array (​arr​) with input from the user (or via file redirection).</li>

  </ol></li>

 <li>void print(double *arr, int size)

  <ol>

   <li>Prints the elements of the array.</li>

  </ol></li>

</ol>




<strong>Additional Specifications: </strong>

<ul>

 <li>I have provided two files: sampleMain.cpp and myArray.h

  <ul>

   <li>I will be using sampleMain.cpp to test your program so you should test using that.</li>

  </ul></li>

</ul>

○    In myArray.h you should write ALL YOUR CODE. This is the file that you will be required to submit. DO NOT RENAME THIS FILE!

<ul>

 <li>DO NOT USE GLOBAL VARIABLES.</li>

 <li>You should check your code with Valgrind for memory leaks. You will get points off for both memory leaks as well as errors reported in Valgrind.</li>

 <li>Your program should consist of a header that contains the following information:

  <ul>

   <li>First name and last name of the programmer.</li>

  </ul></li>

</ul>

○    Date and time of the program completion.

○    A brief description of the program function.

○    Input requirements and format.

○    The output of the program.

○    Any additional needed comments (e.g. related to compilation, execution or other requirements).

<ul>

 <li>Each function needs to be properly commented.

  <ul>

   <li>Your comments need to include a description of the function.</li>

  </ul></li>

</ul>

○    Description of the inputs.

○    Description of the output.

○    Any additional notes assisting future programmers to comprehend the complex portions of your functions.

<ul>

 <li>Make sure your program compiles and runs on one of the Linux machines in the Linux lab before you submit.</li>

 <li><strong><u>Submit the source code (.h) not the executable (a.out).</u> </strong></li>

</ul>

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2021/11/575.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2021/11/575.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>