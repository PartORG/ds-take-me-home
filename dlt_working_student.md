# Working Student - Data position dlt



*Note: Please keep things simple and don’t spend more than max 4h on this task.*



Thank you for taking the time and talking to us about the Working Student - Data position. As a next step, we'd like to give you an Assessment.



### Context:



We’re trying to understand where our users come from, and which sources actually drive high-quality signups and engagement.



You have access to utm_source data for each contact as a custom field, alongside event data ("dlt_working_student" table in DBEaver).



The business is asking:



“Which acquisition sources bring in users who stay engaged? And which sources are just noise?”



The data provided:



You have been provided with a csv that contains a snippet of anonymized data of our users and events, and the fields they click on when they are signing up to any of our forms.



###Your Challenge:



#### 1. Model the Attribution Funnel



Model the data: 



how would you represent contacts, their UTM source, and engagement events?

Assume users will have multiple events after acquisition.

Use dlt OR your choice of tooling in python/sql to create a data model inside a duckdb destination.



#### 2. Create Metrics



For each utm_source, come up with 1-3 metrics like acquisition volume, engagement conversion, or retention. Visualize your chosen metrics.



As a bonus, how would you fit event category into this analysis for your insights?



Please create a python notebook/Google Colab that contains your insights report. Please ensure your report is well annotated.



#### 3. Draw a Business Insight



Examples:



“Alexey’s LinkedIn posts lead to the highest engaged users.”

“ChatGPT links drive high traffic but low follow-through.”