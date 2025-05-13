# csc382-lab-1-compare-fibonacci-solved
**TO GET THIS SOLUTION VISIT:** [CSC382 Lab 1-Compare Fibonacci Solved](https://www.ankitcodinghub.com/product/csc382-project-1-compare-fibonacci-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94047&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC382  Lab 1-Compare Fibonacci Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
CSC 382 Project 1

Compare Fibonacci (recursion vs. bottom up)

In this project we will compare the computational time taken by a recursive algorithm to determine the Fibonacci number of an integer n and the time taken by a bottom-up approach (using a loop) to calculate the Fibonacci number of the same integer n.

A Fibonacci number F(n) is determined by the following recurrence function: F(0) =0; F(1)=1;

F(n)= F(n-1) + F(n-2), for n ≥ 2

Thus the recursive algorithm can be written in C++ as

int FiboR ( int n) // array of size n { if (n==0 || n==1)

return (n);

else return (FiboR (n-1) + FiboR(n-2));

}

And the non-recursive algorithm can be written in C++ as int FiboNR ( int n) // array of size n

{ int F[max]; F[0]=0; F[1]=1;

for (int i =2; i &lt;=n; i++)

{ F[n] = F[n-1] + F[n-2]; }

return (F[n]); }

While FiboR takes exponential time FiboNR takes n steps

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
As you will find out the time to compute the recursive Fibonacci will take a long time as you are repeating the same call to an specific value several times.

But you could modify the recursive algorithm to make it very efficient as if a value has been calculated you can store it and if the recursion is trying to calculate the value again you do not need to make recursive calls as you can returned this value. We will call this algorithm MODFibR. You need to write this algorithm.

Write an algorithm that computes the time (in seconds using ctime.h header library file that takes to determine Fibonacci (n) using FiboR and the time taken by FiboNR on the same input n.

Try to run both routines using different values of n (n={1,5,10,15,20,25,30,35,40,45,50,55,60…) You final output should look like:

Fibonacci time analysis (recursive vs. non-recursive)

FiboNR(seconds)

XX.XX 1 XX.XX 5

</div>
</div>
<div class="layoutArea">
<div class="column">
FiboR (seconds)

XX.XX

XX.XX

.. .. ..

60 XX.XX XX.XX …

</div>
</div>
<div class="layoutArea">
<div class="column">
Integer 1

</div>
<div class="column">
MODFibR

</div>
<div class="column">
Fibo-value

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
<div class="column">
XX.XX XX.XX

</div>
</div>
<div class="layoutArea">
<div class="column">
XX.XX

</div>
<div class="column">
XXXXXXXXXX

</div>
</div>
</div>
