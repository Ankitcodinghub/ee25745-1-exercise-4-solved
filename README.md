# ee25745-1-exercise-4-solved
**TO GET THIS SOLUTION VISIT:** [EE25745-1 Exercise 4 Solved](https://www.ankitcodinghub.com/product/ee25745-1-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112804&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE25745-1 Exercise 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Computer Exercise 4

• Reports should include answers to the questions, diagrams, charts and explanation of your methods.

• MATLAB codes should be attached to your reports. Codes are also considered to be well-written with appropriate comments.

• It is suggested to use MATLAB Live Script for preparing your reports more conveniently.

• Reports should be uploaded to courseware.

• Naming Format: HW4_StudentNumber

1. Use Gaussian elimination without pivoting to solve the linear system

𝜖 1 𝑥1 1 + 𝜖

[1 1] [𝑥2] = [ 2 ]

For 𝜖 = 10−2𝑘 𝑘 = 1, … ,10. The exact solution is 𝑥 = [1 1]𝑇, independent of the value of 𝜖. How does the accuracy of the computed solution behave as the value of 𝜖 decreases?

2. The determinant of a triangular matrix is equal to product of its diagonal entries.

Use this fact to develop a routine for computing the determinant of an arbitrary 𝑛 × 𝑛 matrix A by using LU factorization.

You should design your own routine to obtain LU factorization.

3. Consider the linear system

1 1 + 𝜖 𝑥1 1 + (1 + 𝜖)𝜖]

[1 − 𝜖 1 ] [𝑥2] = [ 1

Where 𝜖 is a small parameter to be specified.

The exact solution is obviously

1

𝑥 = [ ]

𝜖

For any value of 𝜖.

Use Gaussian elimination to solve this system. Experiment with various values

for 𝜖, especially values near √𝜖𝑚𝑎𝑡𝑐ℎ for your computer. For each value of 𝜖 you try, compute an estimate of the condition number of the matrix and the relative error in each component of the solution. How accurately is each component determined? What conclusions can you draw from this experiments?

One way to estimate ||𝐴−1|| is to pick a vector y such that the ratio ||𝑧||/||𝑦|| is large, where z is the solution to 𝐴𝑧 = 𝑦.

Try two different approaches to picking y:

(a) Choose y as the solution to the system 𝐴𝑇𝑦 = 𝑐, where c is a vector each of whose component is ±1, with the sign for each component chosen by the following heuristic. Using the factorization 𝐴 = 𝐿𝑈, the system 𝐴𝑇𝑦 = 𝑐 is solved in two stages, successively solving the triangular system 𝑈𝑇𝑣 = 𝑐 and 𝐿𝑇𝑦 = 𝑣. At each step the first triangular solution, choose the corresponding component of c to be 1 or -1, depending on which will make the resulting component of v larger in magnitude,( You will need to write a custom triangular solution routine to implement this). Then solve the second triangular system in the usual way for y.

The idea here is that any ill-conditioning in A will be reflected in U, resulting in relatively large v. The relatively well-conditioned unit triangular matrix L will then preserve this relationship, resulting in a relatively large y.

(b) Choose some small number, say, five, different vectors y randomly and use the one producing the largest ratio ||𝑧||/||𝑦|| . (For this you can use an ordinary triangular solution routine.)

Test your program on the following matrices:

0.641 0.242

𝐴 = [[ ]

0.321 0.121

10 −7 0

𝐵 = [−3 2 6]

5 −1 5

How do results using these two methods compare? To check the quality of your estimates, compute 𝐴−1 explicitly to determine its true norm (this computation can also make use of the LU factorization already computed).
