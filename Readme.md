> Written with [StackEdit](https://stackedit.io/).
StatisticToolBox
===================
StatisticToolBox is an open source software for the automatic calculation of statistic indices of data series.

![enter image description here](https://lh3.googleusercontent.com/-hKj6fM4w-0c/Vm1DlQ_8PCI/AAAAAAAAJdI/gnZclnhn_FI/s0/01_global.png "StatisticToolBox.png")

Statistic indices calculated
----------------------------
Central tendency:

 - average;
 - median;
 - quantile.

Variability:

 - variance;
 - standard deviation;
 - absolute average deviation;
 - variation coefficient.

Form:

 - skewness
 - kurtosis.

Other:

 - covariance;
 - Pearson product-moment correlation coefficient;
 - linear regression.

User guide
----------
Insert one or two (optional) data series into the corresponding input box; the data series numbers can be separated by a space ' ' or a comma ','.

![enter image description here](https://lh3.googleusercontent.com/-LWE0tUnG3sw/Vm1Da0H6byI/AAAAAAAAJc8/pAi0wBi3Tpk/s0/02_input.png "Series_input.png")

The quantile input have to be in a real range value of [0, ..., 1], using '.' just before the decimal part of number (example of input are 0.25, .4, 0.74, .56, etc).

![enter image description here](https://lh3.googleusercontent.com/-m7BGYG3tTZE/Vm1Dvvc7goI/AAAAAAAAJdU/CVBGdQwooS8/s0/03_qinput.png "quantile_input.png")
In case of wrong input the software will launch a error window that explain what is the invalid input.

To calculate the covariance, linear regression and Pearson indices, the data series **must** have the same number of elements, otherwise they will not be calculated.

To calculate all indices you have to click the 'Go (calculate)!' button.
You can reset all values clicking the 'Reset' button; in case you modify your data series and don't want to reset all values, you can press the 'Go (calculate)!' button for a new calculation, expecting that all calculations are made as a new calculation with no influence from past calculations.

Executable java archive
---------------
The executable java archive (jar) can be found in folder /dist; to be executed it need the java runtime environment (jre).

Compiling/developing
--------------------
The project has been developed with NetBeans IDE, so you can simply import in it (NetBeans) and directly view the GUI/source code/build, or you can modify with your favorite text editor/IDE.
Known bugs
---------
Nothing at the moment of writing.
License
-------
Apache License v2 https://www.apache.org/licenses/







