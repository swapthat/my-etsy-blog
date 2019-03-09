#Instructions

* Activate virtual env ```$ workon etsywebsite```
* Virtual env is activated and cursor redirects to project dir automatically
* Type ```$ ./manage.py``` to execute django commands
* To run the project simply click the 'play' button in PyCharm

* To commit changes to github, use Github desktop program. Do not commit any .idea files

##Deployment
* Commit changes to github
* Go to pythonanywhere console, then ```$ git pull```
* Then ```$ ./manage.py collectstatic```
* Then ```$ ./manage.py migrate``` (if you made any changed to models)
