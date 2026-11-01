# DATA 607 Tidyverse Vignette Assignment




## Overview




In this assignment, you will practice collaborating on a code project with GitHub while helping build a shared collection of examples that demonstrate Tidyverse functions in R.




## Part 1: Create an Example (25 points)


**Due:** Your first vignette must be added by Monday, 11/2/2026.




Create a programming-sample **vignette** that demonstrates one or more capabilities of one or more Tidyverse packages using a dataset of your choice.




Your vignette should:




- Use one or more Tidyverse packages (for example, **dplyr**, **tidyr**, **ggplot2**, **readr**, **stringr**, or **lubridate**).
- Use a dataset from [FiveThirtyEight](https://fivethirtyeight.com/), [Kaggle Datasets](https://www.kaggle.com/datasets), or another source that you clearly identify.
- Include annotated R code that explains what each important step does.
- Demonstrate meaningful data work, such as importing, cleaning, transforming, summarizing, reshaping, or visualizing data.
- State the dataset source and the package(s) and function(s) demonstrated.




You may submit an R script (.R), R Markdown document (.Rmd), or Quarto document (.qmd). Include any supporting data or files needed for classmates and the instructor to understand your work, subject to the dataset's licensing and size limits.




## Part 2: Extend a Classmate's Vignette (15 points)




Later in the course, select one classmate's vignette and extend it with additional annotated code. Your extension should add a meaningful new analysis, transformation, visualization, or Tidyverse technique.




## GitHub Workflow




1. Create a **fork** of this repository in your own GitHub account.
2. Add your vignette and any appropriate supporting files to your fork.
3. **Edit this README in place** in your fork: add a row to the **Class Vignette Index** section below describing your initial vignette.
4. Open a pull request from your fork back to this shared repository.
5. After creating your vignette, submit your GitHub handle through the course submission link so your work can be peer-graded.
6. When you complete Part 2, return to this README and add a row to the **Vignette Extensions** section identifying the classmate and vignette you extended.




Do not submit work to the previous course repository. Use this repository for the current class only.




## Class Vignette Index




**Students:** Edit this README in place by adding one row for your Part 1 vignette.




| Author | Vignette | Packages / Functions | Dataset | What It Demonstrates |
| --- | --- | --- | --- | --- |
| Your Name | [your_vignette.qmd](your_vignette.qmd) | dplyr::filter(), dplyr::mutate(), ggplot2::ggplot() | [Dataset source](https://example.com) | A brief description of your analysis and techniques. |


| Author | Vignette | Packages / Functions | Dataset | What It Demonstrates |
| --- | --- | --- | --- | --- |
| Patricio Romero | [Exploring Vehicle Fuel Efficiency with Tidyverse](vehicle_fuel_efficiency_tidyverse.qmd) | dplyr::select(), dplyr::filter(), dplyr::mutate(), dplyr::group_by(), dplyr::summarise(), ggplot2::ggplot(), ggplot2::geom_col(), ggplot2::geom_point(), stringr::str_to_title() | [ggplot2 mpg dataset](https://ggplot2.tidyverse.org/reference/mpg.html) | Cleans and transforms vehicle data, compares city and highway MPG, summarizes fuel efficiency by vehicle class, and creates visualizations. |


## Vignette Extensions




**Students:** After completing Part 2, edit this README in place by adding one row that states **whose vignette you extended** and links to both the original and your extension.




| Extending Student | Original Author | Original Vignette | Extension File | New Tidyverse Work Added |
| --- | --- | --- | --- | --- |
| Your Name | Classmate Name | [original_vignette.qmd](original_vignette.qmd) | [your_extension.qmd](your_extension.qmd) | A brief description of the added analysis, transformation, or visualization. |
