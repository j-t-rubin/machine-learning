# Machine Learning Engineer Nanodegree
## Capstone Proposal
Joe Udacity  
December 31st, 2050

## Proposal
_(approx. 2-3 pages)_

### Domain Background
_(approx. 1-2 paragraphs)_

I will study ground soil chemical composition by infrared reflectance spectra, weather records, and geographical feature.  This problem is from the domain of physical science, specifically the application of spectroscopy, meteorology, and geography to ecology and agriculture. 

Spectroscopy in the broadest sense is the extension of imaging and optics to frequencies of electromagnetic radiation outside of the visible portion (infrared and lower, ultraviolet and higher) and is used by scientists and engineers across many different fields. In the lab, it is a powerful means of deducing the composition of a mterial or object from the spectrum of light absorbed or reflected- its spectral 'signature', while theoretically the prediction of the spectrum of a substance from its fundamental atomic and chemical structure is a major achievement of quantum mechanics. 

In fact, infrared spectroscopy is so well understood from frundamental physics that one may wonder if a data science approach is valuable. Indeed, spectroscopy is already widely used in Earth sciences, for example in meteorilogical measurements (including those used in this study) that derive rain cover and ground vegetation from the respective spectral signatures of water and photosynthesizing green plants (temperature is measured by a related technique that detects infrared emission but does not use an initial radiation pulse.) 

As it turns out, the spectrum of a ground soil sample is difficult to understand with conventional spectroscopic theory. One problem is that spectroscopy is simplest for highly pure samples with only a single component, while ground soil is a mixture of many different chemical compounds and is inhomogeneous so that the composition changes at different depths below the ground. Spectroscopy can be performed on homogeneous mixtures, such as solutions with different dissolved components, but spectra are sensitive to colligative effects (those depending on the concentration of species) so that spectral signatures are no longer unique to particular substances. This can be a strength if one is interested in measuring colligative properties, but it is also a weakness because there must be some independent method like a chemical test to identify the compounds present. Obviously it is an intractible problem to identify all components of soil and their exact concentrations at all depths. The most that can be said is that colligative effects will give rise to some link between the concentrations of certain species and the spectrum of a sample, and that soil samples from different depths can not be expected to be equivalent.


### Problem Statement
_(approx. 1 paragraph)_

The goal of this study is to use mid infrared reflectance spectra and geological data-  average temperature, rainfal, and albedo)  measured by satellite to predict five features of soil composition- SOC, pH, Ca, P, S- at different location on Earthby using a machine learning model that trains from dataset with known soil features.  The solution should produce a model that, for each of the five features, reproduces the training data with the smallest relative square error and with <5% chance that the null hypothesis produces the same result by random chance.  problem can be reproduced and occurs more than once).

### Datasets and Inputs
_(approx. 2-3 paragraphs)_

The data includes in addition the diffuse reflectance infrared spectrum from ... to... for each sample. If the spectrum is thoguht of as a continuous function of the freuqncy, then the model is a functional (rather than a simple function) that takes in the spectral function and the vector of single valued features and produces some other signle valued vector outpout:


Since real data is discrete, the spectral function could also be thought of as a set of many single-valued features, one for each of the hundreds of freuqnecy measurements. I prefer to take the former view, because the hundreds of readings are probably not all necessary. Instead there will be some feature reduction procedure that corresponds to a pre-processing functional that takes in the spectral function and produces a vector output with a more manageable length that can be concatenated with the single valued feature vector.


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
