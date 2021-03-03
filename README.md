### InvestigateMedicalData_NoShowAppointments

#### What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?

In this project I have analyzing the data associated with 100k medical appointments in Brazil to see if whether people show up for their appoitnments or not is associated with any other factors coded in the data. In particular I was interested in finding trends among the patients who do not show up for their appointment and how they are different from the patients who show up for their appointments. 

This project uses a **jupyter notebook** and Python libraries **NumPy**, **pandas**, and **Matplotlib**.

Contents are:
1. The jupter notebook involving the codes and project walkthrough in both ipynb and html formats: **Erdemir_Project2_InvestigateADataSet_Final_122820** 
2. Data set: **noshowappointments-kagglev2-may-2016.csv**. Original source can be found on Kaggle: https://www.kaggle.com/joniarroba/noshowappointments. This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.
    * ‘ScheduledDay’ tells us on what day the patient set up their appointment.
    * ‘Neighborhood’ indicates the location of the hospital.
    * ‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família
    *  About the encoding of the last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.
