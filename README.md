# NYCProject<p>
**Emma, Wendy, and Chris' NYC Project!**<p>
You can use this site and the additions we made to find your way around NYC.<br>
You can search by Borough, Activity, or Venue.<br>
Each venue displays a photo of the location and provides a link back to the homepage.<br>
We chose simple fonts and backgrounds for easy readability and user friendliness.<p>

This website was developed using the Python-based Django web framework.<br>
GitHub was used for collaboration.<br>
You can see the whole project and our contributions at:<br>
https://github.com/MsWendyKH/NYCProject<p>

**Please report any issues regarding usability or compatibility to us through our GitHub Profiles**

>Emma:  https://github.com/Kwiklearner99<br>
>Wendy: https://github.com/MsWendyKH<br>
>Chris: https://github.com/Kwyjib0<p>

## Make Sure Pip and Venv are Installed<p>

### 1. Install Pip

*In order to install pip and make sure you have the latest update, type the following from the terminal command line:* <br>

#### UNIX/OSX 
```
$python3 -m pip install --user --upgrade pip
```

#### Windows
```
py -m pip install --upgrade pip
```

*Check your pip version using:*<br>

#### UNIX/OSX
```
$python3 -m pip --version
```
#### Windows
```
py -m pip --version
```
  
### 2. Install Venv

*If you need to install venv (which you shouldn't if you're using python3 or newer, but just to check):*<br>

#### UNIX/OSX
```
$python3 -m pip install --user virtualenv
```
  
#### Windows
```
py -m pip install --user virtualenv
```
### 3. Activating (and deactivating!) a Virtual Environment

Once you have pip and venv installed, it's time to check if you can create a virtual environment!<br>

*Make a new directory to run venv:*<br>
  
In that directory, from the terminal command line:

#### UNIX/OSX
```
$python3 -m venv YOUR_DIRECTORY_NAME_HERE
```
  
#### Windows
```
py -m venv YOUR_DIRECTORY_NAME_HERE
```
  
This will make venv create a virtual Python installation in the YOUR_DIRECTORY_NAME_HERE folder.<p>

*Activate the virtual environment:*<br>

#### UNIX/OSX
```
$source YOUR_DIRECTORY_NAME_HERE/bin/activate
```

#### Windows
```
.\YOUR_DIRECTORY_NAME_HERE\Scripts\activate
```
    
*When you are done, you can deactivate:*<br>

#### UNIX/OSX
```
$deactivate
```

#### Windows
```
deactivate
```

## Now We're Ready to Start Building The NYC Project:

### 4. Create the virtual environment

Clone the repository folder to your computer and name the folder as you wish.
  
*At the root folder of the repository run:*  
```
python3 -m venv YOUR_FOLDER_NAME_HERE
```

### 5. Run the virtual environment

#### UNIX/OSX:
```
source YOUR_FOLDER_NAME_HERE/bin/activate
```
#### Windows:
*Powershell users:*
```
YOUR_FOLDER_NAME_HERE\Scripts\activate.bat
```
*Bash users:*

```
source YOUR_FOLDER_NAME_HERE/Scripts/activate
```
  
### 6. Install dependencies
```
pip install -r requirements.txt
```
### 7. Run Django
```
python manage.py runserver
```
### 8. Open your browser of choice to: 
```
http://localhost:8000
```
