# Creating Index Fund
 The objective of this project is to create an index fund by choosing the most representative funds from the portfolio of NASDAQ. 
 I solved this problem in two phases:
  - Integer Programming: Selection of stocks is an integer programming problem.The objective of the problem is to keep minimum stocks that are best representative of the majority of stocks in the fund. The notion of similarity was calculated using the correlation between the daily returns for each stock.
  - Linear Programing: Once the stocks have been selected, they need to be weighted in the portfolio. The weighing was done with the objective of minimzing the total absolute deviation between the fund returns and the index fund returns.


In addition to that, I aslo posed this problem as a mixed integer programming and compared the results for both the approaches.  
  
