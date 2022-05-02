# Algovote
![GitHub](https://img.shields.io/github/license/jacopoesposito/algovote?color=red&style=flat-square)
AlgoVote is an experiment of a de-centralized app based on Algorand that implements a decentralized voting system, made for learning purpose. 

This DAPP allows users to vote for a candidate into a virtual election; this is only a starting point for future implementation. 
Indeed it's only limited to:
- the deployment of the application on a local node of Algorand Blockchain
- the execution of an example voting transaction,
- the showing of the result of the elections,
- finally, the destroyment of the DAPP with the consequent elimination of the data associated with the user. 

## Requirements
- Algorand Sanbox
- Python 3.0
- Pyteal

## Installation 
* First make a clone of the repository
```
$ git clone https://github.com/jacopoesposito/Mooncake.git
```
* Initialize Python Virtual Environment 
```
$ python venv venv
$ venv/bin/activate 
```
* Move to the project's directory and run the command, this will install all the requirements for this project
```
$ pip install requirements.txt
```
* After the installation of all dependencies, deploy the application to the algorand local node and run the example transaction by executing the script deployment.py using the command
```
$ python scripts/deployment.py
```
* Have fun!


## License 
[GNU/GPL 3.0](https://choosealicense.com/licenses/gpl-3.0/)