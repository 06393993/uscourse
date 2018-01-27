# ClassScheduler

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.5.2.

This project includes following features:

* search department
* search course
* selected courses list
* breaks
* schedule

## Search department

An input with dropdown. Departments can be found through code(CSCI) or full name.

## Search course

An input with dropdown.

Once department is selected, courses can be searched. Code(CSCI 571) or full name(Web development) are both accepted.

The detailed sections will not display.

## Selected courses list

A row represents a course.

A check box to toggle if a specific courses will be included in the schedule. Once unchecked, this course will be removed from schedule temporarily.

Code and course name.

A remove button to remove the course from schedule permanently.

Once the row is clicked, the detailed sections will show up, including following collumns:

* check box to remove section temporarily
* section name
* professor
* rating
* week of day and time
* location

## Breaks

A new button to create a new break.

A break list, an accordion, click any row to edit the detail.

* a check box to disable/enable the break
* name
* time
* length(when input, hours and minutes are separted)
* repetation(based on week)
* remove

## Schedules

A list of schedules.