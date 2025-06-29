# AI_Resume_Analyzer

#INTRODUCTION 
➢ The Main Objective of this tool is to analyze Applicant’s 
Resume Using Resume Parser Technique and Some Algorithm. 
 
➢ It Can be Used by any Organizations 
(Company/College/Individual User) that handle resume screening 
process.  
 
➢ The tool keep’s a track of all records into database for 
further admin side analysis. 
 
➢ Provides Tips and Recommendations based on their resume. 



#How to Run
Using CMD - run commands one by one. 

python -m venv venvapp

cd venvapp/Scripts

activate

cd../..

cd App

pip install -r requirements.txt

python -m spacy download en_core_web_sm

streamlit run App.py




 
#Advantages & Features of Proposed Tool  
➢ Tracks and Sort Resume Based on Job Roles. 
 
➢ Fast, Safe, Real-time Predictions. 
 
➢ More Efficient Review Overall. 
 
➢ Applicant’s Side 
 
o Applicant’s can upload their resume. 
 
o Using Parsing technique, it will fetch 
▪ Basic Info 
▪ Level of Expertise 
▪ Skills 
▪ Keys (for resume scoring) 
 
o Using Some Algorithm, it will recommend 
▪ Skills that can be added 
▪ Job role you are looking for 
▪ Your Expertise Level 
▪ Course & Certificate recommendations 
▪ Resume Tips & Ideas 
▪ Resume Overall Score 
▪ Interview & Resume Tip (YouTube Videos) 
 
 
 
 
 
➢ Admin Side 
 
o Get’s all the applicant data into a tabular format. 
 
o Download data into csv file. 
 
o Pie Chart for Predicted Field/roles according to skills. 
 
o Pie Chart of user’s experience level. 
 
o Total Number of applicants have uploaded their resumes. 
 
o Monthly Timeline. 
 
o Activity Maps 
▪ Most Busy Day 
▪ Most Busy Month 
 
#Disadvantage of Current System i.e. 
(Manual Resume Screening) 
➢ Time Consuming.  
 
➢ It is challenging task to handle resume manually. 
 
➢ Requires individual review of each resume from hiring managers 
 
➢ The same amount of time and effort is often expelled for 
candidates who are qualified as the ones who are. 
 
#Technologies Used 
➢ Frontend 
o Managed By Streamlit 
 
➢ Backend 
o Managed By Streamlit 
 
➢ Database 
o MySQL 
 
➢ Programming Language 
o Python3 
 
➢ Packages (pip) 
o Pandas 
o Base64 
o Numpy 
o PyResparser 
o PdfMiner 
o Plotly 
 
#Requirements 
• A Laptop/Desktop 
o Connected with Internet and has a browser 
o Installed MySQL 
 
• Single Network Connection 
o So that other devices can connect through network URL 
 
• A Simple Format Resume to test the tool 
 
#Limitations of Proposed Tool 
• May not give you accurate result because of different resume 
formats. 
 
#Conclusion 
• A Quick and easy to use Resume Analyzer 
o That analyse resume data and extract it into  
machine-readable output 
o Helps applicants with few recommendations. 
o And helps automatically store, organize, and analyse 
resume data to find the best candidate. 
 
#Reference 
• https://www.ijitee.org/wp-content/uploads/papers/v9i7/F4078049620.pdf 
• https://www.academia.edu/32543544/Resume_Parser_with_Natural_Language_Processing 
• https://www.rchilli.com/blog/resume-parsing-101/ 
• https://en.wikipedia.org/wiki/R%C3%A9sum%C3%A9_parsing
