<h1>Multivariate interpolation</h1>

<h2>Description</h2>

There are many situations where interpolation needs to be applied to higher dimensional problems, for instance in cartography, image processing, or in simulations of physical systems. Thankfully the process for this is conceptually straightforward; we simply apply the rules of interpolation in 1D in each direction for the higher dimensional problem. The only real trouble is in the application.

The aim of this project is to extend univariate methods of interpolation to higher dimensions. In the first part of the project we consider the case of *bilinear* interpolation, i.e. linear interpolation in two dimensions. In the second part we consider the case of *bivariate polynomial* interpolation, i.e. polynomial interpolation in two dimensions. We derive the interpolation rules by 'convolution', or composition, of the 1D rule in each direction; in our project, by rules we mean using Lagrange basis to obtain a Lagrange interpolant. Lastly, we carry out the error analysis for some bivariate methods.

<h2>Repository Content</h2>

- <b>LaTeX Report (source and pdf)</b>
- <b>Jupyter notebook containg the code used to compute results and produce plots</b>
