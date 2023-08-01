## Sentence-Similarity-Score-Using-BERT
# Calculate the similarity between two sentences

# Live Working Interface
![Result Page](https://github.com/gyanendra2003/Sentence-Similarity-Score-Using-BERT/assets/109502452/8f079bf6-2897-4a8d-aa1c-318c5228978c)


# Deployment
We fail to deploy the flak app on any free paltform because of memeory  limit issue that's why we cannot also upload ``` My_model.pkl``` model file.
# Setting up Python Virtual Environment for Running Flask App

This guide will walk you through the process of setting up a Python virtual environment to run a Flask application. A virtual environment allows you to isolate dependencies for your Flask app, ensuring a clean and consistent environment.

## Prerequisites

Before you proceed with the setup, make sure you have the following installed on your machine:

- Python: [Install Python](https://www.python.org/downloads/)

## Step 1: Clone the Repository

Clone the repository containing your Flask application code:

```
git clone https://github.com/ayushrag1/Sentence-Similarity-Score-Using-NLP.git
cd Sentence-Similarity-Score-Using-NLP
```

## Step 2: Create a Virtual Environment

Create a new Python virtual environment for your Flask app:

### On Windows:

```
python -m venv venv
```

### On macOS and Linux:

```
python3 -m venv venv
```

This will create a new directory named `venv` that contains the virtual environment.

## Step 3: Activate the Virtual Environment

Activate the virtual environment to start using it:

### On Windows (cmd):

```
venv\Scripts\activate
```

### On Windows (PowerShell):

```
venv\Scripts\Activate.ps1
```

### On macOS and Linux:

```
source venv/bin/activate
```

## Step 4: Install Flask and Dependencies

With the virtual environment activated, you can now install Flask and other dependencies required for your application:

```
pip install -r requirements.txt
```

## Step 5: Run the Flask App

You are all set to run your Flask app now! Use the following command to start the development server:

```
python ./myapp/app.py
```

Your Flask app should now be accessible at `http://localhost:5000` in your web browser.

## Step 6: Deactivate the Virtual Environment

To deactivate the virtual environment and return to your system's default Python environment, simply use the following command:

```
deactivate
```


## Troubleshooting

If you encounter any issues during the setup process, feel free to open an issue in this repository.

Happy Flask development!
