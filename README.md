# Java-Loc8r
Loc8r is ~2 week project that lets you input a longitude-latitude pair and lets you see stores of a selected type in a certain radius around that point.

*Copy-pasted from default README.txt file:*
LOCATION.TXT
---
The "location.txt" file contains a listing of several hundred, Austin-area locations.
Each line of the text file represents information about a single location. Location data
includes a NAME, a STREET ADDRESS, a TYPE, a LONGITUDE, a LATITUDE, whether or not the
location is a FAVORITE, a RATING, and a series of COMMENTS, each separated by a tab character.
The general format for each line of the data file is as follows:

`NAME  <tab>  STREET ADDRESS  <tab>  TYPE  <tab>  LONGITUDE  <tab>  LATITUDE <tab> FAVORITE <tab> RATING <tab> COMMENT 1 <tab> COMMENT 2 <tab> ... LAST COMMENT <newline>`


For example:
---
H-E-B	11521 North FM 620 Road	grocery store	-97.825895829215 	30.454660866175
Courtyard by Marriott	12330 North IH 35	hotel	-97.675170180808 	30.401114551909
HomeAway	1011 West 5th Street	travel	-97.755589195714 	30.270460592763
Saltgrass Steakhouse	10614 Research Boulevard	restaurant	-97.74707445096 	30.397651405056

This data translates to the following 4 locations:

H-E-B
11521 North FM 620 Road
grocery store
(-97.825895829215, 30.454660866175)


Courtyard by Marriott
12330 North IH 35
hotel
(-97.675170180808, 30.401114551909)


HomeAway
1011 West 5th Street
travel
(-97.755589195714, 30.270460592763)


Saltgrass Steakhouse
10614 Research Boulevard
restaurant
(-97.74707445096, 30.397651405056)


The current list of location types (additional types may be added later):
---
accounting
air travel
auto
auto repair
bakery
banking
biomedical
camping
coffee shop
dentist
education
festival
financial service
government
grocery store
hospital
hotel
interior design
jewelry
landscaping
livery service
museum
office supplies
pest control
physician
plumbing
public relations
recreation
restaurant
retail
technology
theater
transportation
travel
venue
