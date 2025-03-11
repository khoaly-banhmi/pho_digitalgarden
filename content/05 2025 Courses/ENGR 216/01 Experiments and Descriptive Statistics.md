---
title: 01 Experiments and Descriptive Statistics
description: When measuring, there are errors and differences between measurements. How can we know which number to choose?
tags:
  - TAMU
  - Spring
  - 🌱Seed
date: 2025-1-16
share: true
---
## Purpose of this lesson:

1. Why do we do experiments?
2. What are we hoping to get from them?
3. Should you repeat an experiment more than once?
After reviewing the lesson, go back and answer these questions.

## Experimental errors

There are always errors when we measure things. Errors place limits on engineering designs, so understanding them is crucial. 
### What are errors?
 * Difference between the **measured or calculated value** and the **true value**.
 * Engineers need to:
	 * Recognize errors
	 * Identify the different types of errors
	 * Express them in numbers
	 * Identify how confidence they are when expressing a number
### Describing errors
There are multiple ways to express errors:
* True error = Reported value - True value
* Fractional error = True error / True value
* Percent error = Fractional error * 100%
### Types of errors:
1. Systematic errors: errors caused by a regular and may be known outside occurrence. For example, a compass is not pointing to the true North because of a magnet attached on the compass. 
	* **Can be corrected**: you can take into account the error
	* **Repeating measurement will not eliminate the error**, however will provide narrower values. 
2. Random (Accidental) errors: randomly happen
	* The scatter
	* **Impossible to know why they occur**, and they don't have a fixed magnitude
	* **Repeating measurements will reduce them**.

### Accuracy and precision:
1. Accuracy: the nearness to the true value --> instrument's calibration
2. Precision: the repeatability of the measurements --> the instrument's design and the user experience in using the instrument.
![[Pasted image 20250302115421.png|Pasted image 20250302115421.png]]

### Why are there errors?
Because the world is not perfect. Sigh. 

## Estimating errors with repeated measurements

Determining uncertainty with single measurements is easy. When dealing with lots and lots of data, you can use statistics to determine uncertainty.

You measure something a bunch of times, you get a table of measurements, now what should you do? You determine the data accuracy and precision using these things:
### Histogram
Histogram is a plot displaying the values and their occurrences. It illustrates a values are distributed in a range. 

Guidelines:
1. There should be no less than 6 classes
2. $\sqrt{ n }$ provides an estimate on how many classes to consider
3. Classes should accommodate all data points
4. Each data point only fits in **ONE** class
5. Make the class intervals equal in length

### Describing the center of a data set
1. Mean (or average): this becomes better as n increases
$$
\bar{x}=\frac{x_{1}+x_{2}+\dots+x_{n}}{n}
$$
1. Median: the center value of an ordered set of data
2. Mode: the value that has the greatest frequency 
### Measurement of variation
To measure the spread of a data set
1. Max and min (or range)
2. Variance
3. Standard Deviation

#### Population measurement of variation
1. Mean of population:
$$
\mu =\frac{1}{n}\sum_{i=1}^{n}x_{i}
$$
2. Population variance: the degree of spread
$$
\sigma^2=\frac{1}{n}\sum_{i=1}^{n}(x_{i}-\mu)^2
$$
3. Population standard deviation: the square root of variance
$$
\sigma=\sqrt{ \sigma^2 }
$$
#### Sample measurement of variation
1. Mean of sample
$$
\bar{x}=\frac{1}{n}\sum_{i=1}^{n}x_{i}
$$
2. Sample variance
	1. Small sample:
$$
s^2=\frac{1}{n-1}\sum_{i=1}^n(x_{1}-\bar{x})^2
$$
	2. Very large sample:
$$
s^2=\frac{1}{n}\sum_{i=1}^n(x_{1}-\bar{x})^2
$$
3. Sample standard deviation: $s=\sqrt{ s^2 }$
### Standard error
$$
\text{error}=\frac{\text{standard deviation}}{\sqrt{ n }}
$$
This is the standard error of the mean.