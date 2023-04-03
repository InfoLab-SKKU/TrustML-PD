# Detection of Parkinson's Disease Progression with Consideration for Fairness.
* PD hinders healthy living. Gender impacts Parkinson's patients' health. Symptoms, onset, and therapy differ. Women with PD exhibited better cognitive, emotional, and non-motor symptoms. Males predicted mental health-related quality of life better than women, while women predicted physical and emotional components. We examine the Parkinson's Progression Markers Initiative (PPMI) dataset for gender, age, and racial biases to address this understudied topic.

* Machine learning algorithms must be checked for biases due to demographic disparities in PD diagnosis and therapy. Probabilistic data transformation maximizes pre-processing fairness. We train ML models without and with fairness mitigation to study bias, unfair model training, and fairness-accuracy trade-offs. Two machine learning classifiers—Decision Tree (DT) and Random Forest—were compared (RF). DT model findings are 82.03% racial bias, 80.05% age bias, and 85.03% accuracy (gender bias). RF model accuracy is 85% (racial bias), 80% (age bias), and 83% (gender bias) (gender bias). 

* Racism and age discrimination reduced after bias abatement. First, address gender prejudice. Bias reduction hurts both models. Both classifiers have higher gender FNRs. Our findings are crucial for medical artificial intelligence academics, physicians, and policymakers since both classifiers work effectively and yield the largest FNR disparity. Understanding digital healthcare systems' biases prevents disparities.

## Dependencies
Please first install the following dependencies
* Python3 (we use 3.8.3)
* numpy
* aif360
* tqdm
* sklearn


## Data Preparation
The PPMI data was originally collected from people across the world with and without PD. The dataset consists of 1083 non-time series patient records, of which 648 have the disease. The first stage of ML is data exploration, which comprises importing files, formatting, defining data types, and performing descriptive statistics.

## Proposed Architecture

## normal hand  
![Arch](Fig\framework.pdf)

## Results

## Acknowledgements
* IBM Fairness 360 is an open source toolkit for detecting and mitigating bias in machine learning models. The toolkit provides a comprehensive set of metrics for measuring bias in datasets and models, as well as a variety of algorithms for mitigating bias. https://github.com/Trusted-AI/AIF360
## Cite paper

```text
it will be updated soon
```