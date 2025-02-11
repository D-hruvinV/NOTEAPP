# MERN Note App

Demo : https://noteappfrontend.vercel.app

Note app built with MERN stack.

Create .env file and add in server directory.

```
MONGO_URI="Cluster connection string. Can not be left empty."
PORT="Default is 8080 if left empty."
DAO_OPTION="Currently MONGOOSE is only option available. It is also the default option if left empty."
JWT_SECRET="Can not be left empty."
```

Create .env.local file and add in client directory.

```
VITE_API_URL='http://localhost:8080'
```
