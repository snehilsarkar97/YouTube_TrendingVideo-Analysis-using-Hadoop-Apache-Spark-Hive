# YouTube Trending Videos Analysis Using Hadoop & Hive

## Project Overview
This project leverages Hadoop and Hive to analyze trending YouTube videos across multiple countries from 2020 to 2023. By examining factors such as viewer engagement, video categories, and sentiment analysis, the project aims to uncover patterns in audience preferences and provide actionable insights for content creators and marketers.

## Objectives
- **Analyze Trending Videos**: Investigate and categorize YouTube videos that have recently gained popularity across different regions.
- **Explore Viewer Sentiments**: Assess how various factors influence viewer engagement and sentiment towards content.
- **Visualize Key Trends**: Present insights using visual tools like Excel and Tableau, highlighting trends in video popularity, viewership statistics, and engagement metrics.

## Platform Specifications
- **Hadoop Version**: 3.3.3
- **Hive Version**: 3.1.2
- **Cluster Configuration**: 
  - **Nodes**: 5
  - **CPU Cores**: 8 per node
  - **Total Memory**: 860.4 GB
- **Tools Used**: 
  - Apache Hadoop
  - Apache Hive
  - Tableau
  - Excel

## Dataset Specifications
- **Dataset Name**: YouTube Trending Videos
- **File Used**: Multiple CSV files from different countries (e.g., US, India, Brazil)
- **Format**: CSV
- **Total Size**: 3.76 GB (individual file sizes may vary)
- **Key Features**:
  - **Title**: Title of the video
  - **Channel Title**: Name of the channel that uploaded the video
  - **Publish Time**: Date and time of the video upload
  - **Tags**: Relevant tags associated with the video
  - **Views**: Number of views
  - **Likes**: Number of likes
  - **Dislikes**: Number of dislikes
  - **Comments**: Number of comments
  - **Engagement Score**: Custom metric based on likes, views, and comments

## Key Steps
### Data Acquisition
1. **Download Dataset**: Obtain the YouTube trending videos dataset from Kaggle.
2. **Upload to HDFS**: Upload the dataset files to the Hadoop Distributed File System (HDFS) for processing.

### Cluster Setup
- **Configure Hadoop and Hive**: Set up a Hadoop cluster with Hive for data management and analysis.

### Data Processing
1. **Schema Definition**: Define the schema for the dataset in Hive to ensure proper data types for each column.
2. **Data Ingestion**: Load the CSV files into the Hive table.
3. **Data Cleaning**: Perform cleaning operations to remove NULL values and irrelevant columns.
4. **Data Transformation**: Convert categorical data (e.g., tags) into numerical indices and calculate engagement scores.

### Data Analysis
- Use HiveQL to conduct various analyses, such as identifying the top trending videos based on views, analyzing the distribution of likes and comments, and exploring correlations between engagement scores and view counts.

### Data Visualization
- **Export Data**: Export processed data from Hive for visualization in Tableau and Excel.
- **Create Dashboards**: Build visual dashboards to showcase trends in video views, engagement over time, and viewer preferences across countries.

## Running the Project
### Clone the Repository
Clone this repository to access all project files.

### Dataset Upload
Download the YouTube trending videos dataset from Kaggle and upload it to HDFS.

### Run Code in  Hadoop Setup
- **Set Up Environment**: Ensure that the Hadoop and Hive environment is correctly configured.
- **Execute Queries**: Use the Hive CLI or a notebook interface to execute the provided SQL queries for analysis.

## Results
The analysis highlighted significant trends in viewer engagement and preferences for YouTube content across different regions. Key findings include:
- Most trending videos worldwide in last 4 years is ‘Turn into Orbeez – Tutorial.’
- Most of the trending videos worldwide are originated from South Korea, such as BTS – 15%, Blackpink- 23% and Jisoo & Jung Kook- 18%
- Most viewed channel in USA in last 4 years is ‘MrBeast’ (18.9 billion views)
- In USA, most watched channel from 2020-2023 are MrBeast, Blackpink, FFunTv & Big Hit Labels respectively.
- New, Song, Comedy, Video etc. are the most frequent searched words in last 4 years in INDIA.
- In last 4 years, all countries are mostly inclinedtowards ‘Entertainment’ category of their most watched videos

## Contact Information
For questions or feedback, please contact:

- **Snehil Sarkar**: [snehil.sarkar100@gmail.com](mailto:snehil.sarkar100@gmail.com)
- **Sapan Shah**: [sshah82@calstatela.edu](mailto:sshah82@calstatela.edu)
- **Sai Sridhar Karri**: [skarri2@calstatela.edu](mailto:skarri2@calstatela.edu)
- **Kaushik N Adhikari**: [kadhika3@calstatela.edu](mailto:kadhika3@calstatela.edu)

