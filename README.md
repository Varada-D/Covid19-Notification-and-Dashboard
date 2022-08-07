# About the Project
* The “COVID-19 Statistics Notification and Dashboard System” is a GUI- based Python-coded system, which uses some basic concepts of web-scraping. The code focuses on extracting the state-wise Covid-19 Data from an existing website (http://bioinfo.usu.edu/covidTracker/india.php) and displaying it in a presentable format through tkinter windows.
* The state-wise extracted data is displayed in the tkinter window through treeview, while four distinct buttons have been created to enable the user to see the bar graphs for each of the statistics (the total confirmed cases, recovered cases, active cases and deaths), state-wise.
* The system also gets the real time location of the user (from the website: https://ipinfo.io/) and notifies her/him with the statistics of her/his state as per the location fetched.

# Required Libraries
* ***PLYER***: for desktop notifications
* ***REQUESTS***: fetch the source code of the web page from where the data is to be extracted
* ***BS4/ BEAUTIFUL SOUP 4***: to parse the source code of the web page, and extract the required data/ information
* ***TKINTER***: to create a Graphics User Interface (GUI) for the dashboard with all the COVID-19 statistics extracted
* ***MATPLOTLIB***: to plot graphs for the acquired statistics

# Additional Files Required
> Used for icons in the tkinter window, and for the notifications generated through the code
* Logo.ico
* Logo.png
* thankYou.png

# Project Report and Demo
* For more details about the project and the libraries used, please refer "Project Report - Covid19StatisticsNotificationAndDashboardSystem.pdf"
* For demo and code explanation, please refer "Demo Video - COVID19 Statistics Notification and Dashboard System.mp4"
