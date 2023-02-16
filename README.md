# Lagrange-Interpolation
## Introduntion to Lagrange method
![image](https://user-images.githubusercontent.com/125180530/219422013-f5b3b9dc-543f-416d-922c-63437e57c72e.png)

![image](https://user-images.githubusercontent.com/125180530/219422084-24a945bb-f7e7-4ee2-9770-ab7d0611b0c1.png)

![image](https://user-images.githubusercontent.com/125180530/219422151-0482cb0c-fb02-4ffe-b41c-327ce6fb54a8.png)

In the following figure you can see some results of using this method for polynomial interpolation:

![image](https://user-images.githubusercontent.com/125180530/219422461-f52e01a8-5d79-4872-8b45-53fbbbea1a0d.png)

When constructing interpolating polynomials, there is a tradeoff between having a better fit and having a smooth well-behaved fitting function. The more data points that are used in the interpolation, the higher the degree of the resulting polynomial, and therefore the greater oscillation it will exhibit between the data points. Therefore, a high-degree interpolation may be a poor predictor of the function between points, although the accuracy at the data points will be "perfect."

![image](https://user-images.githubusercontent.com/125180530/219423053-5a316711-aca1-4586-bb0d-54eca9656823.png)

![image](https://user-images.githubusercontent.com/125180530/219423147-ad16d82a-86a2-4257-abf2-e3d025fc0689.png)

![image](https://user-images.githubusercontent.com/125180530/219423191-07745df5-7d99-447e-99ca-d79ba9cdcc78.png)

## Implementing an example:
Using the Lagrange Interpolation method, we estimate polynomials that can pass through the following given points:

![image](https://user-images.githubusercontent.com/125180530/219423773-389a0422-4c0b-45e6-b755-7f4770bcaa18.png)

f(x) is:

![image](https://user-images.githubusercontent.com/125180530/219424496-ef24e520-ee0e-47be-b9bc-7f24e067fa7a.png)

* We first find polynomials of the degrees 3 to 6 we sets of random points for each case.

* For a better comparison between f(x) and the estimated polynomials, we plot them in the same graph. 

* Now for evaluating the accuracy of the estimated polynomials, we plot the error values between f(x) and other polynomials.

## Conclusion
From the figure in which we plot the f(x) and all interpolated polynomials, it's obvious that the best degree for this estimation is 6. The 6th-degree polynomial could better pass through the points and its curvature is more similar to f(x) than other polynomials.

In addition, by looking at the plot of errors we can conclude that because the error values in the 6th-degree polynomial are less than others, the best degree to use for interpolation is 6. In general, the greater the degree of a polynomial, the better it can fit a curvature for the given points.
