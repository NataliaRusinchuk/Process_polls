# Process_surveys
Process results of surveys on education quality

The Project is aimed on processing the data of results of students' survey.
To ensure the quality of higher education the students should be regularly interviewed about overall impression of the study, about impression on separate subjects and teachers. 

The survey is organized using Google Forms, two types of forms for the surveys can be found via links:
1. Overall level of satisfaction with Educational Program
https://forms.gle/69RPWj3iSBye54xA6 - in Ukrainian
https://forms.gle/xG4nY2bWqJyDGmnw6 - in English

2. Level of satisfaction with subjects and teachers
https://forms.gle/W2AbVEE1KWBzY698A - in Ukrainian
https://forms.gle/8pj7w4ghEiYQq67a9 - in English

The survey results then are saved as *.xlsx files and processing. In the Project Python is used. As a result of the processing three different types of reports are creating in *.pdf format. For using proposed *.ipynb files you need to collect answers, save results as *.xlsx file, and then process them. 
Examples of used *.xlsx files and resulted *.pdf reports are added to the folder "Results".

Processing the results for Programs can be conducted without any additional preprocessing - you need just to put the input file name and the name of the program, which is the output file name. 
Results for Teachers and sibjects should be preprocessed: you need to save the results of all the survey in one file, and give the sheet names in the following format: "ShortenedProgramTitle Semester", e.g. "Chemistry HT 3". Also you need to add to *.ipynb file dictionary for converting shortened names in full program names, and the dictionary consisted names of departments and lists of teachers of these departments. These two dictionaries are needed to input the full program names in the report correctly, and also to create reports for teachers rates for each department. 

The processing also may be done autonatically without installation of Python using Google Colaboratory. You may find these files here:
1. For Program in Ukrainian - https://drive.google.com/file/d/1BxyJgw5p_qCMGP-y7nHMdc9EIzJvk1Q_/view?usp=sharing
