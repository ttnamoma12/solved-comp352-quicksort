Download Link: https://assignmentchef.com/product/solved-comp352-quicksort
<br>
Submit source code and running instructions to EAS<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a>. Do it in Java. Do not use java’s search methods! Do not use Java’s Collections or Subclasses, code your own. Place textual responses for 2, 3 and 4 in block comments in your code.

<strong>Grade: </strong>5%

<ol>

 <li>Quicksort</li>

</ol>

<ul>

 <li>Implement a generic Quicksort algorithm that takes an array as input, it should use trivial pivot selection.

  <ol>

   <li>This file should be called QSNormal.java</li>

   <li>This class should have a sort method: <strong>void sort(int[] input)</strong></li>

  </ol></li>

 <li>Implement a Quicksort algorithm that uses a Median of Three pivot selection.

  <ol>

   <li>This file should be called QSMedian.java</li>

   <li>The class should have a sort method: <strong>void sort(int[] input)</strong></li>

  </ol></li>

 <li>Write classes that generate test inputs of size 10, 100, 10000, 1000000.

  <ol>

   <li>One file should be RandomGen.java</li>

   <li>One file should be FixedGen.java</li>

  </ol></li>

</ul>

<ul>

 <li>RandomGen should generate uniformly random integers.</li>

</ul>

<ol>

 <li>FixedGen should always generate a fixed input.</li>

</ol>

<ul>

 <li>Make a driver that sorts values from your input

  <ol>

   <li>This file should be called QSDriver.java</li>

   <li>This file should output the run-time in either <em>ns </em>or <em>µs</em></li>

  </ol></li>

</ul>

<ul>

 <li>it should accept command-line as follows:</li>

</ul>

<strong>java QSDriver &lt;sort&gt; &lt;gen&gt; &lt;length&gt; &lt;seed&gt;</strong>

<ol>

 <li>&lt;sort&gt; is either QSNormal or QSMedian B. &lt;gen&gt; is either RandomGen or FixedGen

  <ol>

   <li>&lt;length&gt; is the number of ints to be sorted in the input array</li>

   <li>&lt;seed&gt; is an optional argument that lets you repeat the random seed for RandomGen (but is ignored by FixedGen)</li>

  </ol></li>

</ol>

1

(e) Record performance times of runs for each input size specified in 1c for Quicksorts implemented in 1a and 1b using RandomGen.

<ol start="2">

 <li>In clear, natural language, describe the performance differences between the two sorts. Try to correlate this with the underlying mechanism.

  <ul>

   <li>This textual response should be no more than 8 lines / 80 words.</li>

  </ul></li>

 <li>In clear, natural language, describe a pathological input (one that yields a worst-case) for your trivial Quicksort defined in 1a. The FixedGen.java file should produce this pathological input.

  <ul>

   <li>This textual response should be no more than 8 lines / 80 words.</li>

  </ul></li>

 <li>In clear, natural language, describe how the pathological case performs given the Median of Three Quicksort. Reference performance tests that you run and your understanding of what makes that input a pathological case. 1a.

  <ul>

   <li>This textual response should be no more than 10 lines / 100 words.</li>

  </ul></li>

</ol>

2

<a href="#_ftnref1" name="_ftn1">[1]</a> https://fis.encs.concordia.ca/eas/