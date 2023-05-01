Download Link: https://assignmentchef.com/product/solved-cs211-data-structures-and-algorithms-lab-assignment-3
<br>
The objective of this assignment is to implement Priority Queue and Heapsort using max-heaps.




<strong>Command-line argument:</strong>

Your program should receive a file (input file) as a command line argument.




<h1>Input file</h1>

The input file will be a text file where each line will be of any of the following format:

insert &lt;number&gt;, maximum, extract-max, increase-key &lt;index&gt; &lt;number&gt;, sort, where &lt;number&gt; represents any non-negative integer.




The output must be in a file named ‘heap.txt’. Every line in the input file must have a corresponding output line in priority_queue.out. The details are given below.




<table width="564">

 <tbody>

  <tr>

   <td width="140"><strong>Command </strong></td>

   <td width="216"><strong>Meaning </strong></td>

   <td width="208"><strong>Output </strong></td>

  </tr>

  <tr>

   <td width="140">insert &lt;number&gt;</td>

   <td width="216">Insert &lt;number&gt; to the priority queue</td>

   <td width="208">&lt;number&gt; inserted</td>

  </tr>

  <tr>

   <td width="140">maximum</td>

   <td width="216">Find the maximum in the priority queue</td>

   <td width="208">&lt;maximum number&gt; /&lt;empty-line&gt; (if the priority queue is empty)</td>

  </tr>

  <tr>

   <td width="140">extract-max</td>

   <td width="216">Find and remove the maximum from the priority queue</td>

   <td width="208">&lt;maximum number&gt; /&lt;empty-line&gt; (if the priority queue is empty)</td>

  </tr>

  <tr>

   <td width="140">increase-key &lt;index&gt; &lt;number&gt;</td>

   <td width="216">Make the key at &lt;index&gt; as &lt;number&gt; if &lt;number&gt; is at least the current value at &lt;index&gt;. ​<strong>Note that the index ranges from 0 to heap-size – 1 </strong></td>

   <td width="208">Key at &lt;index&gt; changed to &lt;number&gt; / &lt;number&gt; is less than the current key at&lt;index&gt;</td>

  </tr>

  <tr>

   <td width="140">sort</td>

   <td width="216">Do a ​<strong>heapsort</strong>​ on the elements in the priority queue. Note that you don’t have to build a max-heap here. Further, the heap should not be disturbed. So, you may</td>

   <td width="208">Elements in the priority queue in ascending order. Two values are separated by a single space.</td>

  </tr>

  <tr>

   <td width="140"> </td>

   <td width="216">take a copy of the heap and do the heapsort on it.</td>

   <td width="208"> </td>

  </tr>

 </tbody>

</table>







<h1>Submission</h1>

<ul>

 <li>The program you submit should output heap.txt when run.</li>

 <li>The main file of your program should be named as &lt;roll no&gt;.&lt;extension&gt;, where roll no. specifies your roll no. and the extension depends on the language you choose (Usage of C/C++ is mandatory for this assignment). Ex: 180040001.c</li>

 <li>Test well before submission. We have some hidden inputs with us to test your program. The mark you obtain is purely based on whether your program correctly gives outputs for the hidden inputs.</li>

 <li>If your program has only a single source file, please submit the file as it is. If your program has multiple source files, please submit your code as a zip file where the name of the zip file should be your roll number. It is important that you follow the input/output conventions exactly (including the naming scheme) as we may be doing an automated evaluation. There will be a penalty of 10% (on the mark you deserve otherwise) if you do not follow the naming conventions exactly.</li>

 <li>Follow some coding style uniformly. Provide proper comments in your code.</li>

 <li>Submit only through moodle. Submit well in advance. Any hiccups in the moodle/internet at the last minute is never acceptable as an excuse for late submission. Submissions through email or any other means will be ignored.</li>

 <li>Acknowledge the people (other than the instructor and TA) who helped you to solve this assignment. The details of the help you received and the names of the people who helped you (including internet sources, if applicable) should come in the beginning of the main file as a comment. Copying others’ programs is a serious offence and deserving penalty will be imposed if found.</li>

</ul>