# flask-backend

Backend rest server with [Flask](http://flask.pocoo.org/)

## About project
I will be developing and updating a fully functional backend server with complete test coverage and environment deployment support using docker and ansible.

> Please note: This is work in progress series of commits. I will be updating table of content fo help.

To clone the repo use :
```
git clone https://github.com/huzaifarasheedmir/flask-backend.git
```
If you have already cloned the branch and want to fetch latest updates use :
```
git fetch
git rebase -i origin/master
```
> Please note: There are different techniques of getting latest code you can use rebase, merge and pull study about them on git.

for switching to any commit copy the commit id from git: 
```
git checkout <commit id>
```
#### Contents


| Commit # |    Commit titile               |
|------|---------------------------|
| 1  | Setup basic app structure|
## Getting started

1. Install python package management tool pip

  ```
    sudo apt-get install python-pip
  ```

2. If you want to wokr in virtula env follow this or skip to step 3

  ```
    sudo easy_install virtualenv
    virtualenv flaskserver
    cd flaskserver
    source bin/activate
  ```
3. Go to project directory and install require packages using

  ```
    sudo pip install --upgrade -r requirements.txt
  ```
4. Run the server

  ```
    python manage.py runserver
  ```
6. Run tests
  
  * without coverage
  ```
    python manage.py test
  ```
  * with coverage
  ```
    python manage.py test --coverage
  ```
