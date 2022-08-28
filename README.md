# KISHANMITRA
Machine Learning based Web Project to give Crop Predictions and Yield Predictions on basis of data supplied by user, and an API to get the results for usage in creation of more apps. 

### Local Deployment on Windows

1. Copy the `dfhmain` folder and `requirements.txt` file to a new folder.

2. Create a Virtual Environment in the folder using - 
```
pip install virtualenv

virtualenv dfhproject
```

3. Enter the Venv
```
dfhproject\Scripts\activate
```

3. Move to `dfhmain` and install required packages using -
```
cd dfhmain

pip install -r requirements.txt
```

4. Perform migrations
```
python manage.py migrate
```

5. Run the Project
```
python manage.py runserver
```

**Access the project on https://127.0.0.1:8000**
