# python-word-count-beam
# Hemanth Venkata Reddy Telluri
### Check pip version if not available install it
* python --version
### in my system already had pip version, updated it
* python -m pip install --upgrade pip
### for python environment.  i have created env for the project
* python -m venv C:\Users\s542393\Documents\44517\python-word-count-beam
### python activated in my project
python -m pip install apache-beam
### run the word count
python -m apache_beam.examples.wordcount --input input.txt --output out
