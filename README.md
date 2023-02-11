# Project Background Information. 
Every ten years, the United Kingdom undertakes a census of the population, with the most recent one 
having been conducted in 2021. The purpose of such a census is to compare different people across the 
nation and to provide the government with accurate statistics of the population to enable better 
planning, to develop policies, and to allocate certain funding.

# Objective 
The town from the census is a modestly sized one sandwiched between two much larger cities that it is 
connected to by motorways. The town does not have a university, but students do live in the town and 
commute to the nearby cities. The aim is to decide what should be built on an unoccupied plot of land that the local government wishes to 
develop.

# Data Dictionary
The mock census  contains randomly generate data using the Faker package in 
Python. It has been generated in a similar manner to (and designed to directly emulate the format of) 
the 1881 census of the UK wherein only a few questions were asked of the population. The fields 
recorded are as follows: 
(1)  Street Number (this is set to “1” if it is a unique dwelling)

(2)  Street Name

(3)  First Name of occupant

(4)  Surname of occupant

(5)  Age of occupant

(6)  Relationship to the “Head” of the household (anyone aged over 18 can be a “Head” – they are 
simply the person who had the responsibility to fill in the census details)

(7)  Marital status (one of: Single, Married, Divorced, Widowed, or “NA” in the case of minors)

(8)  Gender (one of: Male, Female; note that other responses were not implemented in 1881)

(9)  Occupation (this field was implemented in a modern style, rather than typical 1881 
occupations)

(10) Infirmity (we have implemented a limited set of infirmities following the style of 1881)

(11) Religion (we have implemented a set of real-world religions)

