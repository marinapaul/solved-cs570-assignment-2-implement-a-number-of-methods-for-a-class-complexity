Download Link: https://assignmentchef.com/product/solved-cs570-assignment-2-implement-a-number-of-methods-for-a-class-complexity
<br>
<h1>Assignment</h1>

This assignment asks you to implement a number of methods for a class Complexity. These methods should be implemented using for loops, as seen in class (except for the extra-credit one). In addition, each of these methods should print out the value of an accumulator that counts the number of “operations” performed. The notion of “operation” should be taken loosely; the idea is that if you are requested to implement a method of time complexity <em>O</em>(<em>n</em>), then it should print out values from 1 to <em>n </em>(or close enough). For example, the following code implements a method that has time complexity <em>O</em>(<em>n</em>):

<table width="0">

 <tbody>

  <tr>

   <td width="529"><strong>void public </strong>method0(<strong>int </strong>n) { <strong>int </strong>counter=0; <strong>for </strong>(i=0; i&lt;n; i++) {System.out.println(“Operation “+counter); counter++;}}</td>

  </tr>

 </tbody>

</table>

2

4

6

The methods you should implement are:

<ul>

 <li><strong>public static void </strong>method1(<strong>int </strong>n): a method that has time complexity <em>O</em>(<em>n</em><sup>2</sup>).</li>

 <li><strong>public static void </strong>method2(<strong>int </strong>n): a method that has time complexity <em>O</em>(<em>n</em><sup>3</sup>).</li>

 <li><strong>public static void </strong>method3(<strong>int </strong>n): a method that has time complexity <em>O</em>(log<em>n</em>).</li>

 <li><strong>public static void </strong>method4(<strong>int </strong>n): a method that has time complexity <em>O</em>(<em>n</em>log<em>n</em>).</li>

 <li><strong>public static void </strong>method5(<strong>int </strong>n): a method that has time complexity <em>O</em>(loglog<em>n</em>).</li>

 <li>(Optional) <strong>public static int </strong>method6(<strong>int </strong>n): a method that has time complexity <em>O</em>(2<em><sup>n</sup></em>). For this method you should consider using recursion. This can give you extra points if you miss any points from the previous methods, but the cap for the assignment is 100pts. You can not exceed 100pts with answering this extra-credit question.</li>

</ul>