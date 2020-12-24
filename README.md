# Mafia Activity Index

This project tries to measure the activity of mafia in Italy, irrespective of origin of organized crime organization. This project worked in multiple phases: 

## Spotting mafia in Italy 
Here I used the report by Italy's Direzione Investigativa Antimafia (DIA) reports to the Parliament to spot where mafia was. Using the QDA software, I spotted the so-called 'named entities'. Then I merged the resulting dataset with the names of communes. Given that communes are organized into provinces, I then aggregated the number of quotes per provinces. 

## The logit
The binary quoted/non-quoted was the dependent variable of a number of reported crimes usually connected to mafia activities. I interpreted the logit as the activity of mafia from 0 to 1. The theory is: the more mafia is active, the more the probability it is quoted in one of the DIA reports. 

## Where is the code?
As of Christmas 2020, the code is spread on 3 computers in two countries. I am fixing this ASAP. More details on this project are in the 

