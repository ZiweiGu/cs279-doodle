# cs279-doodle

A doodle-like scheduler app built with Flask. The app uses SQLAlchemy, the Python SQL toolkit, to store users' preferences in a database. To run it locally, first clone the repo and navigate to the root directory. 
```
git clone https://github.com/ZiweiGu/cs279-doodle.git
cd cs279-doodle
```
Then, set up the virtual environment using virtualenv (installation methods [here](https://virtualenv.pypa.io/en/latest/installation.html)).
```
virtualenv -p python3 venv # Create a new virtual environment called venv
```
Activate the virtual environment:
```
source venv/bin/activate
```
Install necessary packages:
```
pip install -r requirements.txt
```
Use the following command and follow instructions in the terminal to run the app:
```
python3 app.py
```
