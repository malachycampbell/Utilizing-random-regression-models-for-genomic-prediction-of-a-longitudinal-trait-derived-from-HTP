<h1 align="center">
  <img alt=" Utilizing random regression models for genomic prediction of a longitudinal trait derived from high-throughput phenotyping platforms" />
</h1>

[Malachy Campbell](https://malachycampbell.github.io/), [Harkamal Walia](http://cropstressgenomics.org/), [Gota Morota](http://morotalab.org/)

## Abstract
The accessibility of high-throughput phenotyping platforms in both the greenhouse and field, as well as the relatively low cost of unmanned aerial vehicles, have provided researchers with an effective means to characterize large populations throughout the growing season. These longitudinal phenotypes can provide important insight into plant development and responses to the environment. Despite the growing use of these new phenotyping approaches in plant breeding, the use of genomic prediction models for longitudinal phenotypes is limited in major crop species. The objective of this study is to demonstrate the utility of random regression (RR) models using Legendre polynomials for genomic prediction of shoot growth trajectories in rice (*Oryza sativa*). An estimate of shoot biomass, projected shoot area (PSA), was recored over a period of 20 days for a panel of 357 diverse rice accessions using an image-based greenhouse phenotyping platform. A RR that included a fixed second-order Legendre polynomial, a random second-order Legendre polynomial for the additive genetic effect, a first-order Legendre polynomial for the environmental effect, and heterogeneous residual variances was used to model PSA trajectories. The utility of the RR model over a single time point (TP) approach, where PSA is fit at each time point independently, is shown through four prediction scenarios. In the first scenario, the RR and TP approaches were used to predict PSA for a set of lines lacking phenotypic data. The RR approach showed a 11.6% increase in prediction accuracy over the TP approach. Much of this improvement could be attributed to the greater additive genetic variance captured by the RR approach. The remaining scenarios focused forecasting future phenotypes using a subset of early time points for known lines with phenotypic data, as well new lines lacking phenotypic data. In all cases, PSA could be predicted with high accuracy (*r*: 0.79 to 0.89 and 0.55 to 0.58 for known and unknown lines, respectively). This study provides the first application of RR models for genomic prediction of a longitudinal trait in rice, and demonstrates that RR models can be effectively used to improve the accuracy of genomic prediction for complex traits compared to a TP approach.

This repo contains all the code and data used for the manuscript: "Utilizing random regression models for genomic prediction of a longitudinal trait derived from high-throughput phenotyping". Check out the preprint [here](https://www.biorxiv.org/content/early/2018/05/11/319897). The contents are layed out according to the order presented in the paper.

## Table of Contents

* **1. Preparation of Phenotypic data**
  - [html output](https://rawgit.com/malachycampbell/Utilizing-random-regression-models-for-genomic-prediction-of-a-longitudinal-trait-derived-from-HTP/master/Rmarkdownfiles/1.Phenoprep.html)
* **2. Preparing the 44k SNP data**
   - [html output](https://rawgit.com/malachycampbell/Utilizing-random-regression-models-for-genomic-prediction-of-a-longitudinal-trait-derived-from-HTP/master/Rmarkdownfiles/2.Genoprep.html)
* **3. Selection of Random Regression model**
   - [html output](https://rawgit.com/malachycampbell/Utilizing-random-regression-models-for-genomic-prediction-of-a-longitudinal-trait-derived-from-HTP/master/Rmarkdownfiles/Rmarkdownfiles/3.RRmodelselection.html)
* **4. Estimating heritability and genetic correlation of shoot growth**
   - [html output](https://rawgit.com/malachycampbell/Utilizing-random-regression-models-for-genomic-prediction-of-a-longitudinal-trait-derived-from-HTP/master/Rmarkdownfiles/4.Heritability.html)
* **5. Scenario A: Genomic Prediction Using Random Regression and Single Time Point gBLUP**
   - [html output](https://rawgit.com/malachycampbell/Utilizing-random-regression-models-for-genomic-prediction-of-a-longitudinal-trait-derived-from-HTP/master/Rmarkdownfiles/Rmarkdownfiles/5.ScenarioA.html)
* **6. Scenario B and C: Forecasting Future Phenotypes with Random Regression Models**
   - [html output]
