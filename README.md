# super-duper-invention
adv_web_dev_project_planning

Phase 1: Definition and Planning - Loan Calculator Web App
Project Title:
SmartLoan Calculator
Team Members:
	Chuks
	Muditha

User Personas
1. Sarah – University Student
•	Age: 21
•	Goals: Looking to understand repayment terms for her student loans.
•	Pain Points: Confused about interest rates and how they affect repayment over time.
•	Tech Savviness: Moderate
•	Device: Smartphone
2. James – Small Business Owner
•	Age: 38
•	Goals: Wants to compare loan options for expanding his business.
•	Pain Points: Needs fast, accurate comparisons without financial jargon.
•	Tech Savviness: High
•	Device: Laptop/Desktop
3. Anita – Young Professional
•	Age: 27
•	Goals: Planning to buy a car, wants to explore auto loan plans.
•	Pain Points: Not sure how different durations affect monthly payments.
•	Tech Savviness: Moderate
•	Device: Smartphone and Laptop

Use Cases and Usage Scenarios
Use Case 1: Calculate Monthly Payment
Actor: Any user
Description: User selects a loan type, inputs the principal and duration, and the app calculates monthly payment.
Use Case 2: Compare Loan Options
Actor: James (Business Owner)
Description: User toggles between loan types to see interest rate differences and how they affect total repayment.
Use Case 3: Mobile Accessibility
Actor: Sarah (Student)
Description: On her mobile phone, Sarah quickly inputs loan info and gets immediate feedback on her repayment amount.

UI Prototypes
The prototype (as shown in the attached UI/UX image) includes:
•	Clean and intuitive layout
•	Radio buttons to choose loan type
•	Input fields for principal and duration
•	Read-only field for interest rate populated from API (with fallback messaging)
•	Reset button
•	Dynamic error handling for API issues

Information Architecture and Technical Design
Front-End:
•	Framework: React.js or vanilla JavaScript + HTML/CSS
•	Design Tool: Figma (for mockups)
•	Responsive Design: Bootstrap or TailwindCSS for responsiveness
Back-End:
•	API Source: AWS Lambda + API Gateway (as seen in the screenshot, currently needs DNS/API configuration fix)
•	Fallback Plan: Hardcoded interest rates as default if API fails
•	Language: Node.js or Python (Flask)
Data Flow:
1.	User selects loan type →
2.	Front-end requests interest rate from API →
3.	User inputs principal and duration →
4.	Calculation: Monthly Payment=P×r(1+r)n(1+r)n−1\text{Monthly Payment} = P \times \frac{r(1+r)^n}{(1+r)^n - 1}
5.	Result is displayed instantly

Project Management and User Testing
Project Timeline:
•	Week 1: Definition and planning (current phase)
•	Week 2: Build front-end structure + API test mockup
•	Week 3: Integrate full back-end and handle edge cases
•	Week 4: Testing, debugging, and user feedback
•	Week 5: Final polish and presentation prep
Project Management Tool:
•	Trello board with to-do, in-progress, and done columns
•	Weekly Zoom stand-up with assigned roles:
o	Chuks: UI/UX & Front-end logic
o	Muditha: Testing, Documentation & Back-end API
User Testing:
•	Run testing rounds with 3 real users from different personas
•	Use feedback to adjust interface, error handling, and labels


Muditha and i have defined our target users, key use cases, detailed our interface prototype, and mapped out our architecture and team workflow. This plan ensures that we are on track to develop a functional and user-friendly loan calculator web app.

