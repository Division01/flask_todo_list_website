This project was done to help me better understand the difference between Flask, Django and FastAPI. 
It's inspired from : https://www.youtube.com/watch?v=3vfum74ggHE 

To make it work as it is right now you can copy this code and run it (in bash) : 

```console
python3 -m venv venv
. venv/bin/activate

pip install Flask
pip install Flask-SQLAlchemy

export FLASK_APP=app.py
export FLASK_ENV=development
flask run
```

I might try to make it work with docker later on.