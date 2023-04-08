# HASTLEKH
Azure Hackathon 2021(Team Envisage)

* Video Link: https://drive.google.com/file/d/1r3UW3A4TppqN-yTFQ8PX-duQrdncFRKE/view?ts=60e1f593
* Demo Link: https://drive.google.com/file/d/1rdhjjX6KXclOPHnQfvI1_nBkedujXAJQ/view?ts=60e200c8
* PPT Link: https://drive.google.com/file/d/1FUGWlVlMnSQpGMuUaQiOOMguzt4R20PO/view?ts=60e1fd49

## INSTRUCTIONS FOR INSTALLATION:

* Clone the repository in your local system.
* Create virtual environment inside the cloned directory.
  ```
  python3.8 -m venv venv
  ```
* Activate the virtual environment.
  ```
  source venv/bin/activate
  ```
* Install the required dependencies from the requirements.txt file
  ```
  pip install -r requirements.txt
  ```
* IMPORTANT: Create one new folder in the project root directory with name 'processed'
  ```
  mkdir processed
  ```
* Run the command
  ```
  python run.py runserver
  ```
* Initialise the database using the command
  ```
  python run.py db init
  ```
* Migrate the changes in database
  ```
  python run.py db migrate
  ```
* Upgrade the database 
  ```
  python run.py db upgrade
  ```
