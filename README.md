# Social Media

## 🔧 Pre-requisites

Before running the project, you must have the following tools installed on your machine: 
* [Python v3.11.0](https://www.python.org/downloads/release/python-3110/)
* [Django v4.1.5](https://docs.djangoproject.com/en/4.1/topics/install/#installing-official-release)

Also, you will need to clone the repository:

```bash
## Cloning the repository
git clone https://github.com/mateuseap/social-media
## Entering the directory
cd social-media
```

## 🚀 Project setup

### > Running the migrations

To run the migrations, you'll need to run the command below:

```bash
## Running the migrations
python manage.py migrate
```

### > Creating a superuser

You'll need to create a superuser to access the admin panel:

```bash
## Creating a superuser 
python manage.py createsuperuser
```

After running the above command, you just need to follow the steps below to create your superuser:

![creating_superuser](https://i.imgur.com/lWiY8hU.jpg)

With a superuser created, now you have the access to the admin panel. If the project is running, you can go to [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin) and login into the admin panel using your superuser infos:

![admin_panel_login](https://i.imgur.com/K2DCP9X.png)

After you log in, you'll have the access to info about the database and much more inside one page:

![admin_panel](https://i.imgur.com/hGcSGv7.png)

### > Running the app

You'll need to run the command below:

```bash
## Running the app
python manage.py runserver
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000) to view it in the browser.