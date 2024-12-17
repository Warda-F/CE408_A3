# CE408_A3
The assignment uses Spark on Docker to implement Exploratory Data Analysis (EDA) on the CSV dataset of Netflix TV shows and Movies by Computational Thinking Labs (available on GitHub).

The steps followed are listed as belows:
1. Set up Docker using Docker Desktop and navigate to terminal.
2. Pull the official Apache Spark image for Docker (apache/py-spark) using docker pull command.
3. Run Docker container with Apache Spark and set the environmental variables.
4. Install the dataset (netflix_titles.csv) within the container using the wget command.
5. Launch pyspark.
6. Run the python codes as provided in the Jupyter Notebook uploaded to perform EDA on the dataset.
7. Exit the session and docker container.
