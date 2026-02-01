# An Exploratory Analysis of Road Traffic Collision Frequency and Severity pre- and post-20mph Implementation in Edinburgh and Glasgow

## Project Overview

This project analyses road traffic collisions (RTCs) pre- and post-20mph implementation in Edinburgh and Glasgow. The analysis was motivated by recent changes to traffic calming policy in both cities:

* **Edinburgh:** A citywide, blanket 20mph speed limit was introduced on all city center roads from 2016 onwards.
* **Glasgow:** Expanded its network of 20mph roads in 2016, but the approach was less radical than that adopted in Edinburgh.


**Road Safety Data Source:**

The relevant road safety data were derived from the Department for Transport's (DfT) centralized database:

* [DfT Road Accidents and Safety Data](https://www.data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-accidents-safety-data) (Contains public sector information licensed under the Open Government Licence v3.0).

**Traffic Data Source:**

The relevant traffic data were derived from the Department for Transport's (DfT) traffic statistics:

* [DfT Road Traffic Bulk Downloads](https://roadtraffic.dft.gov.uk/downloads) (Contains public sector information licensed under the Open Government Licence v3.0).



## Repository Contents

* **`code`:** Contains an R Markdown file with the code for the descriptive analysis: a sequence of visualisations followed by statistical tests.
    * `collision_severity_descriptive_analysis.Rmd` contains R code to reproduce traffic volume and RTC visualisations.
* **`data`:** Contains the processed datasets used for the analysis. (Note: These are directly readable from the GitHub repository).
    * `ED_GLA_collisions_traffic_summary.csv`contains summary RTC and traffic stats for Edinburgh and Glasgow over the study period.
    * `ED_GLA_SV_LS_collisions_traffic_summary.csv` contains equivalent information for a single-vehicle, low-speed subset of RTCs (i.e., collisions that are particularly relevant to pedestrian safety).

## Usage

1.  **Download:** Download the entire contents of the repository.
2.  **Access Model Code:**
    * Open the R Markdown files in RStudio or a similar environment:
3.  **Run the Code:**
    * The model data are directly readable from the repository. You should not have to change the file pathname (however, if the data do not load, you can load directly from your own PC).
    * To run the R Markdown files successfully, ensure the following R packages are installed:
        * `ggplot2`
        * `cowplot`
    * Note: see `session_info.txt` in `code` for package dependencies
4.  **Execute:** Run the entire R Markdown file to reproduce the analysis.

## Acknowledgments

The authors would like to acknowledge the UK Gov. DfT for their provision of publicly accessible road safety and traffic data.

## Contact

* **Email:** <torran.semple@eng.ox.ac.uk>
* **Alternative Email:** <torranas@gmail.com>
