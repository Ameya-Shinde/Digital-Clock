# JavaScript Clock

## Overview

This repository contains a simple JavaScript clock that displays the current time in hours, minutes, seconds, and AM/PM. It updates the time display every second and provides customization options to display the time in different formats.

## Features

- Displays the current time in hours, minutes, seconds, and AM/PM.
- Updates the time display every second.
- Utilizes key JavaScript functionalities, including:
  - `Date` object
  - `getElementById()` method
  - `innerText` property
  - `setTimeout()` method
 
### 1. Date Object

The JavaScript `Date` object is a built-in feature that serves as a core component for handling date and time. It provides various methods to access and manipulate date and time components, such as hours, minutes, and seconds. In this project, we use the following methods from the `Date` object:

- `getHours()`: Retrieves the current hour of the day.
- `getMinutes()`: Retrieves the current minute of the hour.
- `getSeconds()`: Retrieves the current second of the minute.

These methods are used to obtain the current time and update the clock display.

### 2. getElementById() Method

The `getElementById()` method is a Document Object Model (DOM) function used to retrieve an HTML element by its unique identifier, known as the element's ID. Each HTML element can be assigned a distinct ID, and this method allows us to select and work with specific elements in the HTML document.

In our JavaScript clock project, we utilize `getElementById()` to access and manipulate HTML elements that display the time, such as "hour," "minutes," "seconds," and "ampm."

### 3. innerText Property

The `innerText` property is a DOM property that enables us to modify the text content within an HTML element. It allows us to dynamically update the displayed text of an element.

In our project, we utilize `innerText` to set the content of the HTML elements representing the hours, minutes, seconds, and AM/PM parts of the clock. This property is used to reflect the current time.

### 4. setTimeout() Method

The `setTimeout()` method is a JavaScript function used for scheduling the execution of a specified function after a designated time interval. It is especially useful for creating timers and executing code at specific intervals.

Within our project, we employ `setTimeout()` to continuously refresh the clock's display. The `updateClock()` function, responsible for updating the time, is called repeatedly with a delay of 1000 milliseconds (1 second) between each update.

These functionalities collectively create a dynamic digital clock that displays the current time, updating every second.


## Hosted Link
https://ameya-shinde.github.io/Digital-Clock/
