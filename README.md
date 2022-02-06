# This application is a Work Day Scheduler
This application allows users to save events for each work day, typically based on a 9-5. This app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery.


PAST - color coordinated as RED
PRESENT - color coordinated as Blue
FUTURE - color coordinated as YELLOW


<date picker> added 
.addEventListeners to save into localStorage.
Moment.js used for time and date.


# Acceptance Criteria 
GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with timeblocks for standard business hours
WHEN I view the timeblocks for that day
THEN each timeblock is color coded to indicate whether it is in the past, present, or future
WHEN I click into a timeblock
THEN I can enter an event
WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist