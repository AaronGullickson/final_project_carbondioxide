# Carbon Dioxide Emissions and Urbanization

Carbon dioxide emissions through the consumption of fossil fuels are one of the primary causes of global warming. We know that population growth and levels of consumption both play an important role in a country’s carbon dioxide emissions, but the role of other factors is less clear. For example, increasing population density through urbanization is believed to have some positive environmental benefit by reducing sprawl and travel distances. On the other hand, greater urbanization is tied to higher levels of manufacturing and consumption. We will use the cross-national data to address the following research questions:

1. What is the effect of urbanization and population density on carbon dioxide emissions per capita? Pay careful attention to the effect of these two variables with and without controlling for the other variable.
2. Does the effect of urbanization vary by the income level of the country? 

For both of these questions, you should consider controls for a country’s income level, relative size of the working age population, foreign direct investments, and exports. 

We will use data from the World Bank’s World Development Indicators (WDI) database. This database contains cross-national data over time for most countries in the world. We will use data from 2010 to examine predictors of carbon dioxide emissions per capita. The data and more information about the dataset and variables are available in the `input` directory.

## Performing the analysis and producing the report

You can use either a separate script or an R Markdown file to perform your analysis, but the ultimate report should be written up using an R Markdown file. This R Markdown file should be knitted to a PDF file which you will upload to the Canvas site. You should also be sure to commit and push your final code and results back to GitHub. I will be evaluating both your written work and the analysis itself.

The report will typically be around 5-7 pages including figures and tables. The report should have the following format:

- **Introduction**: state the research question (in your own words). This is also a good place to indicate why this is an interesting research question. Use your sociological imagination here. 
- **Data and methods**: describe the data (where it came from, how variables were constructed, how big the sample is, etc.). You may use the report provided on each dataset to help craft this description, but **you must describe it in your own words**. You should include graphical presentations of the distribution of the dependent variable and the critical independent variable(s). 
- **Results**: Report what you found. Typically, this will involve a figure or multiple figures showing the key relationship (e.g. scatterplot, comparative boxplots, etc) and a table of regression model results. Be sure to interpret your results in straightforward concrete terms. Your results table(s) should include measures of statistical significance such as the standard error and an asterisks if the p-value was less than 0.05. Round all values in the table(s) to three decimal places. 
- **Conclusions**: Summarize the findings and discuss any weaknesses or ideas for future research.

All tables and figures should be well captioned and self-explanatory. I should be able to understand what the table or figure is reporting without reading the report itself. 
