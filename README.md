# A/B Testing: Landing Page Optimization

## Project Overview
This project analyzes an A/B test for an online learning platform to determine if a new landing page design significantly increases user registrations. 

## Problem & Hypothesis
* **Problem:** An online learning platform wants to know whether a new landing page encourages more users to register.
* **Hypothesis:** Improving the online learning website with a new landing page will increase the registration rate. 

## Experiment Design
* **Control Group:** Users exposed to the old landing page version.
* **Treatment Group:** Users exposed to the new landing page version. 
* **Primary Metric (OEC):** Registration Rate.
* **Guardrail Metric:** Page Load Time.
* **Assignment:** Random assignment via user session ID.
* **MDE:** 2% 

## Workflow
Problem → Hypothesis → Treatment/Control → OEC & Guardrail → Analysis → Decision

## Results
* **Control Conversion Rate:** 12.04%
* **Treatment Conversion Rate:** 11.88%
* **Absolute Lift:** -0.16% | **Relative Lift:** -1.31%
* **P-Value:** 0.9050
* **Confidence Interval:** [11.72%, 12.05%]

## Decision
**Hold**: The results were not statistically significant with a p-value of 0.9050. Furthermore, the absolute lift did not exceed our practical threshold of 2%.

## Tools Used
* Dataset: https://www.kaggle.com/datasets/aadbutt/ab-testing
* SDAIA Academy GitHub Repository link: https://github.com/SDAIAAcademy


## Contributors
* Alzaynah Almazroa: https://github.com/zainamazroua-cell
* Fatima Ibrahim Hazazi: https://github.com/fatimahazazi-stack
* Fatemah Tawfiq Alelawi: https://github.com/fatemah-taw
