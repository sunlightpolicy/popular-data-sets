# popular-data-sets

An analysis of the most popular open datasets on U.S. local and state data portals.

See our [blog post](https://sunlightfoundation.com/2017/09/11/whos-at-the-popular-table-our-analysis-found-which-open-data-the-public-likes/) for background info and a summary of results for this project.

Highlights of this repository:
- Our detailed methodology can be found in our Jupyter Notebook (["Socrata API Open Data Portal Analysis - Final Version.ipynb"](https://github.com/sunlightpolicy/popular-data-sets/blob/master/Socrata%20API%20Open%20Data%20Portal%20Analysis%20-%20Final%20Version.ipynb)), which contains both the code itself and explanations of the process and decisions that were made. If you want, you can use this to run your own analysis.
- The analysis generated a set of 52 dataset topics, each of which respresents a cluster of related datasets. Using a popularity measure that is explained in the Jupyter Notebook, we ranked these dataset topics by popularity. We have a table (["final_topic_ranks.csv"](https://github.com/sunlightpolicy/popular-data-sets/blob/master/final_topic_ranks.csv)) that has that ranked list.
  - Note that the "Topic Content" is the set of words that the clustering algorithm used to define the cluster of related datasets for a topic. The words were of decreasing importance going from left to right in the list. For example, in the second-highest ranked topic (ID number 3), "transportation" was the most important word for the cluster while "bike" was the least important.
- If you're wondering which individual datasets where classified into which topics, go to the ["topic_datasets" folder](https://github.com/sunlightpolicy/popular-data-sets/tree/master/topic_datasets), which has a list of all the datasets that were part of the cluster for each topic. Note that the individual tables are large and best viewed in a spreadsheet program like Excel.

Thanks for checking out this repo, and let us know if you have any questions by opening an issue or emailing opencities@sunlightfoundation.com.
