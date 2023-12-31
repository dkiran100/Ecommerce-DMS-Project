# Ecommerce-DMS-Project

To run this project, start by having Python installed on your computer. Create a virtual environment to store your projects dependencies separately. You can install virtualenv with

```
pip install virtualenv
```

Clone or download this repository and open it in your editor of choice. In a terminal (mac/linux) or windows terminal, run the following command in the base directory of this project

```
virtualenv env
```

That will create a new folder `env` in your project directory. Next activate it with this command on mac/linux:

```
source env/bin/active
```

Install the project dependencies with

```
pip install -r requirement.text
```

Run the project with this command

```
python run.py runserver
```
Note if you want payments to work you will need to enter your own Stripe API keys into the .env file in the settings files.
