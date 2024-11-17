# date-picker-project

I built a date picker using a combination of HTML, CSS, and JavaScript. I did not use any libraries for this project. Instead, I wrote a JavaScript DatePicker class that directly manipulates the Document Object Model (DOM) and adds event listeners on DOM elements. I also used the JavaScript Date object to calculate the day of the week for the first day of a specified month-year, as well as the number of days in that month-year.

The number of rows is not fixed (while most months have 5 weeks, some have 4 or 6 weeks) and some weeks contain days from a different month, which are showed in a dimmed fashion. The date picker also contains controls to change the calendar’s display to the previous or next month.

### Figure 1:
Cycles through months with different number of weeks.

<br>

<p align="center">
  <img src="https://github.com/hansbdejong/date-picker-project/blob/main/date-picker.gif" 
        width="70%" height="70%">
</p>

<br>
