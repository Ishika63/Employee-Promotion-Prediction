# Employee-Promotion-Prediction

**Predict whether the Employee of an Organization should get Promotion or Not?**

Your client is a large MNC and they have 15 broad verticals across the organisation. One of the problem your client is facing is around identifying the right people for promotion (only for manager position and below) and prepare them in time. Currently the process, they are following is: 
- They first identify a set of employees based on recommendations/ past performance.
- Selected employees go through the separate training and evaluation program for each vertical. These programs are based on he required skill of each vertical.
- At the end of the program, based on various factors such as training performance, an employee gets the promotion.


### Data Description:

| Variable              | Definition                                                     |
|-----------------------|----------------------------------------------------------------|
| employee_id           | Unique ID for employee                                         |
| department            | Department of employee                                         |
| region                | Region of employment (unordered)                               |
| education             | Education Level                                                |
| gender                | Gender of Employee                                             |
| recruitment_channel   | Channel of recruitment for employee                            |
| no_of_trainings       | Number of other trainings completed in the previous year on soft skills, technical skills, etc. |
| age                   | Age of Employee                                                |
| previous_year_rating  | Employee Rating for the previous year                           |
| length_of_service     | Length of service in years                                     |
| KPIs_met >80%         | If Percent of KPIs (Key Performance Indicators) >80% then 1 else 0 |
| awards_won?           | If awards won during the previous year then 1 else 0           |
| avg_training_score    | Average score in current training evaluations                  |
| is_promoted (Target)  | Recommended for promotion                                      |


