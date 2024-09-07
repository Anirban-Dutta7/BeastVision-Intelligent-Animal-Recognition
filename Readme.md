## This is a repository where you can learn how to use all the necessary packages to perform data analysis using python <br>

Requirements:<br>
1. Python (any version)
2. Anaconda (optional though recommended) <br>

To install the required packages for this, download the requirements.txt and run the following command in the terminal:<br>
```pip install -r requirements.txt```

Using Anaconda
If you're using anaconda you can setup a virtual environment using the command:<br>
```conda create -p <your_environment_name> python==<your_python_version>```

Example: <br>```conda create -p myenv python=3.8.1```

You can activate the virtual environment using the command:<br>
```conda activate <your_environment_name>```

Example: <br>```conda activate myenv```

Then you can install the requirements:<br> ```pip install -r requirements.txt```

To deactivate the environment run the command:<br>
```conda deactivate```

To check the list of environments, run the command:<br>
```conda info --envs```