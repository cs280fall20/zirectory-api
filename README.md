# Zirectory Backend

This is the backend for Zirectory: The Zoom Directory App!

* Open the root folder in the terminal and type in `npm install`.
* You must refer to the lecture notes to setup a MongoDB cluster in the cloud. 
* Create a `.env` file and add your MongoDB URI.
  ```text
  DB_URI="YOUR_MONGODB_CLUSTER_URL"
  ```
* To run the application: `nodemon .` (make sure `nodemon` is installed; see the lecture notes).

You can deploy this backend to Heorku. Don't forget to transfer your environment variables (in `.env`) to Heroku's "config" variables.