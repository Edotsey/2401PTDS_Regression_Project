# Insurance claims project


## Table of contents
* [1. Project Overview](#project-description)
* [2. Dataset](#dataset)
* [3. Repository Structure](#Repository-Structure)
* [4. Environment](#environment)

## 1. Project Overview <a class="anchor" id="project-description"></a>
In the insurance industry, precise prediction of claim probabilities is vital for effective risk assessment and accurate policy pricing. However, a significant challenge arises from the frequent class imbalance in insurance claims datasets, where non-claim instances vastly outnumber actual claims. This imbalance complicates predictive modeling, leading to biased outcomes that favor the majority class and diminish the performance of models on the minority class. Addressing this issue is crucial for improving the accuracy and reliability of claims predictions, which are essential for better risk management and policy development.

## 2. Dataset <a class="anchor" id="dataset"></a>
The dataset utilized in this project comprises historical data on insurance claims, encompassing a variety of information about the policyholders, their demographics, past claim history, and other pertinent features. The dataset is structured to facilitate predictive modeling tasks aimed at accurately identifying the likelihood of future insurance claims.

**Dataset Features:**
- policy_id	Unique identifier for the insurance policy.
- subscription_length	The duration for which the insurance policy is active.
- customer_age	Age of the insurance policyholder, which can influence the likelihood of claims.
- vehicle_age	Age of the vehicle insured, which may affect the probability of claims due to factors like wear and tear.
- model	The model of the vehicle, which could impact the claim frequency due to model-specific characteristics.
- fuel_type	Type of fuel the vehicle uses (e.g., Petrol, Diesel, CNG), which might influence the risk profile and claim likelihood.
- max_torque, max_power	Engine performance characteristics that could relate to the vehicle’s mechanical condition and claim risks.
- engine_type	The type of engine, which might have implications for maintenance and claim rates.
- displacement, cylinder	Specifications related to the engine size and construction, affecting the vehicle’s performance and potentially its claim history.
- region_code	The code representing the geographical region of the policyholder, as claim patterns can vary regionally.
- region_density	Population density of the policyholder’s region, which could correlate with accident and claim frequencies.
- airbags	The number of airbags in the vehicle, indicating safety level which can influence claim probability.
- is_esc (Electronic Stability Control), is_adjustable_steering, is_tpms (Tire Pressure Monitoring System)	Features that enhance vehicle safety and could potentially reduce the likelihood of claims.
- is_parking_sensors, is_parking_camera	Parking aids that might affect the probability of making a claim, especially in urban areas.
- rear_brakes_type	Type of rear brakes, which could be related to the vehicle’s stopping capability and safety.
- Various binary indicators (Yes/No) for specific vehicle amenities and safety features	Features like steering_type, turning_radius, length, width, gross_weight, etc., which together build a profile of the - vehicle’s characteristics and its associated risk factors.
- claim_status	Indicates whether a claim was made (1) or not (0), which is the dependent variable the model aims to predict.
 

## 3. Repository Structure <a class="anchor" id="packages"></a>

To carry out all the objectives for this repo, the following necessary dependencies were loaded:
+ `Pandas 2.2.2` and `Numpy 1.26`
+ `Matplotlib 3.8.4`
 

## 4. Environment <a class="anchor" id="environment"></a>

It's highly recommended to use a virtual environment for your projects, there are many ways to do this; we've outlined one such method below. Make sure to regularly update this section. This way, anyone who clones your repository will know exactly what steps to follow to prepare the necessary environment. The instructions provided here should enable a person to clone your repo and quickly get started.

