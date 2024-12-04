# A Day in the Life of a Data Analyst

A day in the life of a Data Analyst can include a number of possibilities — from acquiring data from varied data sources to creating queries for pulling data from data repositories, foraging through rows of data to look for insights, creating reports and dashboards, and interacting with stakeholders for gathering information and presenting the findings, it’s a spectrum.

And yes, the big one — cleaning and preparing the data so that the findings have a credible basis — which, by the way, is a large part of what any Data Analyst may find themselves doing in their jobs. But if I had to walk you through any one “type” of day, I’m going to pick one which has me foraging through data looking for insights. This is the part of my job that I am totally in awe of.

Hi. I’m Sivaram Jaladi. I work as a Data Analyst with Fluentgrid, a smart grid technology solutions company based in Vishakhapatnam in India.

Fluentgrid is an IBM partner and the recipient of IBM Beacon awards for its solutions in the areas of smart energy and smart city industry segments.

We offer integrated operations center solutions for power utilities and smart cities, leveraging our actionable intelligence platform known as Fluentgrid Actilligence.

Our client, a power utility company in South India, has been noticing a spike in complaints regarding overbilling.

And the frequency of these complaints seems to suggest there’s something more to it than random occurrences.

So, I’m asked to look at the complaints and the billing data and see if I can spot something.

I start by taking stock of what I have.

Some of the obvious places that I know I’m going to be looking into is the complaint data, the subscriber information data, and the billing data.

That’s going to be my starting point.

Before I dive into the specifics of the data, I’m going to make a list of questions, initial hypotheses, that I am going to start with.

Such as the usage pattern of subscribers reporting this issue: Is there a consumption range for which overbilling is occurring more than others? Area-wise concentration of complaints: Are the complaints concentrated in specific localities within the city? Frequency and occurrence of complaints based on individual subscribers: Are the same subscribers reporting overbilling repetitively? If yes, what is the frequency of occurrence in repeat cases? If a subscriber is overbilled once, does the overbilling occur every month from the first occurrence, or are repeat occurrences sporadic, or not at all? As I get clear on my initial hypotheses and the set of questions I’m going to start with, I identify the datasets that I am going to isolate and analyze to validate or refute my hypotheses.

I pull out the average annual, quarterly, and monthly billing amounts of the complainants and look for a range in which the complaints are falling more than others.

I then pull up the location data of the complainants to see if there is a connection between overbilling and zip codes. 

Here I see what seems to be a concentration of complaints in certain areas.

This looked like it could add up to something.

So instead of moving to the third hypothesis, I decide to get a little deeper into this data

Next, I pull out the date of connection data.

More than 95% of the complainants had been our subscribers for more than seven years, though not all subscribers over the 7-year mark were facing this complaint.

So now, we see some area-wise concentration, and we see a significant concentration of complaints based on the date of connection.

Next, I pull out the make and the serial number of the meters.

And there it is — the serial numbers belonged to the same batch of meters provided by the same supplier.

The concentration of these meters, and therefore the complaints, was coming from areas in which these meters were installed.

At this stage, I feel confident in presenting these findings to the stakeholders.

I’m also going to share the data sources and my process of arriving at this analysis — that always goes a long way in lending credibility to the findings.

This could be the end of this project, or it may very well come back.

Maybe the same complaints with different commonalities, or a completely different set of complaints for which we need to find answers.