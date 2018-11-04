# Adaptive Interactive Agent on Ubuntu 16.04
step 1 : Check Python & pip version if exist 
On Ubuntu, Python is automatically installed and pip is usually installed. Confirm the python and pip versions:

```sh
  $ python -V  
  $ pip -V     
```

step 2: If not install then follow the below commands

```sh
  $ sudo apt-get install python-pip python-dev   # for Python 2.7
```

Step 3: We need upgraded pip version, to upgrade pip:

```sh
    $ sudo pip install -U pip
```

Step 4: Now, download the flask-chatterbor project from github

```sh
    $ cd Desktop/ #now, current is /home/(username)/Desktop
    $ sudo git clone https://github.com/chamkank/flask-chatterbot

```
	Cloning into 'flask-chatterbot'...
	remote: Enumerating objects: 107, done.
	remote: Total 107 (delta 0), reused 0 (delta 0), pack-reused 107
	Receiving objects: 100% (107/107), 45.42 KiB | 0 bytes/s, done.
	Resolving deltas: 100% (41/41), done.
	Checking connectivity... done.


Step 5: extract the project. Now, To Install chatterbot, flask and other prerequisites packages for Python: 

```sh
    $ cd flask-chatterbot      
    $ sudo pip install -r requirements.txt   # Python 2.7
```

step 6:Check the programs properly executes or not. 

```sh
    $pwd #check your current directory, it must be /home/(username)/Desktop 
    $python app.py
```

step 7:If any issue happen then click on the link below and find the solution 

```sh
     https://github.com/chamkank/flask-chatterbot/issues
```

step 8: To get webview follow the screenshots belowed:

![first](1.png "first")

![first](2.png "first")

![first](3.png "first")  
