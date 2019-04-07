# Create Environment

```
py -3 -m venv venv
venv\Scripts\activate
```

# Run Dev 

```
$env:FLASK_APP = "router.py"
$env:FLASK_DEBUG = 1
flask run
```

# Run Production

```
flask run --host=0.0.0.0
```