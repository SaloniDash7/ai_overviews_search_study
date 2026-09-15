# AI Overviews Reduce Engagement with Search Results and May Influence Attitudes

Materials, data, and analysis code for the paper *"AI Overviews Reduce Engagement with Search Results and May Influence Attitudes"* (Dash et. al, 2026).

## Repository Structure

- **`data/`** — De-identified, analysis-ready datasets (`study_data_final_deidentified.csv` for Study 1, `study_2_data_final_deidentified.csv` for Study 2).
- **`r notebooks/`** — R Markdown analysis notebooks (`Analysis_Notebook_Study_1.Rmd`, `Analysis_Notebook_Study_2.Rmd`) covering data cleaning, all confirmatory and exploratory models reported in the manuscript, and demographic summaries.
- **`survey/`** — Qualtrics survey exports (HTML) for Study 1 and Study 2, containing pretest attitude questions, the mock social media post, the search results page with AI Overview stimuli, and post-exposure measures.


## Note

The files in `data/` have been de-identified for sharing. Because of this, the initial data-loading step at the top of each notebook cannot be re-run as-is.

All statistical models and results reported in the manuscript (from the "Analysis" section of each notebook onward) can be reproduced directly against the provided de-identified CSVs.

## Citation

If you use this code or data, please cite the associated paper.
