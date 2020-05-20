# assign_4_204
Lizzie, Gavi &amp; Simone Embark on Discounting and Economic Model Building 
Homework #4 (A Climate Change Model) – conceptual notes 
By Gavi, Lizzie, Simone
5/19/2020

Formulas & Parameters: 

1. Under BAU, let r(t) be the temperature in year t (t = 0, 1, ..., 200) relative to the
temperature at time 0; Suppose r(t) = min(Tt/100, T) 
-	Where T is the BAU temperature increase at year 100. For example, if T = 5 then the
temperature increases over time (linearly) until year 100, when it flattens out at 5.
The hotter it is, the more it affects daily life and it starts to eat away at economic
activity. 

2. Let K(t) be the fraction of economic activity that is retained in a year if the
temperature is K(t), given by K(t) = exp(−Br(t)^2)

3 . Economic activity (“consumption”) grows over time at rate g, but is reduced by K, so total consumption at time t is: C(t) = K(t)exp(gt) 

4. Society’s utility from consumption is given by the function U(C) = C1−n/1 – n
- For some analyses below, you may wish to discount utility to present value. 

-5. The discount rate is given by the Ramsey Rule: r = s + ng 

#Base case parameters for this model: s= .005, n = .5, g = .01, B= .05.
-	n: elasticity of marginal utility of consumption with respect to income (home much more does a poor person value a dollar compared to a rich person)
-	 s: pure rate of time preference 
-	g: growth rate of income over time 

