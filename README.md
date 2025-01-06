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
| **Feature**                    | **Definition**                                                                                                     |
|---------------------------------|----------------------------------------------------------------------------------------------------------------------|
| **months_as_customer**          | Number of months the customer has been with the insurance company.                                                  |
| **age**                          | Age of the insured person, used for risk assessment.                                                                |
| **policy_number**               | Unique identifier for the insurance policy.                                                                         |
| **policy_bind_date**            | Date when the policy was activated.                                                                                  |
| **policy_state**                | State or region where the policy was issued.                                                                         |
| **policy_csl**                  | Maximum combined coverage for bodily injury and property damage.                                                    |
| **policy_deductable**           | Amount the policyholder pays out-of-pocket before insurance covers the claim.                                        |
| **policy_annual_premium**       | Annual cost of the insurance policy.                                                                                |
| **umbrella_limit**              | Limit of additional liability coverage beyond standard policies.                                                   |
| **insured_zip**                 | ZIP code of the insured person's address.                                                                           |
| **insured_sex**                 | Gender of the insured person.                                                                                       |
| **insured_education_level**     | Highest level of education completed by the insured person.                                                         |
| **insured_occupation**          | Occupation of the insured person, used for risk assessment.                                                         |
| **insured_hobbies**             | Hobbies of the insured, which can affect risk.                                                                      |
| **insured_relationship**        | Relationship status of the insured.                                                                                 |
| **capital-gains**               | Profit from the sale of investments.                                                                                |
| **capital-loss**                | Loss from the sale of investments.                                                                                  |
| **incident_date**               | Date of the incident (e.g., accident).                                                                              |
| **incident_type**               | Type of incident (e.g., collision, theft).                                                                         |
| **collision_type**              | Type of collision in the accident.                                                                                  |
| **incident_severity**           | Severity of the incident (e.g., minor, severe).                                                                     |
| **authorities_contacted**       | Authorities contacted (e.g., police, fire department).                                                              |
| **incident_state**              | State or region where the incident occurred.                                                                        |
| **incident_city**               | City where the incident took place.                                                                                 |
| **incident_location**           | Specific location of the incident.                                                                                  |
| **incident_hour_of_the_day**    | Time of day the incident occurred.                                                                                  |
| **number_of_vehicles_involved** | Number of vehicles involved in the incident.                                                                        |
| **property_damage**             | Whether property damage occurred in the incident.                                                                   |
| **bodily_injuries**             | Whether there were bodily injuries in the incident.                                                                 |
| **witnesses**                   | Number of witnesses to the incident.                                                                                |
| **police_report_available**     | Whether a police report is available for the incident.                                                              |
| **total_claim_amount**          | Total monetary value of the claim.                                                                                  |
| **injury_claim**                | Portion of the claim related to injuries.                                                                           |
| **property_claim**              | Portion of the claim related to property damage.                                                                   |
| **vehicle_claim**               | Portion of the claim related to vehicle damage.                                                                    |
| **auto_make**                   | Make of the insured vehicle.                                                                                        |
| **auto_model**                  | Model of the insured vehicle.                                                                                       |
| **auto_year**                   | Manufacturing year of the insured vehicle.                                                                         |
| **fraud_reported**              | Whether fraud was reported in the claim.                                                                             |

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
