# dataMining 
an simple process on a dataset  

# introduce 
My dataset is from kaggle,below is the link:  
Wine Reviews:  
https://www.kaggle.com/zynicide/wine-reviews. 

It's a dataset about wine,someone has give each kind of wine a point.  
I want to do some pre-process in the dataset,like a statisic count and fill in some value to replace the 'NaN' value.  
My code is write in python in jupyter notebook which I put in the file 'code.ipynb'.  
  
If you want to run it,please prepare:  
1.numpy  
2.pandas  
3.scipy  
4.matplotlib  
5.plotly  
  
# data statistic  
For number colume,I choose an example colume named 'Price'.And I count like this:  
![image](https://github.com/xcircle/dataMining/blob/master/image/2.jpg)

For non-number colume,I choose an example colume named 'Region1'.And I count like this:  
![image](https://github.com/xcircle/dataMining/blob/master/image/1.jpg)

# visionlize  
I use quantile-quantile plot to show 'Price' match the normal distribution.  
![image](https://github.com/xcircle/dataMining/blob/master/image/3.jpg)  

The Box Plot is a plot that shows the distribution of 'Price'.  
![image](https://github.com/xcircle/dataMining/blob/master/image/4.jpg)  

# fill in NaN data  
I choose two ways to fill in the 'NaN' data:  
1.ignore the one is fill with 'NaN'  
2.replace the 'NaN' with the average number  
first is ignore:  
![image](https://github.com/xcircle/dataMining/blob/master/image/5.jpg)  
then I draw a plot comparing with the two method:  
![image](https://github.com/xcircle/dataMining/blob/master/image/6.jpg)  
We can see the two plot are very similar in shape,only the average num in the right is more larger.

And I'm exploring more method to fill in the 'NaN' data more wisely.
I'll continue to focus on this!

