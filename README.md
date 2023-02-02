# Flask-background worker
 
##  use correct version of Python when creating VENV
python3 -m venv venv

##  activate on Unix or MacOS
source venv/bin/activate

##  activate on Windows (cmd.exe)
venv\Scripts\activate.bat

##  activate on Windows (PowerShell)
venv\Scripts\Activate.ps1

##  Activated environment will appear
(venv) D:\Flask-Simple-app>

# Send request below which will execute a long running tasks but the api will give quick response.
<pre>

curl --location --request GET 'http://127.0.0.1:9001/simple_module/long_task_endpoint'
</pre>

# Setting up requirements

## requirement.txt
### -  Create requirements.txt file
### - Add flask as primary requirement
### - celery==5.2.7 , redis

##  install the modules in your requirements.txt file

### pip install -r requirements.txt