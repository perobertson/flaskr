# flaskr

```bash
# Setup virtual env
virtualenv --python /usr/bin/python2.7 env

# activate it
. env/bin/activate

# install the flaskr as a package
pip install --editable .

# run the app
export FLASK_APP=flaskr
export FLASK_DEBUG=true
flask run
```
