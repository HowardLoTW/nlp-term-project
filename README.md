# Write Cafe
A web-based English writing assistant with automatic grammar error correction (GEC).

### Tech Stack
  - Frontend: sass, es6, react, redux, webpack
  - Backend: nodejs for webserver, python flask for GEC business logic.

### Get Started

- Assume that you've installed python virtual environment package - `virtualenv`. You'll need to activate our virtual enviroment in this project, which contains all python packages required by this project.
```
>> source server/env/bin/activate
```
- Assume that you've installed nodejs and npm. Run `npm install` to install nodejs packages required by this project
```
>> npm install
```
- Since this project runs two different servers, one is nodejs for routings, the other is python flask API for GEC. Please enter the following two commands in seperate terminal taps, this will help you get the app started.
```
>> python server/app.py (Start python flask api server)
```
```
>> npm start (Start node web server)
```

### Problem Shooting
If there's any problem, please open an issue or send me an email.
