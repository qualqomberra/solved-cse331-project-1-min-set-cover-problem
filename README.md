Download Link: https://assignmentchef.com/product/solved-cse331-project-1-min-set-cover-problem
<br>



Min-Set-Cover problem is used to find the least number of sets that can cover the union of all given sets.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/06/488.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/06/488.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Write an assembly program that takes different sets <em>S<sub>i</sub></em> and then returns the indices of the sets so that the minimum number of sets are chosen. And the union of these sets is equal to the union of all sets as explained in the above definition.

Actually optimal solution for that problem has no known polynomial time solution. It is an NP-complete problem. Therefore, you will implement a sub-optimal greedy heuristic solution for the problem as shown below:

<strong>Rules: </strong>

<ol>

 <li>All project details will be announced at next PS (October 23). So attend the PS for your own good!</li>

 <li>Your code must not have any bound on number of given sets.</li>

 <li>Assembly that cannot be executed can at most get 20pts.</li>

 <li>You have to use MARS MIPS simulator tool of Missouri State University: <u><a href="http://courses.missouristate.edu/kenvollmar/mars/">http://courses.missouristate.edu/kenvollmar/mars/</a></u></li>

 <li>No late submissions even if 1 minute.</li>

</ol>

<strong>BONUS: </strong>

Taking all sets from a text file instead of MIPS console is a bonus with extra 25pts.

In order to read a file you have to use <strong>syscall</strong> code 13 to open file and code

14 to read file. Details can be found here:

<u><a href="http://courses.missouristate.edu/kenvollmar/mars/help/syscallhelp.html">http://courses.missouristate.edu/kenvollmar/mars/help/syscallhelp.html</a></u>

<strong><em>Honor code</em>:</strong> It is not a group project. Do not take any code from Internet. Any cheating means at least -100 for both sides. Do not share your codes and design to any one in any circumstance. Do not forget, this is named as HONOR code. Be honest and uncorrupt <u>not to win</u> but because <u>it is RIGHT</u>!


