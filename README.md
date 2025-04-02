# RPA Challenge

This repository contains the solution to the **RPA Challenge**, an automation task designed to test your skills in Robotic Process Automation (RPA). The objective of the challenge is to create a workflow that automatically inputs data from a spreadsheet into a web form, while handling dynamic form field positions that change with every submission.

[RPA Challenge](https://rpachallenge.com/)

## Challenge Overview

The challenge consists of the following key requirements:

1. **Data Input**: You will need to automate the process of filling in form fields on a website using data from an Excel spreadsheet. Each field in the form corresponds to specific data points in the spreadsheet (e.g., Role, Company Name, Address, etc.).

2. **Dynamic Fields**: After each submission, the form fields will change their positions on the screen. Therefore, the workflow must be designed to correctly identify and fill in the right fields, no matter where they appear.

3. **Challenge Rounds**: The challenge consists of 10 rounds, each requiring the submission of a new set of data. You are free to test the workflow as many times as needed before starting the countdown. The actual countdown will begin once you click the "Start" button.

4. **Excel File**: An Excel file is provided with the required data. You need to automate the extraction of data from this file and input it into the form correctly.

## Instructions

- **Download Excel File**: Download the Excel file with the data to be entered into the form.
- **Start the Challenge**: Click on the "Start" button to begin the countdown for the actual challenge. You can submit the form multiple times before the countdown starts without any penalties.

## Technologies Used

This solution utilizes **UiPath**, a leading RPA platform, to automate the entire process. UiPath is used to interact with the web form, extract data from the Excel file, and handle the dynamic nature of the form.

- **UiPath Studio**: For designing and developing the automation workflow.
- **Excel Automation**: For reading and processing the data from the provided Excel sheet.
- **Web Automation**: For interacting with the web form and filling in the fields.

## Setup

1. Clone this repository to your local machine.
2. Open the project in UiPath Studio.
3. Ensure you have the necessary dependencies installed, such as UiPath.Excel.Activities and UiPath.UIAutomation.Activities.
4. Download the Excel file provided in the challenge and ensure it is correctly placed in the project directory.

## How to Run

1. Open the UiPath project in UiPath Studio.
2. Run the workflow by clicking **Run**.
3. The automation will start by reading the data from the Excel file and filling in the corresponding fields in the web form.
4. If the positions of the fields change, the workflow will dynamically adjust to identify the new field locations and input the correct data.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
