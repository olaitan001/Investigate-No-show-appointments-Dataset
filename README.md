# __Project: Investigate a Dataset (NoshowAppointment Dataset)__
## __Introduction to the Dataset__ 

This dataset contains medical appointment details for 110,527 Brazilians. The focus of the data is to determine if patients who booked appointment dates showed up for their appointments. There are 14 associated variables (characteristics) in the dataset. These will be explained in much more detail below.

## __Research Questions__

Our EDA would be based on the following questions:
1. What is the ratio of people present or absent for the appointment?
2. What gender booked more medical appointments?
3. Among those scheduled for appointments, what is the most common disease?
4. Which age is most affected by the diseases?
5. What gender is most affected by the diseases?


Note: The diseases are hypertension, diabetes, alcoholism, and handicap.

## Conclusions

The data of medical appointments of patients that attended or did not attend were analyzed to answer several questions.

Our data exploration resulted in an understanding of all the data's features, and we then proceeded to wrangle and clean up the data according to our proposed use.

1. According to the first research question, out of 110527 patients who scheduled appointments, 88208 were present, which amounts to approximately 79.8%, and 22319 were absent, which amounts to 20.2%. As a result, the majority of those who booked appointments were present on the appointment day.
2. As a second step, we investigated the gender with the most medical appointments. Our visualization indicates that more female patients schedule medical appointments, amounting to approximately 65%, than their male counterparts, amounting to approximately 35%.
3. Furthermore, we investigated the most common disease among those scheduled for appointments. Based on the analysis and visualization of our dataset. With an approximate ratio of 61.30%, hypertension constitutes the most common disease among those who set up appointments.
4. Moreover, we examined the age group most affected by the disease. Using our analysis and visualization, we discovered hypertension in patients aged 50 to 70, diabetes in patients aged 60 to 70, alcoholism in patients 40 to 60, and handicaps in patients 40 to 80 are all prevalent. Generally, between the ages of 50 and 60, people are more likely to suffer from these diseases. 
5. Lastly, we examined the gender most affected by the diseases. Our examination and visualization of the dataset show that approximately 56% of females and 44% of males suffer from hypertension. Thus, it implies a higher proportion of female patients with hypertension than male patients

## Limitations

Although the data set allowed us to answer five questions, we still encountered challenges and limitations.

A primary limitation of our analysis was insufficient numerical data amongst the column features to enable us to run more numerical analyses. Initially, this was a problem we encountered. However, we were able to wrangle the data set in such a way as to answer our research questions.

Additionally, the dataset contained many errors, making the data cleaning process take much more time than exploratory data analysis.

In addition, certain assumptions had to be formulated to proceed with our analysis since I observed that many patients were aged zero. It is not apparent from the data why a patient would have an age of 0. In this study, zero-age patients constituted a large portion of the total number of patients - 3539. I assumed they were babies under six months old to proceed with our analysis.

In this study, all statistics are descriptive, not inferential, which means that we did not use our data to create hypotheses or control experiences.
