# Customizing Telehealth Patient Care to Increase Efficiency and Effectiveness
 

## Abstract:

The health industry is always looking to better diagnose and monitor patient needs. As a rapidly growing sector, telehealth has even more to gain from accurately identifying patient needs before they meet with the doctor. When this doesn’t happen, the company is exposed to three problems:
- The patient receives poor support
- The service network has to adapt to fit that patient’s actual need, reducing efficiency
- The company needs to shift expectations with business partners
For Modern Health, a hypergrowth company emerging into this market, this is a special concern. Every inefficiency or inaccuracy could grow exponentially.  As a result, it is important to ask the question: Can Modern Health better identify patient needs using their data? This project looks to answer that question.

## Design

The problem is designed with the following scoping in mind:

Current/Potential Challenges:
- Modern Health patient habits/demographics differ significantly from census data.
- Factors outside available metrics determine patient needs
- System does not account for differences in patient success between therapists
- Evaluation data is currently inaccessible

Impact: The above problems problems are reduced/eliminated
- Better service to each patient by providing more tailored support
- More efficient allocation of therapeutic services
- More accurate customer success metrics

Hypothesis: We want to better classify patient needs. We hypothesize that we can improve prediction using patient demographic and habit data. A more efficient prediction system is better for the patient, their company, and the Modern Health network.

Metric of Success: Reducing patient care level change, the difference between a patient’s prescribed level of care and their ultimate care need.

Data

Missing But Needed:
- Customer opening survey data
- Customer therapy reflections
Available and Useful:
- CDC NHANES
  - Key Metrics:
    - Race
    - Gender
    - Age
    - Depression Rate
    - Smoking Rate
    - Sleep Rate
    - Poverty Line
    - Chest Pain
  - 5,400 surveys
  - Representative of US
    - Oversamples for black, hispanic and asian populations
- CDC Telehealth Data
  - Explores different demographics approach to telehealth

Algorithms

Cleaning was completed in Google Sheets. 18 different sources were used for analysis. Vlookup functions were used to recategorize and combine the different sources. Other filtering was done to account for different data types and missing values. EDA was performed using pivot tables and the graphing functions.

Further visual EDA and dashboard creation were completed in Tableau. While 10 final graphs were ultimately used to convey the information, many more were created to explore different relationships between the variables.

Further analysis will be required using linear regression algorithms and proprietary Modern Health Data.

Tools:

- Pandas
- Google Sheets
- Tableau

Visualizations

![% Adults Who Had a Telehealth Appointment vs Age](https://user-images.githubusercontent.com/67508938/130243820-a576c014-0320-4307-86cf-a832198764c7.png)

![% Adults Who Had a Telehealth Appointment vs  Their State's Political Leaning](https://user-images.githubusercontent.com/67508938/130243821-d1735de9-e1c5-4545-a392-239f2314b8b7.png)

<img width="1131" alt="Screen Shot 2021-08-19 at 9 53 31 PM" src="https://user-images.githubusercontent.com/67508938/130243895-16f48233-b9ba-4460-9891-895dbcafc53a.png">
<img width="1132" alt="Screen Shot 2021-08-19 at 9 53 45 PM" src="https://user-images.githubusercontent.com/67508938/130243900-04fbbbdb-9e0a-4915-9f78-d9764dc03ea2.png">
