#                       **NYC 311 Service Request Analysis - Queens (2024)**


### Overview
An exploratory analysis of NYC 311 non-emergency service requests from Queens in 2024, looking at complaint patterns, agency response times, seasonal trends, and data quality issues.


### Data Used
A 2024 sample of NYC 311 service requests for Queens, sourced from the NYC Open Data 311 portal. (Raw data file not included per assignment guidelines.)


### Tools Used
Python, Pandas, Matplotlib, SQLite3


### Key Analysis

- Identified the most common complaint types and which agencies handle the most requests
- Calculated average resolution times by agency
- Found seasonal patterns (e.g., heat complaints peak in winter, noise complaints peak in summer)
- Detected and handled data quality issues (negative response times, status/closed-date contradictions, missing zip codes)


### Conclusion
Illegal parking is Queens' top 311 complaint, and the NYPD absorbs the vast majority of all requests-far more than any other agency. Complaints cluster heavily in specific zip codes and follow clear seasonal cycles (e.g., heat complaints in winter, noise complaints in summer), while resolution times and status records reveal gaps the city should address.


### Recommendation
The city should pilot targeted parking enforcement in high-complaint zip codes (e.g., 11385, 11368), shift non-criminal quality-of-life complaints like noise to dedicated civilian response teams to ease NYPD's load, and clean up status-tracking inconsistencies so 311 data can be fully trusted for future decision-making.


## Conclusion
Illegal parking is the top complaint in Queens, and the NYPD handles the bulk of all 311 requests. Complaint volume is concentrated in specific zip codes and follows clear seasonal cycles, insights the city could use to better target enforcement and allocate resources throughout the year.

