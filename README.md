# economist-clusters

survey-html-files - folder containing HTML files. Each file corresponds to one survey conducted by the IGM Economic Experts Panel. 

IGM Economic Experts Panel _ IGM Forum.html - simply the saved html file from http://www.igmchicago.org/igm-economic-experts-panel

panel_data_collection.ipynb - Section 1 parses the above HTML to create a csv of links to every panel question webpage (this was simply for convenience: because I was unable to web scrape the IGM Economic Experts Panel website, I needed to save every question and answer page as a HTML to collect the data. Having a csv of every question webpage URL made the process slightly less tedious). Section 2 accesses every HTML file saved in surveu-html-files folder and parses the Q&A data.

output-data/IGMPanelLinks.csv - output of above .ipynb file Section 1

output-data/answers.csv - output of above .ipynb file Section 2; panel question and answer data in tidy form

output-data/answersAsColumns.csv - output of above .ipynb file Section 2; panel question and answer data in pivot form
