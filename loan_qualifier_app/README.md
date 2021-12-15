# Loan Qualifier Application:

This application was built to better assist users inquiring about obtaining a loan. The app asks 4 basic questions: what is your credit score, debt to income ratio, loan to home value ratio, and how large of a loan are you seeking?  The application takes the information provided by the user and shows them if they qualify for a loan and which banks would be willing to provide one.  



---

## Technologies

This application uses python version 3.7 as well as the following libraries:

`fire` - This library is needed to create the command-line interface that the app runs on. 

`questionary` - This is an interactive program that asks users questions in the command-line interface.  

---

## Installation Guide

In this section, you should include detailed installation notes containin
To install and use the applications users 

Before running the program, users must install the following packages:

- `pip install fire`

- `pip install questionary`



---

## Usage

In order to use the loan qualifier application, the user must clone the *Module2_Challenge* repository from GitHub and paste the link in terminal. 

**After cloning from the repository the user must open and run application with the following code in the command line:**
- `python app.py`

After entering the application into the command line, the user will be asked for a CSV file path: *Enter a file path to a rate-sheet (.csv):*


**The user will then enter the following csv file path:**

- `./data/daily_rate_sheet.csv`

Once this step is completed the user is now able to enter their financial information to see if they qualify for a loan.

**If the user does qualify for a loan they will be prompted with a question to save their bank loan options to a CSV file**

- The user can save the CSV file by answering 'Yes' and save the file to their desired location locally. 

---

## Contributors

Brought to you by UNC Charlotte and Patten Williams

---

## License

UNCC
