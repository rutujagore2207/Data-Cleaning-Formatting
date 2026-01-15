# Data-Cleaning-Formatting
In this project, I worked with a Kaggle dataset in CSV format and performed complete data cleaning and preprocessing using Excel/Google Sheets, following industry-standard analyst practices.

First, the dataset was downloaded from Kaggle and imported correctly, ensuring the first row was treated as column headers and the delimiter was properly separated. Header rows were frozen using Freeze Panes, and filters were applied to all columns to allow efficient data exploration.

Next, I identified missing values by filtering blank cells column-wise. These missing values were highlighted using Conditional Formatting, and decisions were made based on column context—some values were replaced where appropriate, while others were left blank or removed to maintain data integrity.

To handle duplicate records, I created a backup sheet before applying the Remove Duplicates feature using key columns such as ID or Title. This ensured no irreversible data loss occurred during cleaning.
