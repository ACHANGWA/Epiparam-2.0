
EpiParam, a web-based Shiny application that provides an interactive platform for estimating and visualizing core epidemiological parameters using community-level outbreak data.

# Installation
This application is available as a shiny application downloadable at https://github.com/ACHANGWA/Epiparam.
R was chosen as the computing platform because it is free, open source, and runs on any modern operating system so the application can be broadly available as possible.

To install and run the shiny app locally on your computer you will need to first install R, it is also suggested that you install Rstudio. For detailed instructions for installing the R and R studio, visit the respective links https://cran.r-project.org/bin/windows/base/ and   https://posit.co/download/rstudio-desktop

# Instructions 
Dowload the Epiparam folder with all the files to your local computer. Please note that all data files must be placed in one folder for the application to run.
After downloading the source code from this repository, to launch the application click on the file called EpiParam.Rmd and this will open an Rstudio window. click on 'Run Document' to open the ui.R and depending on your computer this may take some time.

# Screenshots
Here are example screenshots of the application before analysis.

<img width="1917" height="977" alt="image (10)" src="https://github.com/user-attachments/assets/d0af4b24-4c95-4f6e-a69f-6b36e8864df9" />


The application has 5 modules (windows). 
# 1. Incubation Period
This window estimates the incubation period using MLE parametric models including the lognormal, weibull and gamma models.

<img width="1915" height="978" alt="image (11)" src="https://github.com/user-attachments/assets/9600e1de-1b5d-4ff5-8750-75be7241437c" />

# 2. Incubation Period (Bayesian)
This window estimates the incubation period using parametric Bayesian models. 

<img width="1911" height="981" alt="image (12)" src="https://github.com/user-attachments/assets/768cb01e-29bb-484f-b015-182a6ba2c9e4" />

# 3. Serial interval 
This window estimates the incubation period using MLE parametric models including the lognormal, weibull, gamma and normal models.

<img width="1906" height="979" alt="image (13)" src="https://github.com/user-attachments/assets/75f479e9-018e-4914-8890-645d36515748" />

# 4. Serial interval (Bayesian)
This window estimates the serial interval using parametric Bayesian models. 
<img width="1904" height="961" alt="image (14)" src="https://github.com/user-attachments/assets/4e30b30f-e548-418b-b3ec-906e6cb066c2" />

# k and R0
Estimates the R0 and K values using generation of transmission pairs.
<img width="1908" height="993" alt="image (15)" src="https://github.com/user-attachments/assets/58333d18-ff2d-4b21-8c42-a3359537d783" />


