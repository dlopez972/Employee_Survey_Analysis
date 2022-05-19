Employee Survey Analysis
=============================================================

Employee surveys are a very common practice among HR teams in organizations in order to gather information on employees perceptions of their thoughts, feelings, and behaviors. Typically employee surveys can consist of two type of questions, open ended questions which responses would be open text (e.g. Please describe your work life balance.) or close ended questions with a fixed response (e.g. on a scale of 1 to 5, how satisfied are you with your manager)

This sample employee survey consist of 10 closed ended questions with a 1 (strongly disagree) through 5 (strongly agree) scale, as well as a few attributes about the employees themselves.  The goal of this project is to better understand the survey data and examine results alongside the employee attributes to help explore sentiment around certain employee populations. To see if the responses themselves have internal consistency reliability along their respective theme using Cronbachs Alpha, this is a measure of the extent to which the group (theme) of questions are related. 
                            
                      Score thresholds for Cronbach's alpha 
                      
                            .95 - 1.00 = Excellent
                            .90 - .94 = Great
                            .80 - .89 = Good
                            .70 - .79 = Acceptable
                            .60 - .69 = Questionable
                            .00 - .59 = Unacceptable

Lastly we’d like to explore the data visually for our stakeholders in order to clearly showcase the results by question theme and employee attributes. 


Data Definitions/Description
=============================================================

EmployeeSurveyData:
The dataset consists of 18 variables (columns), 10 are our survey questions and 8 are employee attributes, and 199 observations (records). Each record represents an employees response which the following attributes: 

- Employee ID
- Unit 
- Age
- Tenure (Company)
- Management Level (1-9) 
  - 1 = Jr. Associate
  - 2 = Associate
  - 3 = Sr. Associate
  - 4 = Principal Associate
  - 5 = Manager
  - 6 = Sr. Manager
  - 7 = Director
  - 8 = Sr. Director
  - 9 = VP
- Performance
  - 1 = Needs Improvement
  - 2 = Below Expectations
  - 3 = Meeting Expectations
  - 4 = Exceeding Expectations
  - 5 = Excellent
- Gender
  - 0 = Male
  - 1 = Female
- Ethnicity
  - 0 = Black
  - 1 = Asian
  - 2 = White
  - 3 = Hispanic
  - 4 = Multi-Racial
  - 5 = Unknown
- Response
 - 1 = Strongly Disagree
 - 2 = Disagree
 - 3 = Neutral
 - 4 = Agree
 - 5 = Strongly Agree



Approach
=============================================================
Part 1: Import & Inspect data

Part 2: Clean & Transform data

Part 3: EDA

Part 4: Visulation
