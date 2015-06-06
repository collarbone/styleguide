# styleguide

## setting up the http server locally

to set up this environment to work locally you will need a few things. 
 - python 2.7 , your machine may already this installed. http://stackoverflow.com/questions/1093322/how-do-i-check-what-version-of-python-is-running-my-script

 - pip https://pip.pypa.io/en/latest/installing.html  , you may have this already if you have python installed.
 - virtualenvwrapper https://virtualenvwrapper.readthedocs.org/en/latest/install.html


once you have all that installed you need to make a virtualenv from the command line `mkvirtualenv styleguide` . You can do this from any directory. 

you should see "(styleguide)" in your terminal, mine looks like this: 

(styleguide)spencers-mbp:styleguide spencercooley$


To work on this project in the future you will need to type `workon styleguide` to activate the virtualenv. 


Now make sure you are in the project's directory and run `pip install -r requirments.txt`  this will install the python dependencies that are listed in the requirments.txt file. 


### Starting the web server

run the following commands from the project directory:

```
workon styleguide
```


```
python app.py
``` 


That will run the server and you can visit the application in the browser at `http://localhost:5000`





