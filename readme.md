# Rasa for beginners (demo)

Create a new virtual environment by choosing a Python interpreter and making a ./venv directory to hold it:
```
python3 -m venv ./venv
```

Activate the virtual environment:
```
source ./venv/bin/activate
```

Install Rasa Open Source using pip (requires Python 3.7, or 3.8).
```
pip3 install -U --user pip && pip3 install rasa
```

You are now ready to go! So what's next? You can create a new project by running:
```
rasa init
```

Rasa Train
```
rasa train
```

Rasa run
```
rasa shell
```

Rasa interactive
```
rasa interactive
```
