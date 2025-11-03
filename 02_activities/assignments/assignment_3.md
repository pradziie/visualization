# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    * Python: both Seaborn and PlotLy (.ipynb file). **Must be run first** to save the dataset for Power BI.

    * Power BI: two pages with a .csv dataset saved by the Python script to a relative path. No RDB or data models. Just a single file from the script. Sadly, web and API connectors were not working due to access being locked. I also created a UofT color/font Power BI scheme .json file under Color Schemes folder for everyone's use. 

    * Excel: just a bonus file with a different dataset. Has a couple pages with a table and a chart. Used to create a UofT Excel color scheme. In Windows, you can save the scheme under:
    C:\Users\<YourName>\AppData\Roaming\Microsoft\Templates\Document Themes\Theme Colors\

    > Who is your intended audience? 
    * Learning support :D. But seriously, OPS (Ontario Public Sector) is.

    > What information or message are you trying to convey with your visualization? 
    * Male vs Female pay delta trend in OPS over the years. Data also excludes anyone who does not identify as male or female, which could skew the results.

    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?
    * Bar charts, line charts, donut charts. Will probably add more later.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
    * I added a line to the Python file which saves the dataset to a relative path.
    * Python file itself does not use that file, it connects to it via the web.
    * Saved file is used by Power BI. However, the source may have to be reconnected if the path changes. Sadly, web connectors and API calls did not work without logging into OPS.
    
    > How did you ensure that your data visualization is accessible?
    * Avoided too many red/green colors. Used contrast. Simplified the visuals.  
    
    > Who are the individuals and communities who might be impacted by your visualization?
    * OPS workers curious about everyone's pay, ahah!  
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    * Ratios of some pay ranges had to be calculated and added in Python. May add in Power BI as a measure or transformed column later.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    * Learning staff checking this <: 
    * Me doing some of these activities to get used to producing those color schemes. I hope someone uses them later.
    * My gaming PC pulling way too much wattage over time for this
    * Python existing in open-source. Can't imagine how much went into that.

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 11/02/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
