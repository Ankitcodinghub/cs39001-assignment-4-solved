# cs39001-assignment-4-solved
**TO GET THIS SOLUTION VISIT:** [CS39001 Assignment 4 Solved](https://www.ankitcodinghub.com/product/cs39001-assignment-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92929&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS39001 Assignment 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Question 1

Write a complete MIPS-32 program that –

<ol>
<li>Prompts the user for four positive integers n, a r, m as “Enter three
positive integers (n, a, r and m) : ”.
</li>
<li>Allocates space for an n × n square matrix in integer array A. Populate the array A in a row major fashion using a Geometric Progression (GP) series with initial value a and common ratio r such that the ith element A[i] = (ari) mod m.</li>
<li>Print the elements of matrix A.</li>
<li>Recursively computes the determinant of the matrix A. The value of
determinant of a matrix can be calculated by following Laplace expansion. 1
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Laplace expansion expresses the determinant of a matrix A in terms of determinants of smaller matrices, known as its minors. The minor Mi,j is defined to be the determinant of the (n − 1) × (n − 1) matrix that results from A by removing the ith row and the jth column. The expression (−1)i+jMi,j is known as a cofactor. For every i, one has the equality given in Equation 1 which is called the Laplace expansion along the ith row. The computation of minor is recursive in nature.

n

det(A) = 􏰁(−1)i+j Mi,j · A[i][j] (1)

j=1

The above expression reduces the matrix dimension considering any i-th

row. It can similarly be done w.r.t. any j-th column.

5. Prints the final determinant with suitable message as “Final determinant

of the matrix A is ”.

Follow these implementation-level constraints while writing your code. Write

the following functions:

<ol>
<li>“initStack” : Initialise the stack pointer ($sp) and frame pointer ($fp).</li>
<li>“pushToStack” : This function takes one argument as input (in $a0) and push it to the stack.</li>
<li>“popFromStack” : This function does not take any argument and returns the first element in the stack.</li>
<li>“printMatrix” : This function takes two parameters- the positive integers n (in $a0) and the address of the two-dimensional n × n integer array A (in $a1). It prints the elements of A in a row-major fashion.</li>
<li>Write a recursive subroutine recursive Det that is passed the following parameters- a positive integer n′ and the address of any intermediate ma- trix A′ stored in the two-dimensional n′ × n′ integer array. It returns the determinant of the matrix A′.</li>
</ol>
If required, you can write additional functions as well, but with proper com- ments and descriptions.

Question 2

Write a complete MIPS-32 program that –

1. Reads an array of ten integers from the user (can also be negative). These numbers are collected from the input console using a loop and stored in the memory in an array called ‘array’. Do not store the numbers as scalars in ten different non-contiguous locations or in ten different registers.

2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ol start="2">
<li>Write a recursive function named recursive sort that takes the start ad- dress, start index and end index of an array in order to sort the array recursively. You have to implement your code following Algorithm 1 as given below.</li>
<li>After sorting, print the sorted array on the console with a proper message as “Sorted array :” .</li>
</ol>
Follow these implementation-level constraints while writing your code. Write the following helper functions:

<ol>
<li>“initStack” : Initialise the stack pointer ($sp).</li>
<li>“pushToStack” : This function takes one argument as input and push it
to the stack.
</li>
<li>“SWAP” : The function takes two array elements as inputs and perform swap operation.</li>
<li>“printArray” : This function takes the array address and array size and prints the elements of A.</li>
</ol>
If required, you can write additional functions as well, but with proper com- ments and descriptions.

Algorithm 1 recursive sort(A,left,right)

</div>
</div>
<div class="layoutArea">
<div class="column">
1: 2: 3: 4: 5: 6: 7: 8: 9:

10: 11: 12:

</div>
<div class="column">
l ← left,r ← right,p ← left; whilel&lt;r

while A[l] ≤ A[p] and l &lt; right l + +;

while A[r] ≥ A[p] and r &gt; left r − −;

if l ≥ r then

SWAP(A[p], A[r]); // Swap the array elements recursive sort(A, left, r-1);

recursive sort(A, r+1, right);

return;

SWAP(A[l], A[r]);

</div>
</div>
<div class="layoutArea">
<div class="column">
Question 3

Write a complete MIPS-32 program that –

1. Reads an array of ten integers from the user (can also be negative). Read

an integer (n) from the user to be searched in the array.

3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
<ol start="2">
<li>Sort the 1-D array in ascending order using the recursive sort function implemented in the previous question, and print the sorted array with the message – “Sorted array: ”.</li>
<li>Write a recursive function recursive search to search the array for the presence of the value key in the array following the Algorithm 2 given below. The address of the sorted array and key are passed as argument to implement the recursive search function. The function returns the index where key is found, or return -1 if not found.</li>
<li>If the search is successful, the program will print an appropriate success message with the array index (i) where the value was found, such as- “&lt; n &gt; is FOUND in the array at index &lt; i &gt;.”.</li>
<li>If the search is unsuccessful, the program will print a failure message, such as “&lt; n &gt; NOT FOUND in the array.”.</li>
</ol>
Follow these implementation-level constraints while writing your code. Write the following helper functions:

<ol>
<li>“initStack” : Initialise the stack pointer ($sp).</li>
<li>“pushToStack” : This function takes one argument as input and push it
to the stack.
</li>
<li>“printArray” : This function takes the array address and array size and
prints the elements of A.
</li>
</ol>
If required, you can write additional functions as well, but with proper com-

ments and descriptions.

Algorithm 2 recursive search(A, start, end, key)

</div>
</div>
<div class="layoutArea">
<div class="column">
1: 2: 3: 4: 5: 6: 7: 8: 9:

10: 11: 12: 13: 14:

</div>
<div class="column">
while start ≥ end

mid1 ← start + (end − start)/3; mid2 ← end − (end − start)/3; if key == A[mid1] then

return mid1;

else if key == A[mid2] then

return mid2;

else if key &lt; A[mid1] then

return recursive search(A, start, mid1 − 1, key); else if key &gt; A[mid2] then

return recursive search(A, mid2 + 1, end, key); else

return recursive search(A, mid1 + 1, mid2 − 1, key); return −1

4

</div>
</div>
</div>
