# studentlist
This app is useful for making studentlist . In list we can add data, Update and delete And sorted name with name and his skills

### Prerequisites

You need to install the following packages for backend:

```
asgiref==3.2.3
Django==3.0.1
django-cors-headers==3.2.0
django-jsonfield==1.4.0
djangorestframework==3.11.0
pkg-resources==0.0.0
pytz==2019.3
six==1.13.0
sqlparse==0.3.0
psycopg2==2.7.4

```
### Installation

Clone the repository

```
git clone https://github.com/Pramod0215/studentlist/
```

Setting up your virtual environment:

```
python3 -m venv .env
```

Activating Virtual  Environment

```
source .env/bin/activate
```
Once the repository is cloned and virtual environment set up, go to the directory where the requirements.txt(/React/studentlist$ ) is and type the following code in your terminal:
```
pip install -r requirements.txt
```

### Database (SQlite) : 
Using clould datebase which is provided by django.

Create database
```
python3 manage.py migrate
```
When changeing any field(add new field, Rename, Delate)
```
python3 manage.py makemigrations
```

For Frontend which is ReactJS,
Dependencies are: 
```
"nodejs":"^v8.10.0",
"npm":"^6.13.4",
"react": "^16.12.0",
"react-dom": "^16.12.0",
"react-router-dom": "^5.1.2",
"react-scripts": "0.9.5"

```

Go to '/React/studentlist/frontend/studentlist'  and type the following code in the terminal:
```
"sudo apt install nodejs",
"node --version",
"npm install", 
"npm -v",

```
Go to install axios for fetching data from backend
```
npm install axios
```

Then to run the react server, type the code:
```
npm start
```
# images
![alt Home Page](https://github.com/Pramod0215/Student-management-system/blob/studentdb/image/Screenshot%20from%202020-01-31%2018-53-53.png)<br>
