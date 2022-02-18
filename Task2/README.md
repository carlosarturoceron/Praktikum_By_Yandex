1. Download the event_data.csv dataset, which contains data on the use of the mobile
application of users who registered from July 29 to September 1, 2019:
• user_id - user identifier;
• event_date - time of the event;
• event_type - type of event: 
	registration - registration in the application; 
	simple_event click event in the application; 
	purchase - an event of purchase within the application;
	purchase_amount - purchase amount.

2. Highlight user cohorts based on the week of registration in the application. The cohort
identifier should be the week ordinal (for example, the week from July 29 to August 4
should have identifier 31).

3. How many unique users in the cohort with ID 33?

4. For each event, highlight the indicator lifetime - the weekly lifetime of the cohort. The
lifetime indicator is calculated based on the serial number of the week in which the event
is committed, relative to the week of registration. For example, an event committed on
August 3 by a user from a cohort of registrants at 31 weeks will be committed on the zero
week of lifetime, and an event committed by the same user on August 5 will be committed
on the first week of lifetime).

5. Build a summary table of changes in the Retention Rate for cohorts depending on lifetime.

6. What is the 3 week retention rate for a cohort with ID 32? Give the answer in percent,
rounded to 2 decimal places, inclusive.

7. Build a summary table of changes in the indicator ARPPU (Average Revenue Per Paying
User) for cohorts depending on lifetime.

8. What is the 3-week ARPPU of a cohort with ID 31? Give the answer with a floating point
number, rounded to 2 decimal places, inclusive.

9. What is the median time between user registration and first purchase? Give the answer
in seconds (!) As an integer.
