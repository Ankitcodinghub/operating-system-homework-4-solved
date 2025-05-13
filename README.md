# operating-system-homework-4-solved
**TO GET THIS SOLUTION VISIT:** [Operating-System Homework 4 Solved](https://www.ankitcodinghub.com/product/operating-system-homework-4-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93204&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Operating-System Homework 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>&nbsp;</li>
</ol>
Part I

1. A computer has four page frames. The time of loading, time of last access, and the R and M bits for each page are as shown below (the times are in clock ticks):

Page Loaded Last Reference R M 0 126 279 0 0 1 230 260 1 0 2 120 272 1 1 3 160 280 1 1

(a) Which page will NRU replace?

(b) Which page will FIFO replace?

(c) Which page will LRU replace?

(d) Which page will second chance replace?

2. A small computer has 8 page frames, each containing a page. The page frames contain virtual pages A, C, G, H, B, L, N, and D in that order. Their respective load times were 18, 23, 5, 7, 32, 19, 3, and 8. Their reference bits are 1, 0, 1, 1, 0, 1, 1, and 0 and their modified bits are 1, 1, 1, 0, 0, 0, 1, and 1, respectively. Which page will the second chance page replacement algorithm replace?

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ol start="3">
<li>What is the difference between a physical address and a virtual address?</li>
<li>Are there any circumstances in which clock and second chance choose different pages to replace? If so, what are they?</li>
<li>A small computer has four page frames. At the first clock tick, the R bits are 0111 (page 0 is 0, the rest are 1). At subsequent clock ticks, the values are 1011, 1010, 1101, 0010, 1010, 1100, and 0001. If the aging algorithm is used with an 8-bit counter, give the values of the four counters after the last ticks.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Part II

This part requires that you write a memory manager in C. In other words, instead of wrappers as shown below

<ol>
<li>1 &nbsp;#include &lt;stdlib.h&gt;</li>
<li>2 &nbsp;#include “mm.h”</li>
</ol>
3

4 void *mymalloc(size_t size) 5{

6 return malloc(size); 7}

8

<ol start="9">
<li>9 &nbsp;void myfree(void *ptr)</li>
<li>10 &nbsp;{</li>
<li>11 &nbsp;free(ptr);</li>
<li>12 &nbsp;}</li>
</ol>
13

<ol start="14">
<li>14 &nbsp;void *myrealloc(void *ptr, size_t size)</li>
<li>15 &nbsp;{</li>
<li>16 &nbsp;return realloc(ptr, size);</li>
<li>17 &nbsp;}</li>
</ol>
18

<ol start="19">
<li>19 &nbsp;void *mycalloc(size_t nmemb, size_t size)</li>
<li>20 &nbsp;{</li>
<li>21 &nbsp;return calloc(nmemb, size);</li>
<li>22 &nbsp;}</li>
</ol>
you are writing your own memory management functions, as follows:

1 #include “mm.h”

2

3 void *mymalloc(size_t size) 4{

5 // your own code

6}

7

8 void myfree(void *ptr)

9{

</div>
</div>
<div class="layoutArea">
<div class="column">
10 11 12 13 14 15 16 17 18 19 20 21

</div>
<div class="column">
<pre>    // your own code
</pre>
}

<pre>void *myrealloc(void *ptr, size_t size)
{
</pre>
<pre>    // your own code
</pre>
}

<pre>void *mycalloc(size_t nmemb, size_t size)
{
</pre>
<pre>    // your own code
</pre>
}

</div>
</div>
<div class="layoutArea">
<div class="column">
Note that mm.h is as given below.

<ol>
<li>1 &nbsp;#ifndef __MY_MM_H_INCLUDED__</li>
<li>2 &nbsp;#define __MY_MM_H_INCLUDED__</li>
</ol>
3

4 #include &lt;stddef.h&gt;

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
5

<ol start="6">
<li>6 &nbsp;void *mymalloc(size_t size);</li>
<li>7 &nbsp;void myfree(void *ptr);</li>
<li>8 &nbsp;void *myrealloc(void *ptr, size_t size);</li>
<li>9 &nbsp;void *mycalloc(size_t nmemb, size_t size);</li>
</ol>
10

11 #endif

For an example, please see pp. 185–189 of The C Programming Language, Second Edition by Kernighan and Ritchie, Prentice Hall, 1988.

</div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
