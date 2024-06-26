# End-to-end-machine-learning-with-mlflow


## WorkFlow

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml
10. Update the app.py


## How I made the app
** Basic Setup **
1.	create github repository
2.	add gitignore python
3.	add license from mit
4.	clone the repo in local system 
5.	create a template file
6.	create a virtual environment
7.	change the interprete to the virtual environment in vs code
8.	run the template.py file
9.	push the changes
10.	make the requierments clear in requiernments.txt
11.	setup the setup.py file
12.	run requirements.txt file
13.	write/setup the logger details in __init__.py file in src/{projectname}
14.	write in common.py in utils in src file
15.	push it all

** Actuall Data Science **
1. make the data ingestion .ipynb file in research folder
2. update the config.yaml in terms of data ingestion (dont need schema or params file yet)
3. update the __init__.py file in constants (this gives the constant adress/directories/path to follow for data ingestion)
4. configuration manager in the data_ingestion file itself first.
5. create config_entity.py in entity file and then update it.
6. update the configuration.py in config folder
7. create data_ingestion.py in components and update it
8. create stage_01.py in pipeline and update it
9. update main.py
10. data_ingestion is dont, gitignore the artifacts folder , save everthing, push it and in the terminal run pythom main.py file.