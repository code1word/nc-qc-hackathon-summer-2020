# Qiskit Community Summer Jam 2020 - North Carolina


**Team Name: NCSSM Unicorns**

**Team Members: Dhruv Yalamanchi, Daniel Jin, Joseph Campbell, Shardool Deshpande, Akshat Kumar**

Hello! We are the NCSSM Unicorns, a group of rising 12th graders at the NC School of Science and Math, and for our Quantum Hackathon project, we have implemented a cubic spline generator, integrating features of Qiskit along the way. Cubic splines are useful for the approximation of complex curves and have applications in numerous areas such as statistics, computer graphics, image processing, aeronautical engineering, and many more. The objective of our project is two-fold; we first implement a quantum function that generates random points within a specified range on a target curve. We then generate a smooth curve that passes through this set of points via a cubic spline interpolation to approximate the target curve.

As an example, suppose we are trying to approximate the function *y = cos(x)*:

![Curve to be Approximated](https://github.com/code1word/nc-qc-hackathon-summer-2020/blob/master/Curve.png)

Our program generates random points along the curve to be used in the interpolation. It then produces a smooth, continuous curve that passes through all of these points, as shown below:

![Generated Cubic Spline](https://github.com/code1word/nc-qc-hackathon-summer-2020/blob/master/Cubic%20Spline.png)

The following is a plot of the residuals between our cubic spline approximation and the target curve. As can be seen here, the cubic spline provides a rather accurate approximation for the target curve, making it a useful tool in various modeling applications.

![Residuals](https://github.com/code1word/nc-qc-hackathon-summer-2020/blob/master/Residuals.png)
