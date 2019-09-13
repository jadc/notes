# Mean
![Mean Formula](https://latex.codecogs.com/gif.latex?\dpi{400}\bar{x}=\frac{\sum&space;x}{n})

The sum of all data points divided by the amount of data points.

# Standard Deviation
![Standard Deviation Formula](https://latex.codecogs.com/gif.latex?\dpi{400}\sqrt{\frac{\sum(x-\bar{x})^2}{n-1}})  
> Sidenote: This is the *sample* standard deviation formula.

## What?
The standard deviation describes the average distance away from the mean that your values are.  
Not a perfect definition, but it means that when you plot a data point, you plot the mean.  
Then draw an error bar that's vertical length extends &#177; the standard deviation.

## How?
To perform standard deviation on your data, follow these steps.  
1. Calculate the mean of all your data.  
![Mean Formula](https://latex.codecogs.com/gif.latex?\dpi{200}\bar{x}=\frac{\Sigma&space;x}{n})  

2. Calculate the variance.
   1. For every data point (x) subtract it with the mean (x&#772;).

   ![SD Step 1](https://latex.codecogs.com/gif.latex?\dpi{200}x-\bar{x})

   2. Square all of that.

   ![SD Step 2](https://latex.codecogs.com/gif.latex?\dpi{200}\left(x-\bar{x}\right)^2)

   3. Repeat that for every data point, then add all of these values together.

   ![SD Step 3](https://latex.codecogs.com/gif.latex?\dpi{200}\sum\left(x-\bar{x}\right)^2)

   4. Divide that sum by the number of data points (n) subtracting 1.

   ![SD Step 4](https://latex.codecogs.com/gif.latex?\dpi{200}\frac{\sum\left(x-\bar{x}\right)^2}{n-1})

3. Square root the variance.

![SD Step 5](https://latex.codecogs.com/gif.latex?\dpi{200}\sqrt{\frac{\sum\left(x-\bar{x}\right)^2}{n-1}})

4. That is your standard deviation!

# Example

This is the data we are going to use.

| &#xfeff;    | Width of Jad's Nose<br>/ cm &#177; 0.1 cm |
| :---------: | :-: |
|             | 8.0 |
|             | 4.2 |
|             | 6.5 |
|             | 3.9 |
|             | 0.9 |
| **x&#772;** | ??? |
|    **s**    | ??? |

First, we need the mean. Add up all the values in the table and divide them by how many values there are. In our case, the sum is `23.5` and we have `5` values.

![mean = 23.5 / 5](https://latex.codecogs.com/gif.latex?\dpi{150}\bar{x}=\frac{23.5}{5})

![mean = 4.7](https://latex.codecogs.com/gif.latex?\dpi{150}\bar{x}=4.7)

---

Now for the actual challenge. Standard deviation.

![](https://latex.codecogs.com/gif.latex?\dpi{150}=\(8.0-4.7\)^2+\(4.2-4.7\)^2+\(6.5-4.7\)^2+\(3.9-4.7\)^2+\(0.9-4.7\)^2)  
![](https://latex.codecogs.com/gif.latex?\dpi{150}=\(3.3\)^2+\(-0.5\)^2+\(1.8\)^2+\(-0.8\)^2+\(-3.8\)^2)  
![](https://latex.codecogs.com/gif.latex?\dpi{150}=10.89+0.25+3.24+0.64+14.44)   
![](https://latex.codecogs.com/gif.latex?\dpi{150}=29.46)

That covers the numerator, now for the denominator of the variance. Since this is the sample formula, we use `n - 1`.

![](https://latex.codecogs.com/gif.latex?\dpi{150}\frac{29.46}{5-1})  
![](https://latex.codecogs.com/gif.latex?\dpi{150}=7.365)

This is the variance. Just square root this value to get the standard deviation.

![](https://latex.codecogs.com/gif.latex?\dpi{150}\sqrt{7.365})  
![](https://latex.codecogs.com/gif.latex?\dpi{150}=2.713853349)

Now we can finish our table, to the same percision (number of decimal places) and significant digits.

| &#xfeff;    | Width of Jad's Nose<br>/ cm &#177; 0.1 cm |
| :---------: | :-: |
|             | 8.0 |
|             | 4.2 |
|             | 6.5 |
|             | 3.9 |
|             | 0.9 |
| **x&#772;** | 4.7 |
|    **s**    | 2.7 |