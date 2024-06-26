### Lasso and K-mean Cluster for Viscoelestic Material

<p align="justify">The goal of this research is to determine the coefficient of the Maxwell series for laminated glass, which is a visco-elastic material, using experimental data. This data was obtained from dynamic tests on composite glass specimens with a PVB interlayer, laminated by Roberglass. The tests provided storage and loss modulus values at different frequencies. Calculating the shear modulus from these values using traditional methods is complicated. To simplify this, I initially used Lasso regression techniques in my first project to find an optimal solution. However, Lasso regression resulted in too many coefficients for the Maxwell series. Therefore, in this research, I combined K-means clustering with Lasso regression to reduce the number of coefficients. This combined method produces better results than using Lasso regression alone, making the process more efficient.</p>


<p><b>Conventional Technique</b></p>
<p align="center">
  <img src="CM_AA_Method.jpg" title="hover text">
</p>
<br/>
<br/>
<p><b>Machine Learning Technique (Lasso and K-mean Cluster)</b></p>
<p align="center">
  <img src="LR_KM_Method.jpg" title="hover text">
</p>






