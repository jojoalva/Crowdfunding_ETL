# Crowdfunding Extract, Transform, Load Project
Description: This project has been completed to createe an ETL pipeline using Python, Pandas, and Python dictionary methods as well as regular expressions to extract and transform the data.

After the data has been transformed, four CSV files have been created, to assist with creating the ERD diagram. The ERD diagram was then used to create table schema. The CSV files' data was uploaded into a Postgres database, ready for SQL analysis. Below, you will find instructions on extracting and transforming the data, before instructing you in loading this into Postgres.


Instructions for setting up Jupyter Notebook:

        1. Ensure you have downloaded and installed Jupyter notebook via the python index.
        If not, you can find information on how to do this at:
        https://jupyter.org/install
        
        2. Download the ETL_Mini_Project_JAlva_DHewitt_KBraik.ipynb and the Resources folder into your local directory.

        3. Navigate into this directory from your terminal.

        4. Open Jupyter Notebook in this location. 
        
        5. Open the first file called 'ETL_Mini_Project_JAlva_DHewitt_KBraik.ipynb' into your open notebook.

        6. As you run each cell, by the end of the notebook, you will have created the 4 csv files you require to load into your Postgres database.


The Entity Relationship Diagram is within the 'Resources' directory, called 'crowdfunding_db_ERD' for your reference.

Instructions for setting up Postgres:

        1. Ensure you have downloaded and installed pgAdmin 4. If not, you can find this at:
        https://www.pgadmin.org/download/pgadmin-4-windows/.

        Please refer to the instructions on how to use pgAdmin 4 on the above website.

        2. Download the 4 csv files in the 'Resources' directory within this repository.

        3. Create a database called 'crowdfunding_db' within pgAdmin 4.
        Note- for this, you can either run the query within the 'crowfunding_db_schemas' SQL Source file inside pgAdmin4,
                or you can do it manually using the pgAdmin 4 documentation on the above website.

        4. Load the 'crowdfund_db_schemas' SQL source file within the 'crowdfunding_db' database you have just created.
        This SQL source file can be found in the 'Resources' directory held within this repository.

        5. Run the code within the file using the query tool. This will create the tables you require to load your data into.

        6. Load each csv file into the tables contained with the schema for our 'crowdfunding_db' database.
        Refer to the link above for instructions on how to do this.

        7. You are now ready to load the 'queries' SQL source file. This is also held in the 'Resources' directory in this repository.

        8. Run the code within the file using a new query tool page.

