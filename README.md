# Task-manager
**Task manager** allows to set tasks, assign performers and change their statuses. Registration and authentication are required to work with the system.

# Deployment
**Task manager** is also deployed on [DigitalOcean](https://www.digitalocean.com/), so feel free to register and make experiments with it:

All possible errors and bugs are sending to [Rollbar](https://rollbar.com/) automatically and will be fixed as soon as possible.

# Running

The easiest way to run this App is to use an official **Docker image**. You only need to specify a Django **secret key** (the one you like) and a **port** (e.g. 8000). Run the task manager with the following command:

```bash
docker run -d --env DJANGO_SECRET_KEY=<YOUR_KEY> -p 8000:8000 algosinc/task-manager 
```
Task manager will be available in a browser at ```http://0.0.0.0:8000/``` You may encounter some problems with Safari, so use another browser or open ```http://localhost:8000```.
