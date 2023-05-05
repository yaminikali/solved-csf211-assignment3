Download Link: https://assignmentchef.com/product/solved-csf211-assignment3
<br>
<h1>A: Ice Cream</h1>

There are <em>N </em>kids and <em>M </em>ice cream cones. The <em>i<sup>th </sup></em>ice cream cone has a size <em>S<sub>i</sub></em>. Each kid has a preferred cone size with the <em>i<sup>th </sup></em>child preferring a size <em>A<sub>i</sub></em>. Each child will accept an ice cream cone if the size of the ice cream cone is between <em>A<sub>i </sub></em>± <em>k </em>inclusive. You now have to find the largest number of children that will get an ice cream cone if you distribute the ice cream cones optimally. <em>Please note that you cannot give an ice cream cone to more than one kid and each child can have no more than one ice cream cone.</em>

<h2>Input</h2>

The first line of input contains three space-separated integers <em>N </em>and <em>M </em>(1 ≤ <em>N,M </em>≤ 10<sup>5</sup>) and (1 ≤ <em>k </em>≤ 10<sup>9</sup>). The second line contains <em>N </em>space-separated integers representing the array <em>A </em>that is the preferred sizes of ice cream cones for each of the <em>N </em>kids. The third line contains <em>M </em>space-separated integers representing the size of the array <em>S</em>, the sizes of the available ice cream cones.

<h2>Output</h2>

The output should have exactly one integer, the maximum number of children that can get an ice cream cone if they are distributed optimally.

input

4 3 5

60 45 60 80

30 75 60

output

2

explanation here a kid with preference 60 can get the ice cream cone with size 60 and the kid with preference 80 can get an ice cream cone of size 75. Hence the answer is 2. It is easy to see that we can satisfy no more than two kids.

<h1>B: Assassins</h1>

You have a total of <em>N </em>assassins and each has a skill <em>a<sub>i</sub></em>. There also exist <em>M </em>nobles. Each of these nobles has a bodyguard with a skill <em>b<sub>i </sub></em>and a certain amount of gold <em>g<sub>i</sub></em>. An assassin can kill a bodyguard of a noble if the assassin’s skill is greater than or equal to the bodyguard’s skill (<em>a<sub>i </sub></em>≥ <em>b<sub>j</sub></em>). If an assassin kills a bodyguard he can steal all the gold of the noble. How much gold can each assassin steal? Please calculate the answer for each assassin <em>independent </em>of the other assassins. Do not assume that if a noble’s gold is stolen by one assassin then other assassins can’t steal from him. The assassins are not actually killing the body guards as such, you just need to find how much gold each of them <em>can </em>steal hypothetically.

<h2>Input</h2>

The first line contains two integers <em>N </em>and <em>M </em>(1 ≤ <em>N,M </em>≤ 10<sup>5</sup>), the number of assassins and nobles. The second line contains <em>N </em>integers representing the array <em>a</em>, where <em>a<sub>i </sub></em>is the skill of the <em>i<sup>th </sup></em>assassin (−10<sup>9 </sup>≤ <em>a<sub>i </sub></em>≤ 10<sup>9</sup>). Then <em>M </em>lines follow, where the <em>i<sup>th </sup></em>line contains the two integers <em>b<sub>i </sub></em>and <em>g<sub>i</sub></em>, the skill of the bodyguard of the <em>i<sup>th </sup></em>noble and the amount of his gold. (−10<sup>9 </sup>≤ <em>b<sub>i</sub>,g<sub>i </sub></em>≤ 10<sup>9</sup>)

<h2>Output</h2>

Print one line containing <em>N </em>integers, where the <em>i<sup>th </sup></em>integer represents the maximum gold that the <em>i<sup>th </sup></em>assassin can steal.

input

5 4

1 4 3 2 5

4 2

0 1

2 8

9 4

output

1 11 9 9 11

explanation

The first assassin can only steal gold from the second noble. The second can steal gold from the first, second, and third nobles. The third can steal from the second and third. The fourth can steal from second and third. The fifth can steal from first, second and third.

<h1>C: Tree Planting</h1>

You want to plant <em>N </em>trees in your garden. Your garden can be represented by a number line that contains fertile spots at certain points. In particular there are <em>M </em>fertile spots (<em>M </em>≥ <em>N</em>), <em>x</em><sub>1</sub>, <em>x</em><sub>2</sub>, <em>x</em><sub>3 </sub>… <em>x<sub>M </sub></em>where you can plant a tree. You can only plant a tree in a fertile spot and a fertile spot can have a maximum of one tree. As we know from our high school biology, two trees cannot be kept too close to each other otherwise they will take up each others water and nutrients. To make sure that all the trees are healthy, you want to plant them in such a way that the minimum distance between any two of them is as large as possible. What is the largest possible minimum distance between any two trees?

<h2>Input</h2>

The first line of the input contains two space-separated integers <em>N </em>and <em>M</em>, (1 ≤ <em>N </em>≤ <em>M </em>≤ 10<sup>5</sup>). The second line of input contains <em>M </em>space-separated integers, <em>x</em><sub>1</sub>, <em>x</em><sub>2</sub>, <em>x</em><sub>3 </sub>… <em>x<sub>M</sub></em>, representing the co-ordinates of the fertile spots (0 ≤ <em>x<sub>i </sub></em>≤ 10<sup>9</sup>).

<h2>Output</h2>

Output a single integer which is the largest possible minimum distance you can get by planting the trees in some way.

input

3 5

2 1 8 4 9

output 3

explanation

we can get a minimum distance of 3 if we place trees at positions 1<em>,</em>4 and 8. It can be easily seen that it is not possible to get a larger minimum distance no matter where you plant the trees

<h1>D: Good Pairs</h1>

Given two arrays <em>x </em>and <em>y</em>, both containing <em>N </em>elements, find the number of pairs of integers <em>i,j </em>such that <em>x<sub>i </sub></em>+ <em>x<sub>j </sub></em>+ <em>k</em><sub>1 </sub><em>&gt; y<sub>i </sub></em>+ <em>y<sub>j </sub></em>+ <em>k</em><sub>2 </sub>where (<em>i &lt; j</em>).

<h2>Input</h2>

The first line contains three integers <em>N</em>, the size of the arrays, and <em>k</em><sub>1 </sub>and <em>k</em><sub>2 </sub>(1 ≤ <em>N </em>≤ 10<sup>5</sup>, −10<sup>9 </sup>≤ <em>k</em><sub>1</sub><em>,k</em><sub>2 </sub>≤ 10<sup>9</sup>). The second line contains <em>N </em>integers representing the array <em>a</em>. The third line contains <em>N </em>integers representing the array <em>b </em>(−10<sup>9 </sup>≤ <em>a<sub>i</sub>,b<sub>i </sub></em>≤ 10<sup>9</sup>).

<h2>Output</h2>

Print a single integer, the number of such pairs.

input

5 4 4

4 8 2 6 2

4 5 4 1 3

output 7

explanation

The pairs <em>i,j </em>are (1<em>,</em>4)<em>,</em>(2<em>,</em>4)<em>,</em>(3<em>,</em>4)<em>,</em>(4<em>,</em>5)<em>,</em>(1<em>,</em>2)<em>,</em>(2<em>,</em>3)<em>,</em>(2<em>,</em>5). We can easily verify that no other pair satisfies this inequality

<h1>E: The Simplified Logo Compiler</h1>

<a href="https://en.wikipedia.org/wiki/Logo_(programming_language)">Logo</a> is a programming language that can be used to draw simple shapes on the screen. In this question, you will have to implement a simplified Logo compiler that supports to commands ’FD’ and ’LOOP…END’ statements for a one dimensional turtle. The program begins with the turtle (cursor) located at coordinate 0, and the command ”FD <em>x</em>” (<em>x </em>is an integer) can be used to move the turtle by <em>x </em>units. Loop instructions consist of a line beginning with ”LOOP M” (M is an integer) and end with the line ”END”. The commands between the LOOP and END need to be repeated M times. Given a valid logo program with these two commands, provide the final location of the turtle.

<h2>Input</h2>

The first line consists of one integer <em>N </em>(<em>N </em>≤ 10<sup>4</sup>), the number of lines in the logo program. The next <em>N </em>lines describe the program, and each line will have a maximum of 32 characters.

<h2>Output</h2>

Print one integer <em>X</em>, the final position of the turtle.

input

2                                                                                                 input

FD 40                                                                                       9

FD -30                                                                                      FD 40

LOOP 10

output                                                                                     FD 5

10                                                                                              LOOP 7

FD -5

input                                                                                        FD 7

5                                                                                                END

FD 50                                                                                        FD 6

LOOP 3                                                                                    END

FD 10

FD 25

END                                                                                            output

290

output

155                                                                                              explanation

40 + 10 ×{5 + 7 ∗ (−5 + 7) + 6}

<h1>F: Fighting Fire With Fire</h1>

Moontech Pharmacueticals has successfully created an <em>anti-virus virus </em>that can be used to fight COVID-19. They intend to start injecting the new virus into people as soon as possible, but the astronomical cost of each dose means they want to <em>minimize </em>the number of total doses needed. The <em>antivirus </em>works like a regular virus, and can spread from one human to another, and is highly contagious. Given a population of <em>N </em>people, and a list of <em>M friendships </em>(people who will spend enough time with each other for the antivirus to spread), find the minimum number of people who need to be vaccinated to reach herd immunity (defined to be strictly greater than 80% of the population). Note that if A is a friend of B and B is a friend of C, injecting A with the antivirus will ensure that C also gets infected.

<h2>Input</h2>

The first line of input contains the integer N (population) and M (number of friendships) (1 ≤ <em>N,M </em>≤ 10<sup>5</sup>, and individuals of the population are numbered 0<em>…N </em>−1. The next <em>M </em>lines contain two integers <em>u,v </em>representing that <em>u </em>is friends with <em>v </em>and vice versa.

<h2>Output</h2>

<table>

 <tbody>

  <tr>

   <td width="122"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

Print one integer, <em>E</em>, denoting the number of antivirus doses needed to infect strictly greater than 80% of the population.

input

10 8

<ul>

 <li>1</li>

 <li>8</li>

</ul>

5 7

8 0

6 9

6 7

9 5

2 3

output 3

explanation

Infecting any one of (0, 1, 8) will ensure all three of them are infected. Similarly for the sets (2, 3) and (5,6,7,9). For example, we can infect 5, 1 and 2 to reach a total of 9 people infected, which is strictly greater than 80%.

<h1>G: Hitchcock and Scully</h1>

Hitchcock and Scully are trying to find new places to visit for lunch over the next <em>N </em>days. Since they have only a limited amount of time in their lunch break, they make a list of <em>M </em>restaurants in Brooklyn’s 99<em><sup>th </sup></em>precinct. Each restaurant will cost them $<em>m<sub>i </sub></em>for a lunch. Given a list of size <em>N</em>, representing the (total) amount of money they have in their pockets for each of the next <em>N </em>days, calculate how many <em>options </em>they have for lunch each day. They can go to any restaurant they want on day j, provided <em>n<sub>j </sub></em>≤ <em>m<sub>i</sub></em>.

<h2>Input</h2>

The first line of input contains space-separated <em>M </em>(1 ≤ <em>M </em>≤ 10<sup>5</sup>) and <em>N </em>(1 ≤ <em>N </em>≤ 10<sup>5</sup>). The second line contains <em>M </em>space separated numbers <em>m<sub>i</sub></em>, representing the cost of dining at restaurant <em>i</em>. The third line contains <em>N </em>space separated integers representing the money Hitchcock and Scully have each day. It is guaranteed that 1 ≤ <em>m<sub>i</sub>,n<sub>j </sub></em>≤ 10<sup>9</sup>.

<h2>Output</h2>

Print <em>N </em>space separated integers, representing the number of choices they have for each day.




input

10 5

8 9 6 5 4 3 23 9 10 1

24 9 12 3 1

output

10 8 9 2 1

explanation

On the first day with $24, they can visit all ten restaurants. On day 2, they can visit all restaurants except the one costing $24.

input

5 3

60 40 90 45 120 13 44 90

output

0 1 4

explanation

If they have no options for a certain day, print 0.




<h1>H: H-Index</h1>

Given a graph of publications and citations, with each node representing a publication and each edge representing <strong>one </strong>citation, calculate the <a href="https://en.wikipedia.org/wiki/H-index">H-index</a> of all the authors. We have <em>A </em>authors (numbered 0<em>…A </em>− 1) and <em>P </em>publications (numbered 0<em>…P </em>− 1). The value of h-index (<em>h</em>) of an author is the maximal possible value <em>x</em>, such that the number of papers (<em>x</em>) by the author have <em>x </em>or more citations each. Each publication is written by exactly one author. There are a total of <em>C </em>citations (edges) in the academic graph.

<h2>Input</h2>

The first line of input contains the numbers <em>A</em>, <em>P</em>, <em>C </em>in a space separated fashion such that 0 ≤ <em>A </em>≤ <em>P </em>≤ 1000. The second line contains <em>P </em>numbers – the author for each of the publications. The next <em>C </em>lines contain two space separated values indicating the publication numbers (<em>p<sub>i</sub>,p<sub>j</sub></em>) meaning that <em>p<sub>i </sub></em>cited <em>p<sub>j</sub></em>.

<h2>Output</h2>

Print <em>A </em>space separated integers denoting the H-index of all of the authors.

input

3 5 7

<ul>

 <li>0 1 1 2</li>

 <li>0</li>

 <li>0</li>

 <li>0</li>

 <li>0</li>

 <li>1</li>

 <li>1</li>

 <li>4</li>

</ul>

output

<ul>

 <li>0 1</li>

</ul>

explanation

We have three authors and five publications. The number of citations for each publication is: 4 2 0 0 1. Author 0 has 2 publications with 4, 2 citations respectively. So, his H-index is 2.

<h1>I: Okabe and the Toll Gates</h1>

The cities in Japan lie on a straight line numbered from 0 serially and adjacent cities are unit distance apart. Okabe Rintaro lives in city <em>U </em>has been invited to give a talk on his Time Machine theory in city <em>V </em>. He plans to rent a car from his city to the destination. The road from city <em>U </em>to <em>V </em>has a few toll gates. Each toll gate has a gas station. All the gas stations surprisingly sell gas in fixed capacity containers (in litres). A litre of gas costs <em>K </em>yen. The car Okabe rents runs according to the following mileage: <em>Z </em>litres of gas lets him drive <em>AZ </em>+<em>B </em>units. On his drive, Okabe plans to stop at every immediate toll gate (not anywhere in between), empty any gas currently in the tank and refill it again from the gas station at the toll gate. Help Okabe spend as minimum money as possible on the gas. It is guaranteed that cities <em>U </em>and <em>V </em>will always have tolls gates. Assume that the car had no gas before Okabe rented it. <em>Note that, the use of inbuilt qsort function cannot be made to solve this problem</em>.

<h2>Input</h2>

The first line of input contains three space-separated N (1 ≤ N ≤ 10<sup>5</sup>), M (1 ≤ M ≤ N) and L (1 ≤ L ≤ 10<sup>5</sup>) denoting the number of cities in Japan, the number of cities that have toll gates and the number of different gas containers sold at each gas station. The next line contains five space-separated integers U (0 ≤ U ≤ N – 1), V (U ≤ V ≤ N – 1), A, B (1 ≤ A, B ≤ 10<sup>3</sup>) and

K (1 ≤ K ≤ 10<sup>3</sup>), denoting the starting and destination city, mileage coefficients and the rate of gas respectively. The following line has M space-separated integers (0 ≤ <em>T<sub>i </sub></em>≤ N – 1) denoting the cities that have toll gates. The last line of input contains L space-separated integers (1 ≤ <em>C<sub>i </sub></em>≤ 10<sup>6</sup>) denoting the various gas container sizes sold in the gas stations.

<h2>Output</h2>

Print a single integer P, denoting the minimum money Okabe should spend on gas. If Okabe cannot make it to the city <em>V </em>using the above strategy, print “NOT POSSIBLE”.

input

100 15 7

11 92 2 3 10

52 81 76 36 5 23 50 90 17 46 3 82 11 92 83

1 8 11 7 2 5 9

output 330

<h1>J. Okabe and Entropy</h1>

Okabe, having completed the course on Advanced Statistical Mechanics in his university, has an epiphany as to how to solve the problem of the parallel worldlines. He realizes that to transit from one worldline to another, he needs exactly <em>E<sub>i </sub></em>energy (transit potential) to overcome the entropy between those two worldlines. After painstaking calculations, Okabe has finally figured out all the transit potentials. But to solve the final problem, he needs one extra information, that is the cost of the Minimum Spanning Tree across these worldlines. As he is dog-tired, he turns to you, Makise Kurisu, to help him find that cost. <em>Note: You can read up more about MSTs and how to find their cost </em><a href="https://www.geeksforgeeks.org/kruskals-minimum-spanning-tree-algorithm-greedy-algo-2/"><em>here</em></a><a href="https://www.geeksforgeeks.org/kruskals-minimum-spanning-tree-algorithm-greedy-algo-2/"><em>.</em></a>

<h2>Input</h2>

The first line of input contains two space-separated integers N (2 ≤ N ≤ 500), M (1 ≤ M ≤

), denoting the number of worldlines and the number of transits possible between those worldines respectively. The following M lines contain three space-separated integers <em>U<sub>i</sub></em>, <em>V<sub>i </sub></em>and <em>E<sub>i </sub></em>(0 ≤ <em>U<sub>i</sub></em>, <em>V<sub>i </sub></em>≤ N-1, 1 ≤ <em>E<sub>i </sub></em>≤ 10<sup>5</sup>) denoting an undirected transit between the worldlines <em>U<sub>i </sub></em>and <em>V<sub>i </sub></em>which has a transit potential of <em>E<sub>i</sub></em>. It is guaranteed that worldlines graph will be connected.

<table>

 <tbody>

  <tr>

   <td width="122"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

<h2>Output</h2>

Print a single integer E, denoting the cost of the Minimum Spanning Tree of the worldlines graph.

input

7 10

0 1 1

0 2 5

<ul>

 <li>3 1</li>

 <li>4 3</li>

 <li>5 4</li>

 <li>0 3</li>

 <li>1 3</li>

 <li>6 2</li>

 <li>6 2</li>

</ul>

6 4 3

6 5 2

0 6 2

output

11