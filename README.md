# ETL_Pipeline_Project
Data ETL Pipeline using Python

Goal:
In data engineering, ETL pipelines are fundamental tools for extracting, transforming, and loading data from diverse sources into databases for analysis. I embarked on this project with the goal of not only mastering these concepts but also applying them to a practical scenario.

Data Collection:
The project commenced with the collection of data from a source – in this case, I chose the Fashion-MNIST dataset, a well-known benchmark in the machine learning community, conveniently accessible through the Keras library. This dataset represents a diverse range of clothing items, making it an excellent choice for our purposes.

Data Cleaning and Transformation:
Next came the fascinating part: data cleaning and transformation. I implemented Python scripts to normalise pixel values, ensuring they fell within the 0 to 1 range. This preprocessing step was crucial to prepare the data for further analysis and modelling. Additionally, I reshaped the dataset into a 4D tensor, ready for feature extraction and model training.

Data Loading:
One of the most rewarding aspects of this project was the data-loading phase. I utilised SQLite, a lightweight and efficient database management system, to create a database named "images." Within this database, I carefully structured the tables to store the image data along with their corresponding labels.

Data Insertion:
The ETL pipeline concluded with the insertion of both training and test data into the database. To ensure data integrity and consistency, I used Python's SQLite library to execute SQL commands, storing each image as a binary blob alongside its label. This step was vital for enabling quick access to data for future analysis and model training.

Conclusion:
In summary, this project represents a significant milestone in my data engineering journey. It not only equipped me with a deeper understanding of ETL processes but also demonstrated my ability to apply these skills in a practical context. The resulting ETL pipeline successfully extracted, transformed, and loaded the Fashion MNIST dataset into an SQLite database, setting the stage for seamless data access and analysis.
