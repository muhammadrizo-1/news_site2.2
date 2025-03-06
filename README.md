thats a project made by me, and the virtual environment may not be same as yours and it may give errors, for preventing that you should delete the directory named "venv", if there is no such a directory titled "venv" then skip this step.
after deleting that directory, you should create a new virtual environment for this project.
if you dont know how to create a virtual environment follow these steps:
1. cd "your disk:\your directory\yangilik_sayt"  if you didnt understand: here is an example: cd "D:\Django 2\yangilik_sayt". keep in mind! yours may not be same as mine
2. python -m venv venv
3. venv\Scripts\activate
4. venv\Scripts\Activate.ps1
5. if you get a permission error try this code: Set-ExecutionPolicy Unrestricted -Scope Process
6. pip install django
