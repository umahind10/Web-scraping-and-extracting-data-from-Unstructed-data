# Web-scraping-and-extracting-data-from-Semi-structed-data-(Python)
1.	Write code in Python for each point:
	Search for ONGC’s official website from a search engine.
	From the search engine results,
–	Find link to official website
–	Use link to enter ONGC website to search for 2021 ONGC’s annual report
	Download ONGC’s 2021 annual report, in pdf format, to the “Download” folder of your local computer.
	Extract the information under the section where it shows all subsidiaries, joint ventures, and associates but only the following columns are relevant:
–	Name of the Company
–	Country of Incorporation
–	Proportion of ownership interest as March 31, 2021
	Perform fuzzy matching on each subsidiary name against each of the other subsidiaries’ names. Fuzzy matching is a technique that matches strings together that fits a particular pattern approximately. You will need to record:
–	“Yes” if the fuzzy match is an “approximate match”, along with what the top matched name was to (i.e. the matched subsidiary name)
	Note that you will need to define “approximate match” and explain your reasoning. Your answer can be placed in the output xlsx file in a separate tab.
–	“No” if the fuzzy match is not an approximate match
	Output the results into the below five columns within a xlsx file:
–	Name
–	Country of Incorporation
–	Interest
–	Match (Yes / No)
–	Matched subsidiary name
