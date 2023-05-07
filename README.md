Download Link: https://assignmentchef.com/product/solved-fin5330-homework-2
<br>
<h1>Problem 1</h1>

<ol>

 <li>Simulate <em><sub>T </sub></em>= 500 observations from an <em><sub>AR</sub></em>(1) process for <em><sub>φ </sub></em>= <em>{</em>0<em><sub>.</sub></em>25<em><sub>,</sub></em>0<em><sub>.</sub></em>5<em><sub>,</sub></em>0<em><sub>.</sub></em>75<em><sub>,</sub></em>0<em><sub>.</sub></em>8<em><sub>,</sub></em>0<em><sub>.</sub></em>9<em>}</em>.</li>

</ol>

<em>y</em><em>t </em>= <em>φy</em><em>t−</em>1 + <em>t</em>

<ol start="2">

 <li>Treat the artificial from the simulations above as observed data by an econometrician.</li>

 <li>Estimate each model via OLS.</li>

 <li>Test the standard null hypothesis of <em><sub>φ </sub></em>= 0 with a standard <em><sub>t</sub></em>-test for significance levels <em><sub>{</sub></em>0<em><sub>.</sub></em>01<em><sub>,</sub></em>0<em><sub>.</sub></em>05<em><sub>,</sub></em>0<em><sub>.</sub></em>10<em><sub>} </sub></em>for each one and report the results in a table. Provide test statistics, standard errors, critical values, p-values, etc.</li>

 <li>Pick one of the parameter values for the models above and do the following:

  <ul>

   <li>Use the Central Limit Theorem to derivive a sampling distribution for <em><sub>φ</sub></em>ˆ. Present the parameter values of the sampling distribution. Produce a graph of the distribution.</li>

   <li>Use parametric Monte Carlo to simulate the sampling distribution. Use <em><sub>M </sub></em>= 10<em><sub>,</sub></em>000 repititions. Use the sample mean and standard deviation to estimate the parameter values of the distribution. Produce a histogram.</li>

   <li>Use the IID Bootstrap to simulate the sampling distribution. Use <em><sub>B </sub></em>= 10<em><sub>,</sub></em>000 repititions. Use the sample mean and standard deviation to estimate the parameter values of the distribution. Produce a histogram.</li>

   <li>Compare all three methods.</li>

   <li>Can you interpret the last two distributions as predictive densities?</li>

  </ul></li>

 <li>Return to the problem in 5 above and redo the simulation from step one, but replace the error distribution with a Student-T distribution with <em><sub>df </sub></em>= 5 (degrees of freedom parameter). Even though we know at the generation stage that the errors come from the Student-T distribution, the econometrician assumes a normal distribution when using the CLT and parametric Monte Carlo. The bootstrap obviously does not need to make such assumptions. Compare to the results above.</li>

</ol>

<h1>Problem 2</h1>

Simulate an <em><sub>AR</sub></em>(1) process with parameter <em><sub>φ </sub></em>= 0<em><sub>.</sub></em>8 by using the <em><sub>MA</sub></em>(<em>∞</em>) representation. <strong><sub>Hint: </sub></strong>you will have to truncate the <em><sub>MA</sub></em>(<em><sub>∞</sub></em>) representation, yielding an approximation to the <em><sub>AR</sub></em>(1). Recall that the <em><sub>AR</sub></em>(1) can be represented by the following (i.e. the <em><sub>MA</sub></em>(<em><sub>∞</sub></em>) representation):

<em>x<sub>t </sub></em><em><sub>t−j                       </sub></em>where <em><sub>x</sub></em><sub>0 </sub>is the initial condition.

<em>j</em>=0

<ul>

 <li>Plot the simulated time series.</li>

 <li>Estimate <em><sub>φ</sub></em>ˆ via OLS. Report the usual suspects.</li>

</ul>

<h1>Problem 3</h1>

Take the <em><sub>AR</sub></em>(1) model above:

<em>y<sub>t </sub></em>= <em>φy<sub>t−</sub></em><sub>1 </sub>+ <em>ε<sub>t                     </sub></em>with <em>φ </em>= 0<em>.</em>8

<ul>

 <li>Run the following simulation:</li>

 <li>Set <em>ε</em><sub>0 </sub>= 1<em>.</em>0 <strong>– </strong>Set <em>y</em><sub>0 </sub>= 0<em>.</em>0 <strong>– </strong>Set all <em>ε<sub>t </sub></em>= 0<em>.</em>0 for <em>t &gt; </em>0</li>

 <li>Plot the simulated process <em>{</em><em><sub>y</sub>}<sup>T</sup><sub>t</sub></em><sub>=0 </sub>as a function of time. This is called the <strong><em>impluse response function</em></strong>. Interpret it in terms of the <em><sub>MA </sub></em>(<em><sub>θ</sub></em>) coefficients for the <em><sub>AR</sub></em>(1) representation.</li>

 <li>Simulate <em><sub>T </sub></em>= 50 time steps in the process.</li>

</ul>

<h1>Problem 5</h1>

Simulate <em><sub>T </sub></em>= 500 observations from the following ARMA model:

<em>y</em><em>t </em>= <em>φ</em>1<em>yt − </em>1 + <em>φ</em>2<em>y</em><em>t−</em>2 + <em>θ</em>1<em>ε</em><em>t−</em>1 + <em>θ</em>2<em>ε</em><em>t−</em>2 + <em>ε</em><em>t</em>

Choose appropriate values for the <em><sub>AR </sub></em>and <em><sub>MA </sub></em>coefficients, as well as for <em><sub>σε</sub></em>.

<ul>

 <li>Plot the simulated time series.</li>

 <li>Calculate <em>γ</em><sub>0</sub>, <em>γ</em><sub>1 </sub>and <em>γ</em><sub>2</sub>.</li>

</ul>

<h1>Problem 6</h1>

<ul>

 <li>Simulate <em><sub>T </sub></em>= 500 time steps for the following two equations:</li>

</ul>

<em>y</em><em>t </em>= <em>y</em><em>t−</em>1 + <em>u</em>1<em>,t </em><em>x</em><em>t </em>= <em>x</em><em>t−</em>1 + <em>u</em>2<em>,t</em>

<ul>

 <li>where <em><sub>uj,t </sub></em><em><sub>j </sub></em>= 1<em><sub>,</sub></em>2 are independent standard white noise processes.</li>

 <li>Next regress <em><sub>yt </sub></em>on <em><sub>xt </sub></em>and estimate <em><sub>β </sub></em>(slope coefficient) via OLS in the following regression</li>

</ul>

<em>y<sub>t </sub></em>= <em>α </em>+ <em>βx<sub>t </sub></em>+ <em><sub>t</sub></em>

<ul>

 <li>Test the null hypothesis <em><sub>H</sub></em><sub>0 </sub>: <em><sub>β </sub></em>= 0 against the alternative <em><sub>Ha </sub></em>: <em><sub>β </sub></em>= 0<em><sub>6 </sub></em>. Use the standard <em><sub>t</sub></em>-test with standard significance levels (0.01, 0.05, and 0.10). What should you find? What do you find?</li>

 <li>Repeat the process <em><sub>M </sub></em>= 50<em><sub>,</sub></em>000 times and store the <em><sub>β </sub></em>coefficients for each run of the simulation.</li>

 <li>Summarize the simulated sampling distribution for <em><sub>β</sub></em>.</li>

 <li>Make a histogram plot of the simulated coefficients.</li>

</ul>

<h1>Problem 7</h1>

<ul>

 <li>Repeat the exercise in Problem 1 above for <em><sub>φ </sub></em>= 1<em><sub>.</sub></em></li>

 <li>Comment on your findings.</li>

</ul>

<h1>Problem 8</h1>

<ul>

 <li>Simulate <em><sub>T </sub></em>= 500 time steps from the random walk model</li>

</ul>

<em>x</em><em>t </em>= <em>x</em><em>t−</em>1 + <em>u</em>1<em>,t </em>• Next simulate <em><sub>T </sub></em>= 500 time steps from the model

<em>y<sub>t </sub></em>= <em>α </em>+ <em>βx<sub>t </sub></em>+ <em><sub>t</sub></em>

<ul>

 <li>Where <em><sub>α </sub></em>= 0<em><sub>.</sub></em>22 and <em><sub>β </sub></em>= 2<em><sub>.</sub></em></li>

 <li><em>∼ </em><em><sub>N</sub></em>(0<em><sub>,</sub></em>1) (white noise process)</li>

 <li>Use the Augmented Dickey-Fuller Test to check for the presence of a unit-root in both <em><sub>yt </sub></em>and <em><sub>xt</sub></em>. What do you find? What should you find?</li>

 <li>Implement the Engle-Granger two-step method by:

  <ul>

   <li>First, test for cointegration by submitting ˆ<em><sub>t </sub></em>to the ADF Test. What do you find?</li>

   <li>Obtain <em><sub>β</sub></em>ˆ via OLS.</li>

   <li>Estimate the error-correction model with <em><sub>p </sub></em>= 1 and include contemporaneous <em><sub>xt</sub></em>.</li>

  </ul></li>

</ul>