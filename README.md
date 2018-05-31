# Mediation-and-survival: Research archive

CONTENTS OF THIS FILE
--------------------- 
 *GENERAL INFORMATION
 *INTRODUCTION
 *SPECIAL REQUIREMENTS 
 *FOLDERS
 --------------------- 

GENERAL INFORMATION
*Project
Title: COMPARISON OF METHODS TO PERFORM MEDIATION ANALYSIS WITH TIME-TO-EVENT OUTCOMES
Date: May, 2018
*Author information
Name: Lizbeth Burgos Ochoa
Project affiliation: VU medical center, Department of Epidemiology and Biostatistics
Research master: Methodology and Statistics for the Behavioural, Biomedical and Social Sciences.
*Supervisors
Names: Judith Rijnhart, Martijn Heymans, Jos Twisk 
Affiliation: VU medical center, Department of Epidemiology and Biostatistics

INTRODUCTION
 “Comparison of methods to perform mediation analysis with time-to-event outcomes” is a research project that aims to compare the statistical performance of four methods to perform mediation analysis with time-to-event outcomes. This was done by means of Monte Carlo simulations and an illustration with an empirical dataset. The compared methods are: I) the classical mediation approach with Cox PH model (ab and c-c’ methods); II) the classical mediation approach with the AFT model (ab and c-c’ methods); III-IV) Lange et al. [23] potential outcomes approach for both, Cox and AFT models, respectively. 
In this document I guide the interested researcher through the files contained in the research archive. All the described documents are relevant for the replicability of this study. The final product of the project is a a scientific paper named after the project. The paper includes the background information, methods, results, illustration in an empirical dataset, discussion and conclusion. 

The files are organized in five folders which are listed below. A further description of the contents of each folder can be found in the next sections.
	-R code
	-Raw results
	-Additional Files
	-Data Management Plan 
	-Figures 

SPECIAL REQUIREMENTS
In order to be able to run the code for the simulations it is necessary to have installed the following programs: 
	
- R: a free software environment for statistical computing and graphics. To download please follow the instructions in the following link: https://www.r-project.org/ 

- RStudio: an integrated development environment (IDE) for R. It includes a console, syntax-highlighting editor that supports direct code execution, as well as tools for plotting, history, debugging and workspace management. Download instructions in: https://www.rstudio.com/products/rstudio/download/ 

Furthermore, it is essential to install several R packages. Further instructions and list of necessary packages can be found in the R code files. 

FOLDERS 
1. R code
	This folder contains the code to perform the Monte Carlo simulations and the illustration with the empirical dataset. It is 		divided in three subfolders: 		
	- Classical Mediation Approach, Potential Outcomes, Empirical Illustration.  All the documents in this folder are R Notebook 		files, which are opened with R Studio. Each file has all the code required to generate (or load) the datasets, do the estimation 	 procedure and produce the final results (tables and plots). Specific instructions for running the code can be found inside each 	file. 
	-The Classical Mediation Approach folder contains four R Notebook files to  perform the simulations for the two methods based on 	 the classical mediation approach. To avoid mixing results, each file corresponds to an exposure-mediator-type combination (i.e. 	normal exposure-normal mediator, normal exposure-binary mediator…etc.). 
	- The Potential Outcomes  folder contains four R Notebook files to  perform the simulations for the two methods based on the 		Potential Outcomes mediation approach. As before, each file corresponds to an exposure-mediator-type combination (i.e. normal 		exposure-normal mediator, normal exposure-binary mediator…etc.). 
	- The empirical illustration folder contains instructions to analyze the empirical dataset with the four methods compared in the 	simulation study. Unfortunately, as the variables used are part of the Netherlands Anxiety and Depression Study (NESDA)  dataset, 	 we cannot provide access to the used dataset. Further explanation on this matter can be found in the Data Analysis Plan. However, 	  given that the provided code was designed to be generic, we encourage researchers to use and adapt the code to fulfill their own 	  means. The R code file contains instruction to reproduce results found in Table 3 from the paper.  
	All the analyses and simulations were conducted using R software version 3.4.3. 
2. Raw results
	This folder contains two subfolders, Classical Mediation Approach and Potential Outcomes. Each subfolder contains four  Excel 		files (.xlsx) with the raw results derived from the simulations performed in the R Notebooks ( four from the classical approach, 	four from the potential outcomes approach). The structure of the Raw results folder is similar to the R code folder. 
3. Additional Files
	This folder contains a pdf file with the 16 full results tables. In the paper, this file is referred as Additional File 1. 
4. Data Management Plan
	This folder contains a single  PDF document corresponding to the Data Management Plan (DMP). The DMP is a formal document that 		outlines how the data were handled during the research project, and how it will be handled after the project is completed. 		Topics regarding responsibility for the data management and storage, privacy and ethical issues, are addressed in this document. 	An schedule of the project can be found in the DMP, specifically in the Data Analysis Plan for NESDA, at the end of the DMP 		document.  
5. Additional Figures
	Two PDF files containing additional figures: Single mediator model and Scheme of compared methods. 
