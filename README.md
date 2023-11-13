# FLASK LANDING PAGE

This project is a landing page using Flask.

Flask is a lightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications. It began as a simple wrapper around [Werkzeug](https://werkzeug.palletsprojects.com/en/3.0.x/) and [Jinja](https://jinja.palletsprojects.com/en/3.1.x/) and has become one of the most popular Python web application frameworks.

Flask offers suggestions, but doesn't enforce any dependencies or project layout. It is up to the developer to choose the tools and libraries they want to use. There are many extensions provided by the community that make adding new functionality easy.

## Installation
### Create a project folder
In Pycharm, create a New Project with this name "Flask Landing Page" and check "New Environment Using" with the Dropdown choose Virtualenv

In Visual Studio Code, In VS Code, open the  Command Palette (View > Command Palette or (Ctrl+Shift+P)). Then select the Python: Create Environment command to create a virtual environment in your workspace. Select venv and then the Python environment you want to use to create it.

Make sure that you have this in your terminal:
```bash
(.venv) Ps your Repository Project>
```

### Activate VENV
On Mac/ Linux:
```bash
source .venv/bin/activate
```
On Windows:
```bash
.venv\Scripts\activate
```
### Install Flask
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install flask.
```bash
python -m pip install flask
```

## How to run
In the Integrated Terminal, run the app by entering 
```bash 
python -m flask run
```
This command will run Flask development server. The development server looks for 'app.py' by default. When you run Flask, you should see output similar to the following:

```python
(.venv) D:\py\\hello_flask>python -m flask run
 * Environment: production
   WARNING: Do not use the development server in a production environment.
   Use a production WSGI server instead.
 * Debug mode: off
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```

## Contributing

Pull request are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.
