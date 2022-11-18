---
layout: page
title: Method & Control
permalink: /type1/
---

### 2019 FRQ Q1
* The AP Calender is home to number of methods that are the backend for the end points made in the controller.
* [CLICK HERE!!!! to see working example](http://localhost:8085/api/calendar/dayOfWeek/12/12/2022)
* The method mentioned above uses the first day of any year and day in the given year to compute weekday of the given date. Uses 2 other methods which is the prupose of a method and control structure

```public static int dayOfWeek(int month, int day, int year) { 
    // to be implemented in part (b)
    int x = firstDayOfYear(year);
    int y = dayOfYear(month, day, year) - 1;
    int sum = x + y;

    return (sum % 7);
}
```
