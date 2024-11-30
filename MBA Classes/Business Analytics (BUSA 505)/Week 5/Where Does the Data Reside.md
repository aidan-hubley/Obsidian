## Assignment Prompt
The purpose of this assignment is to identify the data your organization needs to effectively implement analytics and make better decisions. Leverage your work to date in the course and your Business Analytics Project work to determine the following:

1. What are the data requirements (i.e., data needed) to effectively measure what you've proposed thus far?
    - Note: To date you have identified the following:
        - Where your organization could improve in using business analytics [[Discussion 1]]
        - How your organization might be more intentional/specific in what it measures [[Discussion 2]]
        - Critical to Customer Needs, Drivers, and Measures
        - Identification of opportunities where analytics could be embedded into business processes [[SOC Internship Hiring Analytics Process Model.canvas|SOC Internship Hiring Analytics Process Model]]
2. Are these data currently captured somewhere? If so, where? If these data are not currently captured, how might they be captured? (Create/describe the process.)
3. How might the data be structured (organized) and made available to decision-makers? Describe the process for making the data useable for decision-making.

Use the information from this assignment in your Business Analytics Project (BAP). In your BAP, not only do you want to make a compelling case for what needs to be measured, but you also want to illustrate where the data resides and how you intend to capture it and analyze it.

---
## Previous Assignments:
### How my Organization can be more intentional/specific in what it measures / Improve in using business analytics

I currently serve as an IT Security Analyst for Messiah's Cybersecurity team and a manager for Messiah's SOC internship. The value and need for deep analysis within my security analysis responsibilities cannot be overstated. 'How many accounts were affected by X vulnerability?' What percentage of employees are lacking X security measure?' Analysis of Messiah's user base and network is the core of my position, but that analysis isn't directly about data analysis. Another aspect of my position is managing 14 interns who work within Messiah's SOC internship program. On paper, this is a deeply social / leadership-oriented responsibility, but fortunately, the interns need little managing. I have been able to automate many if not all nuances and data collection aspects of the management side of this through a website, (note: it's available to all messiah accounts and has some helpful tools, go to: socservices.messiah.edu) I manage the database and run data analysis on everything, such as: internship timesheets, intern's response time, active vs inactive time on the workstations in the SOC, and more. My boss and I benefit immensely from this automated analysis, we can monitor and support these interns while maintaining our other responsibilities.

My organization, Messiah University, utilizes internal analytics for current students and faculty and externally through advertisements for graduates/alumni. Messiah excels at gathering and analyzing data about their courses, specifically student's experience with every course. They utilize an IDEA evaluation system to serve and report on every undergraduate-level course for each student. The detailed multiple-choice questions/text area questions speak to the depth at which the University is interested in querying and analyzing this data. Messiah collects data in a variety of layouts, types, and structures. Most notably, I have developed many of Messiah's custom websites, and the analytical data collected through my code is raw data, usually in the form of JSON or PHP arrays. More traditional structures of data, such as spreadsheet, pdf, and txt are created when we serve the data to users, clients, students, donors, etc. I believe many of Messiah's analytical processes are currently handled by expensive 3rd party systems such as dynamic forms, while they could be handled in-house by the expertise of the ITS department (where I work). The financial cost of deep data analysis is usually overlooked and I see an efficient alternative option that negates the price tag of 3rd-party services.

### SOC Internship Hiring Process
1. Announce Open Application Portal
	1. SOC managers advertise internship during in-class lecture, and announce the application portal is live
	2. Suggested Embedded Analytics: How many students were already planning to apply before SOC managers advertised the program? How many times should it be advertised?
2. Applicants find Faculty References
	1. Students reach out to faculty (professors) to be advisors / references to bolster their internship application
3. Application Window Closes
	1. Submission of application alerts SOC managers to review the application
	2. Suggested Embedded Analytics: How many applications because of the advertising? How many applications within the week before the deadline?
4. Creation of Team & Shifts
	1. SOC managers discuss team creation and intern roles
5. Applicants Receive Letters
	1. Rejection / Acceptance emails are returned to program applicants
	2. Suggested Embedded Analytics: Analysis on strengths and weaknesses that correlate to rejection and/or acceptance.
6. Begin New Semester
	1. NDA, meeting schedule, contact information, and group chat are provided to accepted applicants

---

## My Submission

Focusing on the SOC Internship Program.

1. What are the data requirements (i.e., data needed) to effectively measure what you've proposed thus far?
	1. To effectively measure my proposed steps in the hiring process and in the goal of improving the program, the data needed to measure is:
		1. Number of students that planned to apply to the program without the advertisement? 
			1. Formula to evaluate how many times should it be advertised?
		2. How many applications are a result of the advertising? 
		3. How many applications within the week before the deadline?
		4. Analysis on strengths and weaknesses that correlate to rejection and/or acceptance. 
		5. Correlation of timesheet data to quality of work / work efficiency. 
2. Are these data currently captured somewhere? If so, where? If these data are not currently captured, how might they be captured? (Create/describe the process.)
	1. The data is all captured through a custom created website 'SOC Portal'.
	2. Data collection process for Internship Application:
		1. SOC Managers open application window
		2. Applicants access the application page
			1. Upon accessing the page their GPA, class credits, year number and more are assessed. If they meet the requirements for applying to the internship, they are provided a form to fill out
		3. Applicants provide information such as: preferred name, interest in the program, who their reference is, their resume and more.
			1. **Suggested Improvement**: Querying applicants "how did you hear about this program" would inform decision makers on if the advertisements are worth it, and how often they should advertise.
		4. All data is sent to a MySQL database for decision makers to review
	3. Data collection process for Internship Timesheets:
		1. Interns access the SOC portal through their internship accounts, and navigate to the timesheet page
		2. They are met with a list of their timesheets and if they within 15 min (before or after) a shift is meant to begin they may clock in
		3. In a similar fashion, if they are within 15 min of a shift ending they may clock out
			1. Upon clocking out interns are met with a form asking for their notes from the shift
				1. All interns provide confident notes that are highly detailed to the SOC Managers
				2. Interns taking the ELI internship course (which provides academic credit) are prompted to provide their course professor with vague professional development takeaways (that do not violate their NDA)
		4. All data is sent to a MySQL database for decision makers to review
3. How might the data be structured (organized) and made available to decision-makers? Describe the process for making the data useable for decision-making.
	1. To ensure the data is organized, accessible, and usable for decisionmakers, 'Admin' pages have been developed for the SOC Portal
	2. These pages allow SOC Managers and some professors to access relevant data
	3. Admin page to review Intern Timesheets:
		1. SOC managers can review and correct timesheet data for each intern
		2. The data is organized in a way that allows for easy evaluation of a single intern's shift performance in reference to their other shifts
		3. **Suggest Improvement**: Developing a system to compare and contrast interns to each other could assist decision makers in providing feedback and in promoting interns to leadership positions
		4. Secondary page that is related to Data Organization for decision makers: ELI Credit Report Page:
			1. Developed to organize all timesheet data and ELI notes to provide to the ELI Internship Professor
			2. This data is organized chronologically to provide a simplified view of progress, stagnation, or decline in performance to both the SOC Managers as well as the Professor of the ELI class
	4. Admin page to review Internship Applications:
		1. SOC managers and Application references (faculty within CMP department) have access to view and depending on their rights approve / deny applications to the program
		2. The data is organized in a fashion that allows internships to be reviewed as "currently in the program and returning" or "first time applicant" or "currently in the program and not returning"
		3. References are provided with all the information from the application, including resume and certifications
		4. Decision-makers at all levels benefit from a consolidated 