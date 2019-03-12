Sample project testing python flask server, with the aim of deploying to a raspberry pi

# Setup
## Auto setup
- Windows: scripts/setup.ps1

## Manual Setup
- Assuming windows, see [the flask docs](http://flask.pocoo.org/docs/1.0/installation/) for full details
- Install python 3 / pip
- In the root folder, run:
    - ```py -3 -m venv venv```
    - ```venv\Scripts\activate``` to activate the virtual environment
    - ```pip install -r requirements.txt```
    - ```python src\app.py``` to run

## Issues setting up on the raspberry pi
If you are having issues running the venv setup, try ```sudo apt-get install python3-venv```


# References
- [Flask docs](http://flask.pocoo.org/docs/1.0/installation/)
- [freeCodeCamp](https://medium.freecodecamp.org/how-to-build-a-web-application-using-flask-and-deploy-it-to-the-cloud-3551c985e492)
- [Miguel Grinberg](https://blog.miguelgrinberg.com/post/designing-a-restful-api-with-python-and-flask)