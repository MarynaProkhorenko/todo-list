# todo-list

In this project, I implemented a simple task-manager.


## Installation 

Python3 must be already installed

```shell
git clone https://github.com/MarynaProkhorenko/todo-list
cd todo_list
python3 -m venv venv
source venv/bin/activate  # on macOS
venv\Scripts\activate  # on Windows 
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver #starts Django Server
```
In main folder you'll find a file .env_sample. In this file an example of SECRET_KEY is stored, required for the project.

You may need create a file .env and write here you secret key as in example.
## Demo

![Website Interface](To_do_list.png)

<br />

