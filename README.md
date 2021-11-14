# NYCProject<p>
**Emma, Wendy, and Chris' NYC Project!**<p>
You can use this site and the additions we made to find your way around NYC.<br>
You can search by Borough, Activity, or Venue.<br>
We chose simple fonts and backgrounds for easy readability and user friendliness.<p>

This website was developed using django, and GitHub for collaboration.<br>
You can see the whole project and our contributions at:<br>
https://github.com/MsWendyKH/NYCProject<p>

**Please report any issues regarding usability or compatibility to us through our GitHub Profiles.**

>Emma:  https://github.com/Kwiklearner99<br>
>Wendy: https://github.com/MsWendyKH<br>
>Chris: https://github.com/Kwyjib0<p>

You'll need pip for this.<p>
*In order to install pip and make sure you have the latest update, type the following from the command line in terminal:* <br>
$python3 -m pip install --user --upgrade pip<p>

*Check your pip version using:*<br>
$python3 -m pip --version<p>

*If you need to install venv (which you shouldn't if you're using python3 or newer, but just to check):*<br>
$python3 -m pip install --user virtualenv<p>

Once you have pip and venv installed, check to see if you can create a virtual environment.<p>
*Go to your preferred directory and run venv:*<br>
$python3 -m venv env<p>

This will make venv create a virtual Python installation in the env folder.<br>
*Activate the virtual environment:*<br>
$source env/bin/activate<p>

*When you are done, you can deactivate:*<br>
$deactivate<p>
  
## To start building our project:

### 1. Create the virtual environment

Clone the repository folder to your computer.
  
*At the root folder of the repository run:*
```
python3 -m venv venv
```
Make sure to call your virtual environment "venv"

### 2. Run the virtual environment
#### On Windows:
*Windows Powershell users:*
```
venv\Scripts\activate.bat
```
*Bash users:*
```
source venv/Scripts/activate
```
#### On Unix or MacOS:
```
source venv/bin/activate
```
### 3. Install dependencies
```
pip install -r requirements.txt
```
### 4. Run Django
```
python manage.py runserver
```
### 5. Open your browser of choice to: 
```
http://localhost:8000
```
