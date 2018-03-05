# Machine Learning Engineer Nanodegree
## Capstone Proposal
Joe Udacity  
December 31st, 2050

## Proposal
_(approx. 2-3 pages)_

### Domain Background
_(approx. 1-2 paragraphs)_

I will study the problem of soil properrty analysis using ifrared spectra measured via satellite. This problem is from the domain of physical science, specifically the application of spectroscopy and radiometry to geophysics and meteorology. Spectroscopy in the broadest sense is the extension of imaging and optics to frequencies of electromagnetic radiation outside of the visible portion (infrared and lower, ultraviolet and higher). 

Spectroscopy occupies a central position in all modern fields of science: In the lab, it is a powerful means of deducing the composition of a mterial or object from the spectrum of light absorbed or reflected- its spectral 'signature'; theoretically, the prediction of the spectrum of a substance from its fundamental atomic and chemical structure is a major achievement of quantum mechanics. Spectroscopy also finds wide application in atmospheric and earth science, such as in the detection of particular gasses based on their unqiue spectral signatures, or in the differentiation of barren land or forest fires from that with green photosynthesizing life.


Often it is not possible to purifying and preparing a sample for measurement and obtaining a spectrum over a sufficiently broad range of the electromagnetic spectrum. For example, the production of X-rays for spectroscopy often requires a gymnasum-sized particle accelerator, and the spectra of solids usually requires obtaining perfectly pure crystals and compressing them into very thin transparent disks. A partiuclar issue is biological samples which may be a heterogenous mix of many components. Thus, while there is  satellite spectroemeters is excellent for weather and climate measurements, it is only recently that researcher have attempted to use the avialable data to probe further.

limited to such things as distinguishing ice and water from photosynthesizing plant life and of purit is not always possible to obtain the full spectra over a large range of frequencies, and it is not always possible to link the spectrum of a sample to its precise chemical composition. Geophysical or biological samples for exampspectra, for example, are often measured from satellite spectrometers where the range of frequencies is limited and the measured samples are heterogeneous mixtures of many different components. These problems are logistical rather than fundamental because they can be solved with better sample prepation (separation of components), better measuring tools (wider range spectrometers), or more intensive computation (calculating the spectrum of mixture rather than individual comonnents) but do not require new theories or methods. 

From a pure science perspective, they are 'uninteresting' because the fundamental science is already understood and the main focus is precisely on dealing with the real world logistical conditions. 
From the perspective of pure science these are logistic issues because they relate to the eparTION OF THE sample and the measurement of the spectrum but do not introduce any new fundamental problems. Thus rom the perspective of pure science, these a problem that scientific perspective, One such problem that encounters these issues is the analysis of soil properties from satellite spectral data. which faces  of detecting soil properties from limited spectra. The problem of analyzing soil properties  is one such problem that encounters which would need to be carefully separated before analyzing the spectrum. or is  nor is the complete spectrum over a wide range of frequencies always available. In this section, provide brief details on the background information of the domain from which the project is proposed. Historical information relevant to the project should be included. It should be clear how or why a problem in the domain can or should be solved. Related academic research should be appropriately cited in this section, including why that research is relevant. Additionally, a discussion of your personal motivation for investigating a particular problem in the domain is encouraged but not required.

### Problem Statement
_(approx. 1 paragraph)_

The goal of this study is to use mid infrared reflectance spectra and geological data-  average temperature, rainfal, and albedo)  measured by satellite to predict five features of soil composition- SOC, pH, Ca, P, S- at different location on Earthby using a machine learning model that trains from dataset with known soil features.  The solution should produce a model that, for each of the five features, reproduces the training data with the smallest relative square error and with <5% chance that the null hypothesis produces the same result by random chance.  problem can be reproduced and occurs more than once).

### Datasets and Inputs
_(approx. 2-3 paragraphs)_

In this section, the dataset(s) and/or input(s) being considered for the project should be thoroughly described, such as how they relate to the problem and why they should be used. Information such as how the dataset or input is (was) obtained, and the characteristics of the dataset or input, should be included with relevant references and citations as necessary It should be clear how the dataset(s) or input(s) will be used in the project and whether their use is appropriate given the context of the problem.

### Solution Statement
_(approx. 1 paragraph)_

The solution will produce values for the five features. In this section, clearly describe a solution to the problem. The solution should be applicable to the project domain and appropriate for the dataset(s) or input(s) given. Additionally, describe the solution thoroughly such that it is clear that the solution is quantifiable (the solution can be expressed in mathematical or logical terms) , measurable (the solution can be measured by some metric and clearly observed), and replicable (the solution can be reproduced and occurs more than once).

### Benchmark Model
_(approximately 1-2 paragraphs)_

The safest benchmark to use here is be a validation data set that is solir off from the training data. Other datasets might not be appropriate for comparison with this model because spectral data are often measured on a relative scale and need to be calibrated between different devices, and additionally there might be unknown geogrpahical features that produce different data relationships
at different points on Eartth.  the data used here is an uncommon mix of spectral data and soil properties little intuition aobut the general trends in the data, and little knowledge whether the trends change with other geographical features.  connection between the measurements and soil properties geographical features. benchmark to use is a will be divided into a main set and a smaller validation used comes from a larger database of infrared spectra and soil properties across Africa. 

### Evaluation Metrics
_(approx. 1-2 paragraphs)_

In this section, propose at least one evaluation metric that can be used to quantify the performance of both the benchmark model and the solution model. The evaluation metric(s) you propose should be appropriate given the context of the data, the problem statement, and the intended solution. Describe how the evaluation metric(s) are derived and provide an example of their mathematical representations (if applicable). Complex evaluation metrics should be clearly defined and quantifiable (can be expressed in mathematical or logical terms).

### Project Design
_(approx. 1 page)_

In this final section, summarize a theoretical workflow for approaching a solution given the problem. Provide thorough discussion for what strategies you may consider employing, what analysis of the data might be required before being used, or which algorithms will be considered for your implementation. The workflow and discussion that you provide should align with the qualities of the previous sections. Additionally, you are encouraged to include small visualizations, pseudocode, or diagrams to aid in describing the project design, but it is not required. The discussion should clearly outline your intended workflow of the capstone project.

-----------

**Before submitting your proposal, ask yourself. . .**

- Does the proposal you have written follow a well-organized structure similar to that of the project template?
- Is each section (particularly **Solution Statement** and **Project Design**) written in a clear, concise and specific fashion? Are there any ambiguous terms or phrases that need clarification?
- Would the intended audience of your project be able to understand your proposal?
- Have you properly proofread your proposal to assure there are minimal grammatical and spelling mistakes?
- Are all the resources used for this project correctly cited and referenced?
