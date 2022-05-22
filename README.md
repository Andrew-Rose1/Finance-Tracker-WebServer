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
![Dashboard_zoomedOut_hidden](https://user-images.githubusercontent.com/55816533/137607154-317f3a0e-4cc2-4071-99b3-e5df97a86085.jpg)
An example of the current home screen (dashboard). Screenshot was taking at 75% zoom.

### Dashboard -- Transactions
![Dashboard_transactions_hidden](https://user-images.githubusercontent.com/55816533/137607159-a9758d8d-8f33-41a9-986d-76561c9c08e6.jpg)
This is what is shown below the two bar graphs on the dashboard.

### History Page
![history_hidden](https://user-images.githubusercontent.com/55816533/137612725-7486f3ed-bba6-472a-bd1f-5c4cc2227bce.jpg)
A screenshot of the "History" page, which shows the past 12 months of expense/income history. Plans to include all transactions beneath each month's graphs. (~75% zoom)


## Developer Notes
This project is still a work in progress and I plan to upload the code when I have a clean and fully functional base version up right now. What you see in the images above is what I currently have working.

