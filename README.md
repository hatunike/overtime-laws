# overtime-laws
A repository that explores various programming challenges with calculating employee wages. These complications arise from different rules for different countries, states, date ranges, and even different types of employeement. Flexible, robust, software should handle each and every one of these rules. A starting place is to simply list all of the particular rules and exceptions in one place. Example data and totals from that data can then be used to test handling of all cases.

Software can then be compliant with the test data and test results.


workweek :  (any fixed and regularly recurring period of 168 hours — seven consecutive 24-hour periods) 

regular rates :  "Bonus payments" are to be included in calculating an employees "regular rate"

hours worked : Ordinarily include all the time during which an employee is required to be on the employer’s premises, on duty, or at a prescribed workplace.

###Federal
Employees covered by [Fair Labor	Standards Act](http://www.dol.gov/whd/flsa/) must receive overtime pay for hours worked in excess of 40 in a workweek of at least one and one-half times their regular rates of	pay

### State
Hours worked beyond eight hours per day qualify for overtime pay of one-and-one-half times the regular hourly wage.
 
### Timezones
Timezone strategy : 

### Seed Data
Good seed data that can be used to verify that numbers have been accurately calculated is essential to writing software for calculating totals. There are many scenarios which, if unhandled by the software, will be shown in real life to give incorrect totals. This suite of tests is designed to cover each of the scenarios. JSON, and XML files will be made available to assist in writing the software. Here they will be documented and discussed. They are grouped by year.

##2016

### #1 - Basic Totals - No Overtime

#### Variation A
    {
        week_start_epoch: 1453075200,
        week_start_human: Mon, 18 Jan 2016 00:00:00 GMT,
        week_end_epoch:1453636799,
        week_end_human:Sun, 24 Jan 2016 11:59:59 GMT
    }












