# fundamental-algorithms-assignment-8-disjoint-sets-solved
**TO GET THIS SOLUTION VISIT:** [Fundamental-Algorithms Assignment 8-Disjoint Sets Solved](https://www.ankitcodinghub.com/product/fundamental-algorithms-assignment-8-disjoint-sets-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97171&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Fundamental-Algorithms Assignment 8-Disjoint Sets Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Disjoint Sets

Implementation

You are required to implement ​correctly and ​efficiently the base operations for ​disjoint set (chapter 21.1 from book1) and the ​Kruskal’s algorithm (searching for the minimum spanning tree – chapter 23.2) using disjoint sets.

You have to use a tree as the representation of a disjoint set. Each tree holds, besides the necessary information, also the ​rank​ field (i.e. the height of the tree).

The base operations on ​disjoints sets​ are: ● MAKE_SET (x)

○ creates a set with the element ​x

<ul>
<li>● &nbsp;UNION (x, y)
<ul>
<li>○ &nbsp;makes the union between the set that contains the element ​x and the set that contains the element ​y</li>
<li>○ &nbsp;the heuristic ​union by rank takes into account the height of the two trees so as to make the union</li>
<li>○ &nbsp;the pseudo-code can be found in the chapter 21.3 from the book1​</li>
</ul>
</li>
<li>● &nbsp;FIND_SET (x)
<ul>
<li>○ &nbsp;searches for the set that contains the element ​x</li>
<li>○ &nbsp;the heuristic ​path compression links all nodes that were found on the path to ​x to
the root node

Thresholds

Grade Requirements
</li>
</ul>
</li>
</ul>
5 Correct implementation for: MAKE_SET, UNION and FIND_SET + demo 7 Correct and ​efficient​ implementation for: Kruskal’s algorithm

<ol start="9">
<li>9 &nbsp;Evaluate the disjoint sets operations using Kruskal’s algorithm</li>
<li>10 &nbsp;Interpretations, discussion</li>
</ol>
1 Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest and Clifford Stein. ​Introduction to Algorithms

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Evaluation

! Before you start to work on the algorithms evaluation code, make sure you have a correct algorithm! The correctness of the algorithm must be proved on a small-sized input (i.e. create 10 sets and execute the sequence: UNION and FIND_SET for 5 elements and dump the content of the sets).

Once you are sure your program works correctly:

<ul>
<li>● &nbsp;vary n from 100 to 10000 with step 100;</li>
<li>● &nbsp;for each n
○ build a undirected, connected, random graph with random weights on edges (​n nodes, ​n*4​ edges)
</li>
</ul>
○ find the minimum spanning tree using Kruskal’s algorithm

Evaluate the computational effort as the sum of the comparisons and assignments performed by each individual base operation on disjoint sets.

</div>
</div>
</div>
</div>
