# 4365---programming-assignment---ii-solved
**TO GET THIS SOLUTION VISIT:** [4365 – Programming Assignment – II Solved](https://www.ankitcodinghub.com/product/4365-programming-assignment-ii-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110718&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;4365 - Programming Assignment - II Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Constraint Satisfaction -Graph Coloring Problem

4365 Artificial Intelligence

Find an “admissible” coloring of a graph such that all adjacent nodes have different colors.

(It had been conjectured for a long time that such a coloring is possible with only 4 colors if the graph is planar. This conjecture was formulated precisely by F. Guthrie already in 1852 but proved by K. Appel and W. Haken only in 1976 using a computer program).

Write a Prolog program that finds all admissible colorings of a given graph using the colors red, blue, yellow, and green.

You should write a predicate called coloring which has two variables, first one is the assignment and the second one is the graph. The graph is a list with two items, the first item the list of vertices and the second item the list of list with adjacent vertices corresponding to the first list. The assignment will have paint for each vertex with appropriate color. The constraint here is that the adjacent vertices cannot have the same color. Your algorithm will return all possible combinations of four colors for the graph.

For example

?- coloring(M,[[a,b],[[b],[a]]]).

M = [paint(a, red), paint(b, blue)] ;

M = [paint(a, red), paint(b, yellow)] ;

M = [paint(a, red), paint(b, green)] ;

M = [paint(a, blue), paint(b, red)] ;

M = [paint(a, blue), paint(b, yellow)] ;

M = [paint(a, blue), paint(b, green)] ;

M = [paint(a, yellow), paint(b, red)] ;

M = [paint(a, yellow), paint(b, blue)] ;

M = [paint(a, yellow), paint(b, green)] ;

M = [paint(a, green), paint(b, red)] ;

M = [paint(a, green), paint(b, blue)] ;

M = [paint(a, green), paint(b, yellow)] ; false.

More examples are given at the end of the description.

Submission Instruction: –

For this assignment you will submit a single .pl file containing your Prolog program. Include a report file with input / output samples of your program.

Hint

Write the different/2 predicate indicating how 2 colors are different.

Write coloring/2 predicate, any coloring must be complete and valid. So you will write 2 different predicate to ensure these 2 properties.

For example the predicate to ensure completeness will just go over the first list and add paint(X,_) for each element in the list [X|T] and ensure completeness of the remaining items T using recursion. There should be a base case stating that if both lists are empty in the graph [[][]] then empty assignment is an empty list as well [].

These assignment should have very few lines of code. If you have any questions, please ask during class.

Example-1

?- coloring1(M,[[a,b,c],[[b,c],[a,c],[a,b]]]). M = [paint(a, red), paint(b, blue), paint(c, yellow)] ;

M = [paint(a, red), paint(b, blue), paint(c, green)] ;

M = [paint(a, red), paint(b, yellow), paint(c, blue)] ;

M = [paint(a, red), paint(b, yellow), paint(c, green)] ; M = [paint(a, red), paint(b, green), paint(c, blue)] ;

M = [paint(a, red), paint(b, green), paint(c, yellow)] ;

M = [paint(a, blue), paint(b, red), paint(c, yellow)] ; M = [paint(a, blue), paint(b, red), paint(c, green)] ;

M = [paint(a, blue), paint(b, yellow), paint(c, red)] ;

M = [paint(a, blue), paint(b, yellow), paint(c, green)] ; M = [paint(a, blue), paint(b, green), paint(c, red)] ;

M = [paint(a, blue), paint(b, green), paint(c, yellow)] ; M = [paint(a, yellow), paint(b, red), paint(c, blue)] ;

M = [paint(a, yellow), paint(b, red), paint(c, green)] ; M = [paint(a, yellow), paint(b, blue), paint(c, red)] ;

M = [paint(a, yellow), paint(b, blue), paint(c, green)] ; M = [paint(a, yellow), paint(b, green), paint(c, red)] ;

M = [paint(a, yellow), paint(b, green), paint(c, blue)] ; M = [paint(a, green), paint(b, red), paint(c, blue)] ;

M = [paint(a, green), paint(b, red), paint(c, yellow)] ; M = [paint(a, green), paint(b, blue), paint(c, red)] ;

M = [paint(a, green), paint(b, blue), paint(c, yellow)] ; M = [paint(a, green), paint(b, yellow), paint(c, red)] ;

M = [paint(a, green), paint(b, yellow), paint(c, blue)] ;

false.

Example-2

The following graph has multiple four-color assignments.

?- coloring(M,[[a,b,c,d,e],[[b,c,d,e],[a,c,d,e],[a,b,d],[a,b,c],[a,b]]]).

M = [paint(a, red), paint(b, blue), paint(c, yellow), paint(d, green), paint(e, yellow)] ;

M = [paint(a, red), paint(b, blue), paint(c, yellow), paint(d, green), paint(e, green)] ;

M = [paint(a, red), paint(b, blue), paint(c, green), paint(d, yellow), paint(e, yellow)] ;

M = [paint(a, red), paint(b, blue), paint(c, green), paint(d, yellow), paint(e, green)] ; M = [paint(a, red), paint(b, yellow), paint(c, blue), paint(d, green), paint(e, blue)] ;

M = [paint(a, red), paint(b, yellow), paint(c, blue), paint(d, green), paint(e, green)] ; M = [paint(a, red), paint(b, yellow), paint(c, green), paint(d, blue), paint(e, blue)] ;

M = [paint(a, red), paint(b, yellow), paint(c, green), paint(d, blue), paint(e, green)] ;

M = [paint(a, red), paint(b, green), paint(c, blue), paint(d, yellow), paint(e, blue)] ;

M = [paint(a, red), paint(b, green), paint(c, blue), paint(d, yellow), paint(e, yellow)] ; M = [paint(a, red), paint(b, green), paint(c, yellow), paint(d, blue), paint(e, blue)] ;

M = [paint(a, red), paint(b, green), paint(c, yellow), paint(d, blue), paint(e, yellow)] ;

M = [paint(a, blue), paint(b, red), paint(c, yellow), paint(d, green), paint(e, yellow)] ;

M = [paint(a, blue), paint(b, red), paint(c, yellow), paint(d, green), paint(e, green)] ;

M = [paint(a, blue), paint(b, red), paint(c, green), paint(d, yellow), paint(e, yellow)] ;

M = [paint(a, blue), paint(b, red), paint(c, green), paint(d, yellow), paint(e, green)] ; M = [paint(a, blue), paint(b, yellow), paint(c, red), paint(d, green), paint(e, red)] ;

M = [paint(a, blue), paint(b, yellow), paint(c, red), paint(d, green), paint(e, green)] ; M = [paint(a, blue), paint(b, yellow), paint(c, green), paint(d, red), paint(e, red)] ;

M = [paint(a, blue), paint(b, yellow), paint(c, green), paint(d, red), paint(e, green)] ;

M = [paint(a, blue), paint(b, green), paint(c, red), paint(d, yellow), paint(e, red)] ;

M = [paint(a, blue), paint(b, green), paint(c, red), paint(d, yellow), paint(e, yellow)] ; M = [paint(a, blue), paint(b, green), paint(c, yellow), paint(d, red), paint(e, red)] ;

M = [paint(a, blue), paint(b, green), paint(c, yellow), paint(d, red), paint(e, yellow)] ;

M = [paint(a, yellow), paint(b, red), paint(c, blue), paint(d, green), paint(e, blue)] ;

M = [paint(a, yellow), paint(b, red), paint(c, blue), paint(d, green), paint(e, green)] ; M = [paint(a, yellow), paint(b, red), paint(c, green), paint(d, blue), paint(e, blue)] ;

M = [paint(a, yellow), paint(b, red), paint(c, green), paint(d, blue), paint(e, green)] ; M = [paint(a, yellow), paint(b, blue), paint(c, red), paint(d, green), paint(e, red)] ;

M = [paint(a, yellow), paint(b, blue), paint(c, red), paint(d, green), paint(e, green)] ; M = [paint(a, yellow), paint(b, blue), paint(c, green), paint(d, red), paint(e, red)] ;

M = [paint(a, yellow), paint(b, blue), paint(c, green), paint(d, red), paint(e, green)] ;

M = [paint(a, yellow), paint(b, green), paint(c, red), paint(d, blue), paint(e, red)] ;

M = [paint(a, yellow), paint(b, green), paint(c, red), paint(d, blue), paint(e, blue)] ; M = [paint(a, yellow), paint(b, green), paint(c, blue), paint(d, red), paint(e, red)] ;

M = [paint(a, yellow), paint(b, green), paint(c, blue), paint(d, red), paint(e, blue)] ;

M = [paint(a, green), paint(b, red), paint(c, blue), paint(d, yellow), paint(e, blue)] ; M = [paint(a, green), paint(b, red), paint(c, blue), paint(d, yellow), paint(e, yellow)] ;

M = [paint(a, green), paint(b, red), paint(c, yellow), paint(d, blue), paint(e, blue)] ;

M = [paint(a, green), paint(b, red), paint(c, yellow), paint(d, blue), paint(e, yellow)] ;

M = [paint(a, green), paint(b, blue), paint(c, red), paint(d, yellow), paint(e, red)] ;

M = [paint(a, green), paint(b, blue), paint(c, red), paint(d, yellow), paint(e, yellow)] ; M = [paint(a, green), paint(b, blue), paint(c, yellow), paint(d, red), paint(e, red)] ;

M = [paint(a, green), paint(b, blue), paint(c, yellow), paint(d, red), paint(e, yellow)] ;

M = [paint(a, green), paint(b, yellow), paint(c, red), paint(d, blue), paint(e, red)] ;

M = [paint(a, green), paint(b, yellow), paint(c, red), paint(d, blue), paint(e, blue)] ;

M = [paint(a, green), paint(b, yellow), paint(c, blue), paint(d, red), paint(e, red)] ; M = [paint(a, green), paint(b, yellow), paint(c, blue), paint(d, red), paint(e, blue)] ; false.

Example-3 Let’s say the graphs looks like the following image.

The first list is the list of vertices [a,b,c,d,e] , second list is the list of adjacent vertices corresponding to first list [[b,e,d],[a,c,d,e],[b,d,e],[a,b,c,e],[a,b,c,d]].

The above graph is a planar graph and has multiple assignments using 4 colors, some of the solutions are as follows.

coloring(M,[[a,b,c,d,e],[[b,e,d],[a,c,d,e],[b,d,e],[a,b,c,e],[a,b,c,d] ]]).

M = [paint(a, red), paint(b, blue), paint(c, red), paint(d, green), paint(e, yellow)] ;

M = [paint(a, red), paint(b, blue), paint(c, red), paint(d, yellow), paint(e, green)] ;

M = [paint(a, red), paint(b, yellow), paint(c, red), paint(d, green), paint(e, blue)] ;

M = [paint(a, red), paint(b, yellow), paint(c, red), paint(d, blue), paint(e, green)] ;

M = [paint(a, red), paint(b, green), paint(c, red), paint(d, yellow), paint(e, blue)] ;

M = [paint(a, red), paint(b, green), paint(c, red), paint(d, blue), paint(e, yellow)] ;

M = [paint(a, blue), paint(b, red), paint(c, blue), paint(d, green), paint(e, yellow)] ;

M = [paint(a, blue), paint(b, red), paint(c, blue), paint(d, yellow), paint(e, green)] ;

M = [paint(a, blue), paint(b, yellow), paint(c, blue), paint(d, green), paint(e, red)] ;

M = [paint(a, blue), paint(b, yellow), paint(c, blue), paint(d, red), paint(e, green)] ;

M = [paint(a, blue), paint(b, green), paint(c, blue), paint(d, yellow), paint(e, red)] ;

M = [paint(a, blue), paint(b, green), paint(c, blue), paint(d, red), paint(e, yellow)] ;

……

Example-4

coloring1(M,[[a,b,c,d,e,f],[[b,c,d,e],[a,c,d,f],[a,b,d,e,f],[a,b,c,e,f ],[a,c,d],[b,c,d]]]).

M = [paint(a, red), paint(b, blue), paint(c, yellow), paint(d, green), paint(e, blue), paint(f, red)] ;

M = [paint(a, red), paint(b, blue), paint(c, green), paint(d, yellow), paint(e, blue), paint(f, red)] ;

M = [paint(a, red), paint(b, yellow), paint(c, blue), paint(d, green), paint(e, yellow), paint(f, red)] ;

M = [paint(a, red), paint(b, yellow), paint(c, green), paint(d, blue), paint(e, yellow), paint(f, red)] ;

M = [paint(a, red), paint(b, green), paint(c, blue), paint(d, yellow), paint(e, green), paint(f, red)] ;

M = [paint(a, red), paint(b, green), paint(c, yellow), paint(d, blue), paint(e, green), paint(f, red)] ;

M = [paint(a, blue), paint(b, red), paint(c, yellow), paint(d, green), paint(e, red), paint(f, blue)] ;

M = [paint(a, blue), paint(b, red), paint(c, green), paint(d, yellow), paint(e, red), paint(f, blue)] ;

M = [paint(a, blue), paint(b, yellow), paint(c, red), paint(d, green), paint(e, yellow), paint(f, blue)] ;

M = [paint(a, blue), paint(b, yellow), paint(c, green), paint(d, red), paint(e, yellow), paint(f, blue)] ;

M = [paint(a, blue), paint(b, green), paint(c, red), paint(d, yellow), paint(e, green), paint(f, blue)] ;

M = [paint(a, blue), paint(b, green), paint(c, yellow), paint(d, red), paint(e, green), paint(f, blue)] ;

M = [paint(a, yellow), paint(b, red), paint(c, blue), paint(d, green), paint(e, red), paint(f, yellow)] ;

M = [paint(a, yellow), paint(b, red), paint(c, green), paint(d, blue), paint(e, red), paint(f, yellow)] ;

M = [paint(a, yellow), paint(b, blue), paint(c, red), paint(d, green), paint(e, blue), paint(f, yellow)] ;

M = [paint(a, yellow), paint(b, blue), paint(c, green), paint(d, red), paint(e, blue), paint(f, yellow)] ;

M = [paint(a, yellow), paint(b, green), paint(c, red), paint(d, blue), paint(e, green), paint(f, yellow)] ;

M = [paint(a, yellow), paint(b, green), paint(c, blue), paint(d, red), paint(e, green), paint(f, yellow)] ;

M = [paint(a, green), paint(b, red), paint(c, blue), paint(d, yellow), paint(e, red), paint(f, green)] ;

M = [paint(a, green), paint(b, red), paint(c, yellow), paint(d, blue), paint(e, red), paint(f, green)] ;

M = [paint(a, green), paint(b, blue), paint(c, red), paint(d, yellow), paint(e, blue), paint(f, green)] ;

M = [paint(a, green), paint(b, blue), paint(c, yellow), paint(d, red), paint(e, blue), paint(f, green)] ;

M = [paint(a, green), paint(b, yellow), paint(c, red), paint(d, blue), paint(e, yellow), paint(f, green)] ;

M = [paint(a, green), paint(b, yellow), paint(c, blue), paint(d, red), paint(e, yellow), paint(f, green)] ; false.
