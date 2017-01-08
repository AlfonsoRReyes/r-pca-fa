# Motivation

The purpose of this repository is documenting a little bit of (introduction) to Principal Component Analysis (PCA) and Factor Analysis( FA) in R. The idea started when I started converting the examples in the book "Exploratory Data Analysis with MATLAB" by Martinez and Martinez. All the examples in that book are written in Matlab. The examples are very good, as well as the theoretical basis, so I decided as I learn EDA in R, use the base of that book for deepen the statistical analysis understanding.

The examples in the book are written in Matlab but I will be using Octave since is open source and readily available. The datasets are .MAT files but are easily convertible to be read by R using the corresponding package.

# Content
In the first notebook we do Exploratory Data Analysis with the library `psych`.

In the second notebook we do Least Square Factor Analysis (LSB) with the `psyhc` library.

In the third notebook we do Factor Analysis using one of the examples in the M&M EDA book. We use the `factanal` R function. The dataset `stockreturns.mat` belongs to the Matlab Statistics Toolbox.

In the fourth notebook we use the library `Hmisc` and R functions from Dr. Steiger to learns more about `factanal`



# Challenges

These are the challenges:

* Some of the functions in Matlab/Octave are not available in R but function can be created. That takes time but contributes to enhance the larning in R.
* Plotting is a little bit different but still doable using the R libraries.
* A big challenge is using the examples that make use of the Matlab Statistical Toolbox. These scripts are very long and may take a long time converting them to R. In this case, it is better to learn what the input is, how the output looks and replicate the intermediate statistical processing using the libraries in R. It doesn't have any sense trying to convert literally what Matlab toolbox does.