# Principles_of_Data_Analytics_mywork

**by Matthias Wiedemann**

Student at [ATU] (https://www.atu.ie/).

![Penguins](https://allisonhorst.github.io/palmerpenguins/reference/figures/lter_penguins.png)


## About this project

This project is the [assessment](https://ianmcloughlin.github.io/2324_principles_of_data_analytics/) for the Principles of Data Analytics module. It focuses on the widely available [palmerpenguins data set](https://raw.githubusercontent.com/mwaskom/seaborn-data/master/penguins.csv).
The data set is an excellent base to explore and demonstrate the following items:

    1. Source and investigate sets of data.
    2. Programmatically explore and visualize data.
    3. Apply basic mathematical data analysis techniques to data sets.
    4. Model real-world problems for analysis by computer.
    5. Provide evidence in a decision-making process using a data set.
    6. Appreciate the limitations of graphical representations in data intensive workflows.


## Use of This Project

The project serves as an analysis of the correlation between two select variables from the data set. 


## Tools

For data frames: [Pandas](https://pandas.pydata.org/) is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language. 

For plotting: [Metplotlib](https://matplotlib.org/stable/) is a comprehensive library for creating static, animated, and interactive visualizations.

For numerical arrays: [Numpy](https://numpy.org/). The fundamental package for scientific computing with Python.

# Table of content

* [1. About the data](#1-about-the-data)
* [2. Imported libraries and modules](#2-imported-libraries-and-modules)
    * [2.1 For data frames: Pandas](#21-for-data-frames-pandas)
    * [2.2 For plotting: Matplotlib](#22-for-plotting-matplotlib)
    * [2.3 For numerical arrays: Numpy](#23-for-numerical-arrays-numpy)
    * [2.4 Load the penguins data set](#24-load-the-penguins-data-set)
* [3. Data frame and determination of variables](#3-data-frame-and-determination-of-available-variables)
    * [3.1 Overview and taking the data apart](#31-overview-and-taking-the-data-apart)
    * [3.2 Number of occurences of each sex](#32-number-of-occurences-of-each-sex)
* [4. Islands](#4-islands)
    * [4.1 Number and sex on each island](#41-number-and-sex-on-each-island)
    * [4.2 Number of penguins of each set](#41-number-and-sex-on-each-island)
    * [4.3 Summary](#43-summary)
* [5. Data types](#5-data-types)
    * [5.1 Inspect](#51-inspect)
* [6. Numeric values](#6-numeric-values)
* [7. Numpy arrays](#7-numpy-arrays)
    * [7.1 Flipper length in mm](#71-flipper-length-in-mm)
    * [7.2 Bill length in mm](#72-bill-length-in-mm)
    * [7.3 Bill depth in mm](#72-bill-length-in-mm)
    * [7.4 Body mass in gram](#74-body-mass-in-gram)
* [8. Visualization of Palmer penguins data](#8-visualization-of-palmer-penguins-data)
    * [8.1 Body mass of the three species in a histogram](#81-body-mass-of-the-three-species-in-a-histogram)
    * [8.2 Quantities of samples taken on each island](#82-quantities-of-samples-taken-on-each-island)
    * [8.3 Penguin attributes by species](#83-penguin-attributes-by-species)
* [9. Two variable plots](#9-two-variable-plots) 
    * [9.1 Bill length vs bill depth](#91-bill-length-vs-bill-depth)
    * [9.2 Flipper length vs. body mass](#92-flipper-length-vs-body-mass)
* [10. Add best fit line](#10-add-best-fit-line)
    * [10.1 Remove NaN values](#101-remove-nan-values)
    * [10.2 Fit straight line between X and Y](#102-fit-straight-line-between-x-and-y)
    * [10.3 np.linspace](#103-nplinspace)
    * [10.4 Plot best fit line on top of scatter plot](#104-plot-best-fit-line-on-top-of-figure)
* [11. Correlation coefficient](#11-correlation-coefficient)
* [12. Further reading and references](#12-further-reading-and-references)