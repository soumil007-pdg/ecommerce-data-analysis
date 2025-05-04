# ecommerce-data-analysis
## Customer Segmentation and Lookalike Analysis
### Overview
This project performs customer segmentation and lookalike analysis using transaction data. It includes data preprocessing, feature engineering, customer segmentation, and identifying similar customers based on cosine similarity. The project is divided into multiple tasks, each implemented in separate Jupyter notebooks.
## Project Structure

### notebooks

lookalike(1).ipynb: Initial attempts at lookalike analysis.

segments.ipynb: Customer segmentation based on transaction behavior.


task[1,1_insights].ipynb: Task 1 - Data preprocessing and initial insights.


task_2.ipynb: Task 2 - Feature engineering and initial lookalike analysis.


task_2_remaining.ipynb: Task 2 - Completed lookalike analysis with cosine similarity and visualization.


task_3.ipynb: Task 3 - Further analysis (details TBD).

task_3_new_up.ipynb: Task 3 - Updated version with new features.


### outputs

CustomerSegments.csv: Segmentation results.



Lookalike.csv: Top 5 similar customers for each customer with similarity scores.


### visualization

customer_segments.png: Visualization of customer segments.


db_index-checkpoint.png: Davies-Bouldin index for clustering evaluation.


revenue_by_category.png: Revenue distribution by product category.


revenue_by_region.png: Revenue distribution by region.


sales_by_day.png: Sales trends over time.


similarity_scores.png: Distribution of similarity scores from lookalike analysis.


spending_by_tenure.png: Customer spending patterns by tenure.







# Outputs



Customer Segmentation: Results are saved in outputs/CustomerSegments.csv.


Lookalike Analysis: Top 5 similar customers for each customer are saved in outputs/Lookalike.csv.


Visualizations: Various plots (e.g., similarity_scores.png) are saved in the visualization/ folder.



# Key Features

Feature engineering: Total spending, transaction count, average spending per transaction, and average days between purchases.





One-hot encoding for regions.


Cosine similarity for lookalike customer identification.


Visualizations of similarity scores, revenue, sales, and spending patterns.




