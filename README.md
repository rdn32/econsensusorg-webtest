To run the tests
----------------
Assuming you have firefox on your local machine, and want to run locally

./tests/test_edit_discussion.py --username <username> --password <password> --baseurl http://localhost:8000 

To run on saucelabs server
./tests/test_edit_discussion.py --username <username> -- password <password> --baseurl http://econsensus.stage.aptivate.org --remoteurl <url-to-saucelab-session>  
