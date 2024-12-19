# Insurance claims project


## Table of contents
* [1. Project Overview](#project-description)
* [2. Dataset](#dataset)
* [3. Repository Structure](#Repository-Structure)
* [4. Packages](#Packages)
* [5. Environment](#Environment)
  
## 1. Project Overview <a class="anchor" id="project-description"></a>
In the insurance industry, precise prediction of claim probabilities is vital for effective risk assessment and accurate policy pricing. However, a significant challenge arises from the frequent class imbalance in insurance claims datasets, where non-claim instances vastly outnumber actual claims. This imbalance complicates predictive modeling, leading to biased outcomes that favor the majority class and diminish the performance of models on the minority class. Addressing this issue is crucial for improving the accuracy and reliability of claims predictions, which are essential for better risk management and policy development.

## 2. Dataset <a class="anchor" id="dataset"></a>
The dataset utilized in this project comprises historical data on insurance claims, encompassing a variety of information about the policyholders, their demographics, past claim history, and other pertinent features. The dataset is structured to facilitate predictive modeling tasks aimed at accurately identifying the likelihood of future insurance claims. The data utilized in this exercise was obtained from Kaggle, under the dataset titled "Insurance Claim Analysis (Demographic and Health)". Access the dataset [here](https://www.kaggle.com/datasets/thedevastator/insurance-claim-analysis-demographic-and-health/data).

**Dataset Features:**
| **Feature**                    | **Definition**                                                                                                                                                          |
|---------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **months_as_customer**          | The number of months a customer has been with the insurance company, indicating customer loyalty and duration of coverage.                                                |
| **age**                          | The age of the insured person, a critical factor in risk assessment for calculating premiums.                                                                          |
| **policy_number**               | A unique identifier for each insurance policy, used to track and reference the specific insurance contract.                                                             |
| **policy_bind_date**            | The date when the insurance policy was activated or "bound."                                                                                                            |
| **policy_state**                | The state or region where the insurance policy was issued, which can influence premiums due to local regulations and risk factors.                                        |
| **policy_csl**                  | The maximum combined coverage for bodily injury and property damage in a single accident, expressed as a single limit rather than separate limits.                       |
| **policy_deductable**           | The amount the policyholder must pay out-of-pocket before the insurance covers the rest of the claim.                                                                  |
| **policy_annual_premium**       | The total amount paid by the insured annually for the insurance policy.                                                                                               |
| **umbrella_limit**              | The limit of an umbrella policy, which provides additional liability coverage beyond standard auto or home insurance.                                                   |
| **insured_zip**                 | The ZIP code of the insured person's address, which can influence premiums based on geographic location.                                                                |
| **insured_sex**                 | The gender of the insured person, which can sometimes influence risk and premium pricing.                                                                               |
| **insured_education_level**     | The highest level of education completed by the insured person, which can be used to assess risk and potential for claims.                                               |
| **insured_occupation**          | The occupation of the insured person, influencing risk assessment based on job-related factors.                                                                       |
| **insured_hobbies**             | The hobbies or activities of the insured person, which can impact risk, particularly if they involve higher-risk activities.                                              |
| **insured_relationship**        | The relationship status of the insured person, which could affect risk and premiums.                                                                                   |
| **capital-gains**               | The profit made from the sale of assets or investments, providing insight into the insured person’s financial standing.                                                  |
| **capital-loss**                | The loss incurred from the sale of assets or investments, which can reflect the financial status of the insured person.                                                 |
| **incident_date**               | The date the incident (such as an accident) occurred, helping to categorize and assess risk based on timing.                                                           |
| **incident_type**               | The type of incident (e.g., collision, theft, vandalism), used to categorize the nature of the claim.                                                                  |
| **collision_type**              | The type of collision that occurred in an accident, such as rear-end or side-impact.                                                                                   |
| **incident_severity**           | The severity of the incident, typically categorized as minor, moderate, or severe, determining the potential cost of 


## 3. Repository Structure <a class="anchor" id="packages"></a>

- `Insurance claims data.csv:` Contains the dataset file.
- `QCTO---Workplace-Module ipynb` Jupyter notebooks used for data exploration, model training, and analysis.
- `images/:` Images used in the notebook.
- `README.md:` Project documentation.
- `requirements.txt:` Files for recreating the project's environment.
- `shapefiles/:` Shapefiles that are part of the Natural Earth dataset, used in the project to perform spatial operations for the countries and areas in the dataset.

## 4. Packages <a class="anchor" id="packages"></a>

To carry out all the objectives for this repo, the following necessary dependencies were loaded:
+ `Pandas 2.2.2` and `Numpy 1.26`
+ `Matplotlib 3.8.4`
+ `Seaborn 0.13.2`
+ `Scikit-learn 1.5.1`
+ `GeoPandas 1.0.1`
+ `Power BI`

## 5. Environment <a class="anchor" id="environment"></a>

```bash
# activate the virtual environment
conda activate <QCTO---Workplace-Module>
# install the pip package
conda install pip
# install the requirements for this project
pip install -r requirements.txt
```
