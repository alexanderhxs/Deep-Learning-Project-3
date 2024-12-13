### Project 2 - Deep Learning for Science ###
This repository is for the Submission of Project 2 for the course Deep Learning for Science at TalTech. The folder structure is as follows:
* **Notebooks:**  Contains the JupyterNotebook files with the code for the exercises
* **data:** Contains some example pictures for YOLO and semantic segmentation, as well as the time series data for the RNNs
* **models:** Contains the pretrained and fine-tuned models used in the exercises
* **mlflow:** Contains the mlflow logs of all trainings.

**Access the mlflow runs:** To access the runs properly mlflow has to be started. If you want to run the code, this should be done before executing the code, otherwise you will run into an error. To start mlflow you need to go into the Terminal and change the directory first. If you clone the repository the terminal will run in the "Deep-Learning-Project-2" folder, but the files are in the folder "mlflow". So type "cd mlflow" into the terminal to get to "Deep-Learning-Project-2/mlflow". From this point you can start mlflow by typing "mlflow server", then a link should open, where you can see the uns and projects in your browser.
