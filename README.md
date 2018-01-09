# flask-fileupload

## Project Installation
**1) Install Virtualenv**
```sh
$ sudo pip install virtualenv
```
**2) Clone the project and cd to the cloned project**
```sh
$ cd "flask-fileupload"
```
**3) Create virutalenv**
```sh
$ virtualenv venv
```
**4) Activate virtualenv**
```sh
$ source venv/bin/activate
```
**5) Install packages**
```sh
$ pip install -r requirements.txt
```
  
## Running the server
  - $ export FLASK_APP=app.py
  - $ flask run
    * Running on http://127.0.0.1:5000/
    
## Change file upload directory
  - Change path in **"UPLOAD_FOLDER"** variable inside app.py file
  
## Flask Sources
* [Installation] - How to install Flask.
* [Quick Start] - A Minimal Application.
* [Uploading Files] - Basic on how to upload file
* [Deploy server] - Deploying the application to the webserver


[Installation]: <http://flask.pocoo.org/docs/0.12/installation/>
[Quick Start]: <http://flask.pocoo.org/docs/0.12/quickstart/#a-minimal-application>
[Uploading Files]: <http://flask.pocoo.org/docs/0.12/patterns/fileuploads/>
[Deploy server]: <http://flask.pocoo.org/docs/0.12/deploying/#deployment/>
