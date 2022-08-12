# US District Education Analysis
This is an experimental repo that will analyze US District data for education and apply a machine learning algorithm to determine likely factors in district success.

# Data Sources <br>
## Department of Education<br><br><img src="https://upload.wikimedia.org/wikipedia/commons/a/ad/Seal_of_the_United_States_Department_of_Education.svg" width="150">
### <u>Documentation:</u><br><i>https://www2.ed.gov/about/inits/ed/edfacts/data-files/assessments-sy2018-19-public-file-documentation.docx</i><br><br>
<b>grad_rate.csv:</b> <i>https://www2.ed.gov/about/inits/ed/edfacts/data-files/acgr-lea-sy2018-19-wide.csv</i><br>
<b>math_achieve.csv:</b> <i>https://www2.ed.gov/about/inits/ed/edfacts/data-files/math-achievement-lea-sy2018-19-wide.csv</i><br>
<b>math_part.csv:</b> <i>https://www2.ed.gov/about/inits/ed/edfacts/data-files/math-participation-lea-sy2018-19-wide.csv</i><br>
<b>read_achieve.csv:</b> <i>https://www2.ed.gov/about/inits/ed/edfacts/data-files/rla-achievement-lea-sy2018-19-wide.csv</i><br>
<b>read_part.csv:</b> <i>https://www2.ed.gov/about/inits/ed/edfacts/data-files/rla-participation-lea-sy2018-19-wide.csv</i><br>
## US Census Data<br><br><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/85/Seal_of_the_United_States_Census_Bureau.svg/1200px-Seal_of_the_United_States_Census_Bureau.svg.png" width="150">
### <u>Documentation:</u><br><i>https://www2.census.gov/programs-surveys/saipe/technical-documentation/file-layouts/school-district/2020-district-layout.txt</i><br><br>
<b>poverty.csv</b> <i>https://www2.census.gov/programs-surveys/saipe/datasets/2020/2020-school-districts/ussd20.xls</i><br>
<i>The above file needed to be modified from its original xls file to a csv for ease of analysis.</i><br><br><br>
# Work and Idea Log:
<i>August 12th, 2022</i><br>
My plan is to make a model for successful school district achievement prediction based on curricular, extra-curricular and socioeconomic features.