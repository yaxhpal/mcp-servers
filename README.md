# README #

This README documents steps necessary to get the application up and running.

### What is this repository for? ###

This is **Conversive AI** project. The project is aimed to provide core Gen AI
services to Conversive framework

* Version
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

### How do I get set up? ###

* Clone the **Conversive AI** repository
```shell
git clone https://git.txtbox.in:8080/smsmagicportal/conversive_ai.git
cd conversive-ai
```
* Create virtual environment
```shell
mkdir -p ~/virt
python3.9 -m venv ~/virt/conversive_ai
source ~/virt/conversive_ai/bin/activate
```
* Dependencies - install all required packages
```shell
pip install -U pip
pip install -r requirements.txt
```
* Configuration - Modify environment variables in `.env` file
* Run the application
```shell
export FLASK_APP=src/main.py
export ENV="TEST"
export PYTHONPATH=$PWD
flask run
```
* Access application at http://127.0.0.1:5000
* 
### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Yashpal Meena <yashpal.meena@screen-magic.com>
