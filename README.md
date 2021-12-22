# AssociatonRules
Association Rule mining for psychometric Data. In the present Repository there are Python files and RStudio files because I'm trying both languages to mine association rules related to psychometric data, being GMA the results of hability tests and Personali-T being the results of psychometric studies of each candidate.

## Disclaimer:
Neither the raw data nor the files where the data is modified will be uploaded due to the presence of sensitive non-disclosable information.

## About the files:
Apriori Personali-T is the implementation of the Apriori Algorithm for association rule mining for the personality traits evaluation dataset.
Apriori GMA is the implementation of the Apriori Algorithm for association rule mining for the hability evaluation dataset.
Association Rule Mining (not finished yet) will contain both GMA and Personality traits data. The purpose of this particular file is recreating Association Rules in RStudio and plotting and clustering them.

## About the datasets:
Some NA's have been categorized with 0 in the GMA dataset.
All datasets have been turned to binary data (1 = fits in the category or meets the criteria, 0 = doesn't fit or doesn't meet the criteria).
GMA contains the results of psychological hability tests.
Personali-T contains the results of Psychometric testing, measuring almost 50 personality traits.
