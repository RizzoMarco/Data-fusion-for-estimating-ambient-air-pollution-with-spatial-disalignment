# Data-fusion-for-estimating-ambient-air-pollution-with-spatial-disalignment
Polispatial
Hello World! 
This is the README of the  project of Bayesian Statistics Course (Academic Year 2022/2023).



*** WHO WE ARE ***************************************************************************************************************

  These are the members:
  G. Barbato
  M. Cosi
  M. Del Basso
  C. Esposito
  A. Frabetti        
  M. Rizzo        


*** HOW TO NAVIGATE THIS SEA OF DOCUMENTS *************************************************************************************

  The project was carried out using two programming languages: R and (little C++).
  This is the content of the documents we have attached:

  1) Simulated_Data.R             : Here you can find the R code of our complete model. More accuratively we create Simulated Data. 
                                    From the derived Full conditional we run the Gibbs Sampler and finally we make prediction using 
				    kriging method for unkonwn locations.
            
  2) Real_data Natural Sea.R      : We follow the same modus operandi of Simulated_Data, but in this case using real data.
. 

  3) Real_Data Flat Sea.R         : This code is speculate to the Real_data Natural Sea, but we change the covariate (population density) 
                                    taking into account the "sea problem".
		    
  4) Real_Data Intercept Model.R  : Here we run our code with simplified model (y = b0 +b0(s)) to overcome the absence of CMAQ data.
  
  5) Rcpp_Kernel.Cpp              : This function uses Rcpp and RcppArmadillo to compute the covariance matrix. 
                                    It optimizes the slow R for-loops and it compute efficiently the squared exponential covariance 
                                    function of every entry of the input matrices. 
  
  
  Also, last but not least the datasets to run the codes, placed in this folder: 

  6) DATASETS.zip


Buon viaggio!
