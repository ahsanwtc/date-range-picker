# date-range-picker
A calendar plugin for date range picks.

Adding variable to hold the dates within a range including start and end date.
```javascript
this.eventDates = [];
```
```javascript
this.startDate && this.endDate && ($(e.target).hasClass('in-range') || $(e.target).hasClass('today') || $(e.target).hasClass('active'))
```
This checks if clicks are inside the range. Once the click is inside the range, it updates the `eventDates` array

Extended from https://github.com/dangrossman/bootstrap-daterangepicker