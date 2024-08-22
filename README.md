# ca-oc-election-results
Code for parsing election results from Orange County, California's Registrar of Voters.

This repository contains a Python notebook that scrapes the website of the Orange County (CA) Registrar of Voters and parses the downloadable election results into two CSV files: precincts.csv and elections.csv. These data sources are intended for use with data visualization tools, particularly Tableau.

I don't own this data; the OC ROV does. Please don't use it for nefarious purposes. I also make no guarantees re the accuracy of the parsed data; this code was not validated before publishing. Please check open issues; there are some known bugs that affect the output of this code.

OC Archived Statements of Votes: https://www.ocvote.gov/data/election-results-archives/archived-statement-of-votes
