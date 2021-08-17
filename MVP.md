I have included my detailed project idea/scoping, since it has changed significantly since the proposal

# Can Modern Health better identify patient needs using their data?

## Problem/Opportunity: 
The health industry is always looking to better diagnose and monitor patient needs. As a rapidly growing sector, telehealth has even more to gain from accurately identifying patient needs before they meet with the doctor. When this doesn’t happen, the company is exposed to three problems:
- The patient receives poor support
- The service network has to adapt to fit that patient’s actual need, reducing efficiency
- Modern Health needs to shift expectations with business partners

## Current/Potential Challenges:
- Modern Health patient habits/demographics differ significantly from census data.
- Factors outside available metrics determine patient needs
- System does not account for differences between therapists
- Evaluation data is currently inaccessible

## Impact: 
- Better service to each patient by providing more tailored support
- More efficient allocation of therapeutic services
- More accurate customer success metrics

## Hypothesis: 
We want to better classify patient needs. We hypothesize that we can improve prediction using patient demographic and habit data. A more efficient prediction system is better for the patient, their company, and the Modern Health network.


## Problem Type: 
Classification (Identification) into one of three categories
- Low Support - Patients engage in digital materials/tools, rarely require additional sessions
- Significant Support - Patients engage in therapeutic services for their own comfort
- Clinical Support - Patients require clinical support for a mental health disability

## Data:
Missing But Needed:
- Customer opening survey data
- Customer therapy reflections
Available and Useful:
- CDC health survey
- CDC telehealth data

The project will inform patient need identification using a linear regression model. 
Model will produce predictions which will be compared with actual patient outcomes. 
Historical Modern Health data can be used to train and evaluate the model retroactively. 
Success metrics will depend on current Modern Health outcomes, which are proprietary.


## MVP:
After extensive data analysis in Google Sheets and Tableau, demographics appear to have very little sway on predicting the mental health of a patient. However, there are several easily accesible factors that have a relationships to the number of depressive episodes a patient has, detailed in the dashboard below. Additionally, filtering for specific demographics highlights hidden relationships that would be beneficial for future feature engineering.

Please view the dashboard below for more information.
https://public.tableau.com/views/MVP_Dashboard/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link
