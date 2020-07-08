# Job-Application-Analysis
I.	Introduction
The original file: https://docs.google.com/spreadsheets/d/1eGPU-awXQFqB4__AC4lmCt4vjFy1rt3m-6zZ85_siGE/edit?usp=sharing
The cleaned file: https://docs.google.com/spreadsheets/d/1idtPjBjZ-qqJJrFvWDRVC_mH2V7Dx2sEPIeOhB9AYdo/edit?usp=sharing
Things were cleaned:
-	Arrange values into right columns
-	Rename the header of columns
II.	Part 1 - Talent Analysis
1.	Education
In this part, I would like to pay attention to find out how many students have completed or are pursuing bachelor degree, master degree and PhD programs.
•	For PhD degree, I would like to find the frequency of keywords “PhD”, “Ph.D” or “Doctorate”.
•	For Master degree, the frequency of keywords “Master”, “Masters”, “MS”, or “M.S” are counted.
•	For MBA degree, the frequency of keywords “MBA” are counted
•	For Bachelor degree, I would like to find the frequency of keywords “Bachelor”, “Bachelors”, “BS”, “BA”, “B.S” or “B.A.
2.	Job Title
Computer Scientist, Data Scientist, Software Engineer are those titles that the company would like to showcase. Job Title can be retrieved from different columns including “Your ideal job”, “Pick your Team” or major in “Education”. 
To answer the question that how many data scientists, software engineers and computer scientists Forkaia have, I would like to say:
-	Get the number of candidates picking Data Team for the number of Data Scientist (802 Data Scientists)
-	Get the number of candidates picking Development Teams for the number of Software Engineer (264 Software Engineers)
-	Get the number of candidates studying Computer Science (in “Education”) for the number of Computer Scientist (313 Computer Scientists)
Reasons for choosing this approach is:
-	Although the column Ideal Job has the closest meaning to the Job title, it is has least observation (just 1014 observation). A lot of values in this columns are not meaningful enough for counting number of job titles.
-	Title “computer scientist” can be only retrieved from major Computer Science.
-	Number of people picking the team Data and Development is the closest reflection of counting Data Scientists and Software Development because current or applied position is a better metrics to analyze than majors.
3.	Awards – Achievement
Hackathon are mention 15 times in 348 observations of Biggest Achievement. However, after checking manually the meaning of 15 results mentioned Hackathon, there are only 11 people said that they have participated, won finalist rounds or prizes of Hackathon.
Given the complexity of text “Analysis” Hackathon, the analyst decided not to go deeper in this parts regarding key word “Honor”or “Dean’s List”.
