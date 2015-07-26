# HealthCruncher  
athenahealth hackathon 2015

Netflix but for insurance companies to predict customers' health outcomes.  
"B2B SaaS" (Business to business software as a service)  

It is also an API that attempts to follow the principles of REST  

## Development  
- Some stuff we use: `flask`, DigitalOcean, `scikit-learn`, `anaconda` ;)  
- `$ python main.py`  
- Test at `0.0.0.0:5000`  
- Use a `virtualenv` if you feel like it.  

## Deployment  
- `$ ssh root@strtup.me`  
- `$ cd /var/www/healthcruncher`  
- `$ git pull`
- In `main.py`, `debug` should be `FALSE`!!!  
- `$ . venv/bin/activate`  
- `$ nohup python main.py > /dev/null&` (TBD)  

## Undeployment
- `$ ps -fA | grep python`  
- Find the `<PID>` of the one that has python main.py
- `kill <PID>`  
- Save some 

## Todo
- Better the algorithm (actual data, better validation)  
- Better form validation (CSRF protection!)  
- Streamline deployment (scripts, etc.)  

## Primary roles
Rainier Ababao - web dev/deployment/data science  
Shaun Mataire -  iOS/deployment  
Hayley Call - web dev/business model  
Sarah Gorring - web dev/business model  

## Our original idea
A web app that accepts user input on easily accessible patient data and output metrics based on a machine learning algorithm.

