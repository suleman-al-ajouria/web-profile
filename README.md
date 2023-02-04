# web-profile

this is simple web profile using React js &amp; django rest framework ... 
to start this app in your local host you can follwo this steps:

### start backend server

1 + open root dir using two terminal or cmd 

2 + in first terminal you can go to the backend dir and create venv using this comand 

```sh
python3 -m venv myenv
```

Replace myenv with the desired name for your virtual environment

To activate the virtual environment, run the following command:

```sh
source myenv/bin/activate
```
Once the virtual environment is activated, you can install packages and start using them without affecting other packages on your system. When you're done using the virtual environment, you can deactivate it by running the `deactivate` command.

3 + install the packages using the command:

```sh
pip install -r requirements.txt
```

4 + now you can follow this command to run server:

```sh
python manage.py makemigrations

python manage.py migrate

python manage.py runserver

```

once you do that the server run on `127.0.0.1:8000` so you can see the api returned data from  the database ...
