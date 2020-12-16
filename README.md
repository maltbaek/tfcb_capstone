# tfcb_capstone

The data for this repo is sourced from [here](https://datadryad.org/stash/dataset/doi:10.5061/dryad.g8h71).

These data are used in the following published paper: [this published study](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0166067#pone.0166067.s001).

For my analysis in this repo, the following files are included (start with 'report_r.Rmd' for explanation of dataset and analysis):

# Directory structure and files:
	README - Explanation of primary directory structure
	data/: original data sets
		README - Explanation of dataset(s) used in final project
		pcbil_raw.csv: immunohistochemical data and anatomical diagnoses
		pcbilDataImputed.csv: raw data tidying and imputed; certain samples eliminated (explained further in r_report.rmd)
	figures/: final figures for capstone project
		README - Explanation of figures generated from questions in final project
		question2.png: result from Question 2, generated in R studio
		question3.png: result from Question 3, generated in python
	report_r.Rmd: Questions 1-2: explanation of research questions and code
	report_python.ipynb: Question 3: explanation of research question and code
