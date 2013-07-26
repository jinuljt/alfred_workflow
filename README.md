juntao's alfred workflow
========================

***

##Add Event to Calendar

####usage:

>cal  event title  [at] time [on] date [in] location [#] calendar

####example:

* cal work hole day
>today's all day event

* cal new alfred workflow at 19:30
>event at 19:30 today

* cal dinner with wife at 19:30 on tomorrow
>event at 19:30 tomorrow

* cal meet with boss at 17:00  on fri in office # personal
>event at 17:00 friday on the calendar named "personal"

####optional arguments:

>**at** hh:mm *default* current time, without time will be all day event
>
>**on** date dd/mm/yyyy *default* today
>
>>string date mon/tue/wed/thu/fri/sat/sun/tomorrow  is ok
>   
>>short date dd dd/mm dd/mm/yyyy is ok
>   
>**in** location *default* is empty

>**\#** calendar name, *default* **please edit script to add your default calendar**


####TODO:

* parse params by python
* support am/pm
* select default calendar at first time