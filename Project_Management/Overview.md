# Project Overview

X-SFH_ARV_report is an AI-powered software tool to generate a report for After Repair Value (ARV) of a given Single Family House (SFH). 

## Input
Input of the software tool is the full address of a single family house. The full address needs to contain a street number, a street name, city, state, and zip code. It's the users' responsibility to make sure the address is a SFH. See some examples below.
9731 Wagon Train, Converse, TX, 78109
2643 Waleetka St, San Antonio, TX, 78210
8803 Merion Cir, Austin, TX 78754
3402 Chisholm Trl, Killeen, TX, 76542

## Output

Output of the software tool is a pdf report to show the SFH's ARV estimates and the house information of comps (houses used to generate the ARV are called comps). See some example in the output_examples folder.

# Requirements

In order to get accurate comps, this ARV report tool needs MLS access based on the location of the SFH. For example, the tool requires Austin MLS access to generate ARV reports for the houses in greater Austin area.

We start from Austin MLS access and will expand to other locations.
