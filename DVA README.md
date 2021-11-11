# Data and Visual Analytics

Various tools and techniques have been used in the four homeworks and a final project to analyze and visualize data at scale. View hw3_instructions.pdf and the corresponding subfolders for each question. 

Homework 1 - End-to-end analysis of TMDb data using Argo-Lite, SQLite, OpenRefine, Flask
- The Movie Database (TMDb) API used to scrape raw data which are then cleaned for later use
- Visualize co-actor network of Meryl Streep (for movies rated over 8.0, two degrees of separation) using Argo-Lite
- See final graph here: https://poloclub.github.io/argo-graph-lite/#a5358eae-4231-40a8-9be5-63b3fbeb2722
- Construct a TMDb database in SQLite3 in Python and perform various queries
- Visualize data trends via plots in webpages using D3 (to view html, set-up a local HTTP server) 
- Use Google's OpenRefine to clean and construct GREL queries 
- Use Flask to display TMDb table on a web-page (enter "python run.py" in cmd then open http://127.0.0.1:3001/)

Homework 2 - Tableau, D3 graphs and visualization
- Use Tableau to analyze and visualize board game data from BoardGameCreek 
- Create a force-directed graph using D3
- Create interactive plots that creates bar charts when mouse hovers on a point
- Create chrolopleth map that displays results based on filters, and shows additional details when mouse hovers over a country
- See readme.txt to view the htmls. An image preview is also available in a folder for each question

Homework 3 - Large data with Spark, Docker, DataBricks, AWS, GCP
-  Analyze a dataset containing millions of individual taxi trips from the New York City Taxi & Limousine Commission (TLC)
-  Use Apache's Pyspark in a Docker container to provide trip summaries, fare and traffic information
-  Use Spark and Scala in Databricks for various data queries and summary (see instructions.pdf for details)
-  Use Spark in Amazon Cloud (EC2, EMR, Hadoop) to find most profitable taxi dropoff locations in Manhattan
-  Use Spark in Google Cloud (Storage, Dataproc cluster) to filter the dataset and find values for several sub-tasks
-  Use Azure ML Studio to predict automobile price

Homework 4 - Other topics: PageRank, Random Forest, Scikit-learn
- Create PageRank algorithm from scratch and rank a graph network with 1 million nodes and 3 million edges
- Perform binary classification with Random Forests to determine if a person has diabetes using the below
- Create from scratch decision tree and implement random forest with bootstrap aggregating
- Compare results with Scikit-learn's Classifiers (Linear Regression, Random Forest, Support Vector Machines)

Final project - The Effect of Significant Events on Music
- This group project attempts to find if significant events can predict future trends in the music industry
- Music data and lyrics were scraped from BillBoard and Genius Lyrics
- Audio features were analyzed to find changes after an event
- Lyrics were analyzed to find if sentiment changed after an event
- A webpage has been created and can be viewed following the readme in the final project folder
