# Economic-Shocks-Modeling

The crux of this project is the idea to decompose the variation in the US stock market and the Treasury yield curve into orthogonal shocks which have an intuitive economic interpretation. They isolate growth news, monetary news, and two distinct shocks generating time-varying risk premiums as common drivers of stocks and yields, recognizing that stocks and yields are differentially exposed to those shocks. Our aim is to model and explain the movement, or more importantly the comovement of these stocks and bond returns as a function of these 4 orthogonal shocks.

We make use of Structural Vector Autoregression (VAR) to model internal states of the ecnomoy. We impose sign restrictions on the VAR Matrix according to the definition and intuitions of the Shocks. Then we use Cholesky Decomposition and simulation to recover the shocks.

This project is a crude but not exact implementation of the following paper: Common shocks in stocks and bonds : https://www.sciencedirect.com/science/article/pii/S0304405X21002749
We have shown similaraties, reconstruction of the results and differneces between the method in the above mentioned project and our implementation in the report.
