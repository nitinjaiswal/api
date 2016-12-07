# Code Setup guide

This api is already hosted on heroku at [https://vast-everglades-95203.herokuapp.com/wingify/api/v1.0/product/](https://vast-everglades-95203.herokuapp.com/wingify/api/v1.0/product/).

But still this is the code setup guide

## System Dependencies
- Pyhton 3.4

## Clone repo

Clone repo from [https://github.com/nitinjaiswal/product-api](https://github.com/nitinjaiswal/product-api)

Thr directory `product-api` contains three main files:

- **app.py**: This is the main api file.
- **test.py**: This file is for testing the api.
- **requirements.txt**: This file contains requirements required by the app.py and test.py

### Directory Structure
```
    -|/api/
           -|/app.py
           -|/test.py
           -|/requirements.txt
           -|/...
           
   
```



## Create Virtual Enviroment

 - Install virual enviroment using command `pip install virtualenv`
 - Make virtual eviroment inside `product-api` directory using command `virtualenv flask`
 - activate virtualenv using `.\flask\Scripts\activate`
 
## Install requirements

- After activating virtualenv
- Install requirements by using command `pip install -r requirements.txt`

## Running api

 - Run app.py using command `python app.py`
 - Now api is live on localhost:5000 or given localhost
 - Now go to `https://localhost:5000/wingify/api/v1.0/product/` to use api
 
## Testing api
 - To test the api, run `test.py` using command `python test.py`
 -

 
