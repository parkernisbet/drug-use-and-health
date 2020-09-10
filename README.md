# Drug Use and Health
This project intends to cover two separate drug use related insights: drug use trends as a function of earliest age of consumption, and the impact of drug use on mental health. At the time of writing, only the first insight has been completed and uploaded to Github.

The health data used herein was sourced from National Survey on Drug Use and Health reports, spanning 2002 to 2018. Links for source overview and survey background can be found [here](https://nsduhweb.rti.org/respweb/homepage.cfm) and [here](https://www.datafiles.samhsa.gov/study-series/national-survey-drug-use-and-health-nsduh-nid13517), respectively.

For this notebook to be run, you will need to pull all NSDUH reports from the previous links and save them in the same project folder (under the naming scheme 'NSDUH_{year}\_Tab.tsv'). The files together amount to over 11GB, far in excess of GitHub's 25MB-per-file limit. When run, this notebook will create a series of new Excel files, of which only the 'df_{drug_type}.xlsx' are of importance; only these files were used in the creation of this project's infographic.

### Drug Use and Age Trends
A brief look at drugs use trends as a function of earliest age of consumption. In particular, the created infographic 'Drug Use and Age Trends.png' highlights an overall trend of individuals waiting until later in life before experimenting with drugs. The only drug to not strictly follow this pattern was inhalants, seeing slight net-positive change to for abusers under the age of 10.

### Impact of Drugs on Mental Health
Pending completion.
