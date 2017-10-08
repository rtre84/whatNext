# Chatbots with Watson Conversation and Python
To run:

1. Import the Watson Conversation workspace from conversation/workspace.json into your Watson Conversation service.

Python:

1. cd into the python directory
2. Rename .env.template to .env
3. Add your Watson Conversation credentials to .env
4. Add your Cloudant Database Username, Password, and URL to .env
5. Add your Foursquare credentials to .env
6. Optional, create a virtual environment by running `virtualenv venv`
7. Optional, activate the virtual environment by running `source ./venv/bin/activate`
8. Install dependencies by running `pip install -r requirements.txt`
9. Run `python app.py`
10. Go to http://localhost:8080
