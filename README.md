# flaskr

```bash
# Setup virtual env
virtualenv --python /usr/bin/python2.7 env

# activate it
. env/bin/activate

# install the flaskr as a package
pip install --editable .

# setup flask environment
export FLASK_APP=flaskr
export FLASK_DEBUG=true

# initialize the db
flask initdb

# run the app
flask run
```

Run the tests
```
python setup.py test
```
