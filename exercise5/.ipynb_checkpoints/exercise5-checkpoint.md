# Exercise 5
We have seen how the marginal propensity to consume and the parameter that determines the interest rate sensitivity of the consumer affect the IS equation. In this assignment, we will use Excel (or another suitable analysis tool, such as STATA or Python) to find these two parameters.
The consumption function of the IS-RR-PK model is given by:

C = z<sup>C</sup> + c<sub>1</sub> (Y-T) – c<sub>2</sub> (i-&pi;<sup>e</sup>)

The challenge with this equation is that C and Y-T are increasing over time (this is called non-stationary variables). In contrast, the real interest rate, (i-&pi;<sup>e</sup>), is a more or less stationary variable. A stationary variable is a variable that, quite simply, does not have a rising or falling trend.
Calculating models with non-stationary variables can be challenging. Therefore, we look at the difference of the variables:
The model we must count on is thus:
	Δc_t=z^C+c_1 Δy_t^D-c_2 (i_t-π_t^e)
&Delta; c <sub>t</sub>  = z<sup>C</sup> + c<sub>1</sub>&Delta;y<sup>D</sup><sub>t</sub> + c<sub>2</sub>(i<sub>t</sub>-&pi<sub>t</sub><sub>e</sub>)

Where &Delta; is what we call the differential operator and y<sup>D</sup> is the logarithm of real disposable income &Delta;y=log(Y<sub>t</sub> - T<sub>t</sub>). Where P<sub>t</sub> is the prices at time t. 

We find that &Delta;c = log C<sub>t</sub> - log C<sub>t-1</sub>

## Assignments

1. Create a figure showing the development in consumption, C, real disposable income, YD and the real interest rate. Briefly summarize what this figure shows
2. Create a similar figure, but replace with change in consumption and real disposable income, Dc and Dyd.
3. Try running an equation regression (1). Use Excel, STATA or Python
4. Briefly describe the parameters you find and correspond to what we have learned in the lectures
