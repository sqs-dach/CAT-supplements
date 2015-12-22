Additional stuff for practical iSQI&#0153; CAT Certified Agile Tester&#0153;  Training
=========

* Holidays.xsls - Excel Sheet to generate SQL statements to add holidays of a given year

Scripts
------
Copy the content of the directory into the root home (/root) in the CAT image. 

* `sprintX_dropX` - The scripts prepare the environment for the corresponding sprint and drop. 
* `add_events` - add events for further years to the database. The events are specified in the `wp_eventscalendar\_YYYY.sql` files. New files may be generated using the `Holiday.xsls` Excel sheet. 