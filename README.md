# Finance Tracker WebServer
This is a webserver which allows you pull your bank account data via Plaid Link and see a break down of your income and expenses, including data visualization through bar graphs.

## Development Stage: Development

Source code and Getting Started section coming soon. Current build is not 100% stable and code is messy...

## Features
- Define your own categories by providing keywords to look for in transaction titles.
- See a snapshot of your current month's spending and where income is coming from.
- Look back on the past year's worth of historical banking data using your predefined categories.
- Utilizes local JSON data structures to minimize the amount of Plaid API calls needed to be made.
- Utilizes Python and Flask to run back-end computations/API calls.
- Utilizes HTML/CSS and Jinja2 Tempaltes to provide frontend visualization and communication to back-end. 

## Example
Below are some screenshots of the current build, including the main dashboard and historical data page.
I have ran the build in "privacy" mode, to hide things such as available balance. Most other sensative information has been manually blacked out.

### Dashboard
![Dashboard_zoomedOut_hidden]<img width="1510" alt="expense-tracker-spotlight" src="https://github.com/Andrew-Rose1/finance-tracker/assets/55816533/f3e932a2-b265-4ff2-bcae-4712f1db027c">

An example of the current home screen (dashboard).

## Developer Notes
This project is still a work in progress and I plan to upload the code when I have a clean and fully functional base version operational. What you see in the images above is what I currently have working.

