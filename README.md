# AssociatonRules
Association Rule mining for psychometric Data. In the present Repository there are Python files and RStudio files because I'm trying both languages to mine association rules related to psychometric data, being GMA the results of hability tests and Personali-T being the results of psychometric studies of each candidate.

## Disclaimer:
Neither the raw data nor the files where the data is modified will be uploaded due to the presence of sensitive non-disclosable information.

## About the files:
- *Apriori Personali-T* is the implementation of the Apriori Algorithm for association rule mining for the personality traits evaluation dataset.

- *Apriori GMA* is the implementation of the Apriori Algorithm for association rule mining for the hability evaluation dataset.

- *Association Rule Mining* will contain anly Personality traits data because GMA Association rules (python file) showed that the most relevant rules were all related to time variables, which makes absolute sense because those variables measure the time spent on a question, showing an obvious relation between the earlier questions (antecedents) and the las questions (consequences). The purpose of this particular file is recreating Association Rules in RStudio and plotting and clustering them with the R Library 'arulesViz'.

## About the datasets:
- Some NA's have been categorized with 0 in the GMA dataset.
- All datasets have been turned to binary data (1 = fits in the category or meets the criteria, 0 = doesn't fit or doesn't meet the criteria).
- GMA contains the results of psychological hability tests.
- Personali-T contains the results of Psychometric testing, measuring more than 30 personality traits out of 5 main personality traits families (Big Five theory).
