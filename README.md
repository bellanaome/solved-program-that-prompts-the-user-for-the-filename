Download Link: https://assignmentchef.com/product/solved-program-that-prompts-the-user-for-the-filename
<br>
<table>

 <tbody>

  <tr>

   <td>Write a C++ program that prompts the user for the filename of an input data file that contains a list of double-precision numbers representing test scores. The program should then prompt the user for the number of test scores in the input data file. After the user enters the number of test scores in the input data file, the program must declare an array, named scores, which will hold the user-specified number of double- precision test scores. The program must then read the user-specified number of</td>

  </tr>

  <tr>

   <td>double-precision test scores from the input data file into the program “storing” each score in the array named scores. After all scores have been “stored” in the array, your program must invoke a function named sort which sorts the scores in the array into ascending order (low to high) you may use the selectionSort function given on pages 449 and 451 of the textbook. The program must then compute the sum and average of the scores. Finally, the program must prompt the user for the filename of an output data file. The program must open the user-specified output data file and then write the following data to the output data file:</td>

  </tr>

 </tbody>

</table>

The total number of scores which were processed. This will be the user-entered number that was used as the “size” of the array named scores.

The sum of the scores which were processed.

The average of the scores which were processed.

The list of scores in ascending numeric order. For each score in the list,

place an asterisk (*) in front of each score that is below the average. Additionally each score should be followed by its letter grade equivalent using the following scale:

Between 90 and 100 = AGreater than or equal to 80 and less than 90 = B Greater than or equal to 70 and less than 80 = C Greater than or equal to 60 and less than 70 = D Less than 60 = F

Here is an example run showing what your program’s console input and output must look like:

<pre>Please enter the name of the input file: inputFile.txtPlease enter the number of scores in inputFile.txt: 10Please enter the name of the output file: outputFile.txtPress any key to continue . . .</pre>

<table>

 <tbody>

  <tr>

   <td>Here are the ten scores contained in my inputFile.txt:<pre>9010079.07069.56180.589.90</pre>51</td>

  </tr>

  <tr>

   <td>Note: In order to properly test your program, you must generate your own input data file. DO NOT test your program with only my inputFile.txt data file.And here are the contents of outputFile.txt after the program has processed all ten scores in the array named scores:<pre>A total number of 10 scores were processed.The sum of these scores is: 690.9.The average of these scores is: 69.09.</pre>The individual scores processed were: *0F* 51 F* 61 D<pre>69.5 D70 C79 C80.5 B89.9 B90 A100 A</pre></td>

  </tr>

 </tbody>

</table>