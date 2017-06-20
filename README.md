# Movies_app

This application created for storing simple information about your favorite movies. Use it with a pleaser!
Run this app locally.
**First** you need to clone this repo at your PC.

>git clone https://github.com/GAsdeX/Movies_app_backend

>git clone https://github.com/GAsdeX/Movies_app_frontend

This app divides into two cases: backend and frondend. Chack it out at same titled directories.

Please run mongodb on your machine:

```bash
sudo mongod>
```

Current your database is empty but not for a long time.

**Second** install the backend. Enter */backend* folder and install npm packages:

```bash
npm install 
```
A local server is working on localhost:3000. It listens to mongodb collection *movies*. 
Run backend.

```bash
npm start
```
Now your backend must work!

**Thurd** install the frontend. Enter */frontend* folder and do the same install:

```bash
npm install
npm start
```
Now run the app on *localhost:8080*

As early was said the db is empty. Pull the first data! Click green circle. Fill all the fields and press "Add movie".
Also, you can load data containing in a file. Choose file and load it. It is an ini format.

Now your db contains data.

Test an ability deleting of a card. Press on a little circle button at the top right corner.
Press on the card to learn more about the movie.
Search a movie by actor name and by movie name.
Also, sort the movies bu alphabet 
