# No-show-appointment-project

## Objective
The number of patients' missed appointments in Brazilian health centers is not negligible. This project is intended to analyze a dataset of +100K medical appointments scheduled in Brazilian health structures in order to discover trends that can help us explain the possible reasons why so many patients used to miss their medical appointments.

## Files description
Here is the description of projects main files.
- ‘noshowappointments-kagglev2-may-2016.csv’: the dataset used for the analysis.
- ‘Project-investigate-a-dataset.ipynb’: a jupyter notebook, contains all the necessary code to be executed.
- ‘Project-investigate-a-dataset.html’: a sample report.

## About the dataset

This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

- ‘ScheduledDay’ tells us on what day the patient set up their appointment.
- ‘Neighborhood’ indicates the location of the hospital.
- ‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
- Be careful about the encoding of the last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

## Guidelines to use the script:
### Requirments
- anaconda distribution
### usage
- download the project.
- run conda and go to the project directory
- run the following command
```
$ jupyter notebook
```
