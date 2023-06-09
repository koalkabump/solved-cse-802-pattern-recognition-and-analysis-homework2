Download Link: https://assignmentchef.com/product/solved-cse-802-pattern-recognition-and-analysis-homework2
<br>






<ol>

 <li></li>

 <li>Consider a set of 1-dimensional feature values (i.e., points) pertaining to a class that is available <a href="https://www.cse.msu.edu/~rossarun/courses/sp20/cse802/data/hw02_data01.txt">here</a><a href="https://www.cse.msu.edu/~rossarun/courses/sp20/cse802/data/hw02_data01.txt">.</a>

  <ul>

   <li>[3 points] Plot the histogram of these points using a bin size of 2, i.e., each bin should have a range of 2.</li>

   <li>[4 points] Compute and report the mean and the biased variance of these points.</li>

   <li>[3 points] Assuming that the given points are generated by an underlying Gaussian distribution, plot the pdf function on the same graph as (a).</li>

  </ul></li>

 <li>Consider the three-dimensional normal distribution <em>p</em>(<strong><em>x</em></strong>) <em>∼ N</em>(<strong><em>µ</em></strong>,<strong><em>Σ</em></strong>), where <strong><em>µ </em></strong>= (1,1,1)<em><sup>t </sup></em>and <strong><em>Σ </em></strong>=</li>

</ol>

             

1   0   0

0    5    2.

0   2   5

<ul>

 <li>[2 points] Compute and report the determinant of the covariance matrix, i.e., <em>| Σ |</em>.</li>

 <li>[2 points] Compute and report the inverse of the covariance matrix, i.e., <em>Σ</em><em>−</em><sup>1</sup>.</li>

 <li>[3 points] Compute and report the eigen-vectors and eigen-values of the covariance matrix.</li>

 <li>[3 points] Compute and report the probability density at (0,0,0)<em><sup>t </sup></em>and at (5,5,5)<em><sup>t</sup></em>.</li>

 <li>[2 points] Compute the Euclidean Distance between <strong><em>µ </em></strong>and the point (5,5,5)<em><sup>t</sup></em>.</li>

 <li>[3 points] Compute the Mahalanobis Distance between <strong><em>µ </em></strong>and the point (5,5,5)<em><sup>t</sup></em>.</li>

</ul>

<ol start="3">

 <li>[10 points] Suppose we have two normal distributions, corresponding to two classes (<em>ω</em><sub>1 </sub>and <em>ω</em><sub>2</sub>) with the same covariances but different means: <em>N</em>(<strong><em>µ</em><sub>1</sub></strong>,<strong><em>Σ</em></strong>) and <em>N</em>(<strong><em>µ</em><sub>2</sub></strong>,<strong><em>Σ</em></strong>). In terms of their prior probabilities <em>P</em>(<em>ω</em><sub>1</sub>) and <em>P</em>(<em>ω</em><sub>2</sub>), state the condition that the Bayes decision boundary <em>not </em>pass between the two means.</li>

 <li>[10 points] Consider a two-class problem with the following class-conditional probability density functions (pdfs): <em>p</em>(<em>x | ω</em><sub>1</sub>) <em>∼ N</em>(0,<em>σ</em><sup>2</sup>)</li>

</ol>

and <em>p</em>(<em>x | ω</em><sub>2</sub>) <em>∼ N</em>(1,<em>σ</em><sup>2</sup>).

Show that the threshold, <em>τ</em>, corresponding to the Bayes decision boundary is:

<em>τ</em>= <em> −σ</em>2ln<em>λλ</em><sub>21</sub><u>12</u><em><sub>P</sub>P</em>(<sup>(</sup><em>ωω</em><sub>1</sub><u>2</u>))<sup></sup>,

where we have assumed that <em>λ</em><sub>11 </sub>=<em>λ</em><sub>22 </sub>= 0.

<ol start="5">

 <li>[15 points] Consider a two-category classification problem involving one feature, <em>x</em>. Let both classconditional densities conform to a Cauchy distribution as follows:</li>

</ol>

1     1 <em>p</em>(<em>x | ω<sup>i</sup></em><sup>)= </sup><em><sub>πb</sub></em>.<sub>1</sub>+ <em>x<u>−</u>ba</em><em><u>i </u></em>2,  <em>i </em>= 1,2.

Assume a 0-1 loss function and equal priors.

<ul>

 <li>Compute the Bayes decision boundary.</li>

 <li>Show that the probability of misclassification according to the Bayes decision rule is</li>

</ul>

1     1

<em>P</em>(<em>error</em>)= 2 <em>− π </em>tan<em>−</em>1<em>a</em><u>2</u>2<em>−ba</em><u>1</u>.

<ul>

 <li>Plot <em>P</em>(<em>error</em>) as a function of <em>|a</em><sub>2 </sub><em>− a</em><sub>1</sub><em>|/b</em>.</li>

 <li>What is the maximum value of <em>P</em>(<em>error</em>). Under what conditions will this occur?</li>

</ul>

<ol start="6">

 <li>[10 points] Consider the following class-conditional densities for a three-class problem involving twodimensional features:</li>

</ol>

<em>p</em>(<strong><em>x</em></strong><em>|ω</em><sub>1</sub>) <em>∼ N </em>(<em>−</em>1,<em>−</em>1)<em><sup>t</sup></em>,<em>I</em>; <em>p</em>(<strong><em>x</em></strong><em>|ω</em><sub>2</sub>) <em>∼ N </em>(1,1)<em><sup>t</sup></em>,<em>I</em>;

<em>p</em>.

(Here, class <em>ω</em><sub>3 </sub>conforms to a <strong>Gaussian Mixture Model (GMM) </strong>with two components – one component is <em>N </em>(0.5,0.5)<em><sup>t</sup></em>,<em>I</em> and the other component is <em>N </em> – whose weights are equal (i.e., )).

<ul>

 <li>In a 2D graph, mark the mean of <em>ω</em><sub>1</sub>, <em>ω</em><sub>2</sub>, and the two components of <em>ω</em><sub>3</sub>. In the same graph, mark the point <strong><em>x </em></strong>=(0.1,0.1)<em><sup>t</sup></em>.</li>

 <li>Assuming a 0-1 loss function and equal priors, determine the class to which you will assign the two-dimensional point <strong><em>x </em></strong>=(0.1,0.1)<em><sup>t </sup></em>based on the Bayes decision rule.</li>

</ul>

<ol start="7">

 <li>Consider the following bivariate density function for the random variable <strong><em>x</em></strong>:</li>

</ol>

0 20           10

<em>p<sup>original</sup></em>(<strong><em>x</em></strong>) <em>∼ N          </em>0 , 10     30    .

<ul>

 <li>[5 points] What is the whitening transform, <strong><em>A<sub>w</sub></em></strong>, of <strong><em>x</em></strong>? (You can use matlab (or any other programming language) to compute the eigenvectors/values).</li>

 <li>[3points]Whenthewhiteningtransformationisappliedto <strong><em>x</em></strong>, whatisthedensityfunction, <em>p<sub>transf orm </sub></em>of the resulting random variable?</li>

 <li>[5 points] Generate 10,000 bivariate <em>random </em>patterns from <em>p<sub>original </sub></em>(if you are using matlab, then the <em>mvnrnd </em>function can be used to generate these patterns). Plot these patterns in a graph.</li>

 <li>[5 points] Apply the whitening transform, <strong><em>A<sub>w</sub></em></strong>, to the 10,000 bivariate patterns generated above. Plot the transformed patterns in a separate graph.</li>

 <li>[2 points] Compare the patterns in 7c and 7d. <strong>What do you observe?</strong>.</li>

</ul>

<ol start="8">

 <li>Consider a two-category (<em>ω</em><sub>1 </sub>and <em>ω</em><sub>2</sub>) classification problem with equal priors. Each feature is a twodimensional vector <strong><em>x </em></strong>= (<em>x</em><sub>1</sub>, <em>x</em><sub>2</sub>)<em><sup>t</sup></em>. The class-conditional densities are:</li>

</ol>

<em>p</em>(<strong><em>x</em></strong><em>|ω</em><sub>1</sub>) <em>∼ N</em>(<em>µ</em><sub>1 </sub>=(0,0)<em><sup>t</sup></em>,<em>Σ</em><sub>1 </sub>= 2<em>I</em>), <em>p</em>(<strong><em>x</em></strong><em>|ω</em><sub>2</sub>) <em>∼ N</em>(<em>µ</em><sub>2 </sub>=(2,2)<em><sup>t</sup></em>,<em>Σ</em><sub>2 </sub>= <em>I</em>).

<ul>

 <li>[7 points] Compute the Bayes decision rule and the Bayes decision boundary.</li>

 <li>[3 points] Generate 10,000 bivariate <em>random </em>patterns from each of the two densities (if you are using matlab, then the <em>mvnrnd </em>function can be used to generate these patterns). Plot these patterns in a graph using different markers to distinguish the two classes. On the same graph, plot the Bayes decision boundary.</li>

 <li>[5 points] Compute and report the empirical error rate and the confusion matrix when classifying these 10,000 patterns using the Bayes decision policy.</li>

</ul>

<ol start="9">

 <li>Consider a two-category classification problem involving two-dimensional feature vectors of the form <strong><em>x </em></strong>= (<em>x</em><sub>1</sub>, <em>x</em><sub>2</sub>)<em><sup>t</sup></em>. The two categories are <em>ω</em><sub>1 </sub>and <em>ω</em><sub>2</sub>, and</li>

</ol>

<em>p</em>(<strong><em>x </em></strong><em>| ω</em><sub>1</sub>) <em>∼ N </em>(<em>−</em>1,<em>−</em>1)<em><sup>t</sup></em>,<em>I</em>, <em>p</em>(<strong><em>x </em></strong><em>| ω</em><sub>2</sub>) <em>∼ N </em>(1,1)<em><sup>t</sup></em>,<em>I</em>,

<em>P</em>.

<ul>

 <li>[10 points] Calculate the Bayes decision boundary and write down the Bayes decision rule assuming a 0-1 loss function. The Bayes decision rule has to be written in terms of the Bayes decision boundary.</li>

 <li>[5 points] What are the Bhattacharyya and Chernoff theoretical bounds on the probability of misclassification, P(error)?</li>

 <li>[5 points] Generate <em>n </em>= 25 test patterns from <em>each </em>of the two class-conditional densities and plot them in a two-dimensional feature space using different markers for the two categories (if you are using matlab, then the <em>mvnrnd </em>function can be used to generate these patterns). Draw the Bayes decision boundary on this plot for visualization purposes.</li>

 <li>[5 points] What is the confusion matrix and empirical error rate when classifying the generated patterns using the Bayes decision rule?</li>

 <li>[5 points] Can the empirical error rate exceed the theoretical bounds on the probability of misclassification? Why or why not? (Hint: Compute the empirical error rate multiple times by <em>repeatedly </em>generating <em>n </em>= 25 test patterns from <em>each </em>of the two class-conditional densities.)</li>

</ul>

<ol start="10">

 <li>[15 points] Consider a 1-dimensional classification problem involving two categories <em>ω</em><sub>1 </sub>and <em>ω</em><sub>2 </sub>such that <em>P</em>(<em>ω</em><sub>1</sub>) = 2<em>/</em>3 and <em>P</em>(<em>ω</em><sub>2</sub>) = 1<em>/</em> Assume that the classification process can result in one of three actions:</li>

</ol>

<em>α</em><sub>1 </sub>– choose <em>ω</em><sub>1</sub>; <em>α</em><sub>2 </sub>– choose <em>ω</em><sub>2</sub>; <em>α</em><sub>3 </sub>– do not classify.

Consider the following loss function, <em>λ</em>:

<em>λ</em>(<em>α</em><sub>1</sub><em>|ω</em><sub>1</sub>)=<em>λ</em>(<em>α</em><sub>2</sub><em>|ω</em><sub>2</sub>)= 0; <em>λ</em>(<em>α</em><sub>2</sub><em>|ω</em><sub>1</sub>)=<em>λ</em>(<em>α</em><sub>1</sub><em>|ω</em><sub>2</sub>)= 1; <em>λ</em>(<em>α</em><sub>3</sub><em>|ω</em><sub>1</sub>)=<em>λ</em>(<em>α</em><sub>3</sub><em>|ω</em><sub>2</sub>)= 1<em>/</em>4.

For a given feature value <em>x</em>, assume that <em>p</em>(<em>x|ω</em><sub>1</sub>)= <u><sup>2</sup></u><em><u>−</u></em><sub>2</sub><em><u><sup>x </sup></u></em>and <em>p</em>(<em>x|ω</em><sub>2</sub>)= 1<em>/</em>2. Here, 0 <em>≤ x ≤ </em>2.

Based on the Bayes minimum risk rule, what action will be undertaken when encountering the value <em>x </em>= 0.5?