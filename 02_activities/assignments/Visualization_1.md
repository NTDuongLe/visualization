Source: https://data.ontario.ca/dataset/ontario-top-baby-names-female

Plot 1: 'Top 20 female baby names in Ontario 2023'

> What software did you use to create your data visualization?  
    - Python

> Who is your intended audience?  
    - Potential parents in Ontario who want to know the most popular baby girl's first names in the year 2023 (the most recent year with available data) for inspiration.

> What information or message are you trying to convey with your visualization?  
    - The top 20 most frequently registered as first name for baby girl in Ontario for the year 2023 in descending order from left to right. 

> What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?  
    - The graph focused on presenting clear, accurate and relevant data by sorting the popularity of the names in descending order.\
    - The bar charts are good for comparing quantities, such as the frequency of each name in this case. This makes it effective to show the differences in name popularity.\
    - I chose orange as the color for the bar graph as this color is neutral and colorblind-friendly. The names on the x axis labels are rotated to make sure they do not overlap and the data callouts on top of the bar chart are adjusted in reasonable size for readability.\
    
> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?  
    - Pandas and Matplotlib are used for data analysis and plotting. There are no random variables generated so there's no need to set a seed. The dataset is reproducable using the same coding logic.\
    - Comments are added to the code to explain certain portions and ensure readability.\
    - If the tool used to make the data visualization was not reproducible, this would limit access and flexibility, making it difficult for others to replicate the original work or tweak the visualization in any way for their own purposes.

> How did you ensure that your data visualization is accessible?  
    - Spacing and data callout: even though the colors are the same (all orange), there's sufficient spacing between each bar with data labels to distinguish each data/name from the other.\
    - Font: the axis labels, title and data labels are set to readable font size.

> Who are the individuals and communities who might be impacted by your visualization?  
    - Expecting parents in Ontario looking for popular baby names in recent year for inspiration.\
    - Researchers/organizations that want to monitor the trend in data or patterns for social-cultural studies.

> How did you choose which features of your chosen dataset to include or exclude from your visualization?  
    - I chose the top 20 names from the year 2023 because 2023 is the most recent year in the dataset. There were too many datapoints to display if all names are chosen to be displayed. Hence, I excluded datapoints that are earlier than 2023 and outside of top 20 in terms of registration frequency to provide clean and organized chart. This is to avoid overwhelming the audience with too much information.

> What ‘underwater labour’ contributed to your final data visualization product?  
    - Hospital staff who recorded the data over the years.\
    - All personnel who participate in the process of data collection, compilation, processing, and making this dataset publibly available for use. 
