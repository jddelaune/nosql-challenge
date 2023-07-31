# Exploring with PyMongo #
======

This project uses PyMongo via Jupyter Notebook to interact with a local MongoDB database. After creating the database and importing a json file with the data using a command in the terminal, the rest of the work occurs in two Jupyter notebooks: [NoSQL_setup](../NoSQL_setup.ipynb) and [NoSQL_analysis](../NoSQL_analysis.ipynb).

First we do some setup work, ensuring the database was correctly created, adding a new record, and giving it the correct BusinessTypeID.
Since we don't care about establishments in Dover, we delete those.
We correct some data types to Decimal and Integer.

With these steps completed, we move on to some exploratory analysis in our NoSQL_analysis notebook. While a higher RatingValue is better, a lower Hygiene score is better -- we are actually looking for the cleanest establishments near Penang Flavors.

## Try It Yourself ##

If you would like to run this code or experiment with further analysis of the data, the data itself is provided in the Resources folder as [establishments.json](../Resources/establishments.json).

This code was written in Python 3.10 with libraries pymong, pandas, and pprint required.

You will also need a version of MongoDB such as the MongoDB Community Server available at: https://www.mongodb.com/try

## Acknowledgements ##

I gained valuable insights into the princples involved in this project from discussions with Aaron Otto, and Kourt Bailey helped squash a particularly annoying bug.
