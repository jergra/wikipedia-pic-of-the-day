dec 15, 2022

C:/dev/pic

this updates the project from september 16, 2021, 
redeploying from 'heroku' to 'pythonanywhere' and improving the css

this is a flask website which is a stand-alone display of the 
wikipedia 'today's featured picture' which is down the 
wikipedia main page:
    https://en.wikipedia.org/wiki/Main_Page
wikipedia has its own stand-alone display:
    https://en.wikipedia.org/wiki/Template:POTD_protected

the inspiration for this project is from exploring the 
wikipedia API, the main page of which is:
    https://www.mediawiki.org/wiki/API:Main_page

there, I found a tutorial with python and flask code to 
build a 'Picture of the day viewer'. 

The completed tutorial is on the ACER ASPIRE computer:
    C:\webdev\pic-of-the-day>

Since this only retrieved the picture and not the caption, 
I took another approach and found scraping code which I used to 
scrape wikipedia's stand-alone page.

The advantage of this project over wikipedia's page is that 
the picture is larger and more conveniently presented at the 
top of the page.

to activate the virtual environment, type:
    ./virtual_env/Scripts/activate

start locally:
    activate virtual environment: ./virtual_env/Scripts/activate
    note: might need to do 'pip install -r requirements.txt' if
        we are doing a clone
    python app.py

deployed at:
    http://jergra43.pythonanywhere.com/
    
    It is necessary to login to pythonanywhere every three months
    to keep the website operating. They will send a reminder email.
 
to update:
    go to https://www.pythonanywhere.com/user/jergra43/files/home/jergra43
    login:
        jergra43
        !V------3e
    go to 'Files'
    go to the 'mysite' directory and upload the updated 'flask_app.py' file, or 
    go to the 'mysite/static' directory and upload the updated 'style.css' file, or 
    go to the 'mysite/templates' directory and upload the updated 'index.html' file

    at upper right, click on 'Web'
    click the green 'Reload' button

to update the code stored at github:
    git add .
    git commit -m 'message'
    git push

--------------------------

LEGACY INFO:

September 16, 2021

acer travelmate
C:\webdev\pictureProj2>

this is a flask website which is a stand-alone display of the 
wikipedia 'today's featured picture' which is down the 
wikipedia main page:
    https://en.wikipedia.org/wiki/Main_Page
wikipedia has its own stand-alone display:
    https://en.wikipedia.org/wiki/Template:POTD_protected

the inspiration for this project is from exploring the 
wikipedia API, the main page of which is:
    https://www.mediawiki.org/wiki/API:Main_page

there, I found a tutorial with python and flask code to 
build a 'Picture of the day viewer'. 

The completed tutorial is on the ACER ASPIRE computer:
    C:\webdev\pic-of-the-day>

Since this only retrieved the picture and not the caption, 
I took another approach and found scraping code which I used to 
scrape wikipedia's stand-alone page.

The only advantage of this project over wikipedia's page is that 
the picture is larger.

to activate the virtual environment, type:
    ./my_venv/Scripts/activate

start locally:
    activate virtual environment: ./my_venv/Scripts/activate
    note: might need to do 'pip install -r requirements.txt' if
        we are doing a clone
    python app.py

(update dec 15, 2022: UNDEPLOYED)
deployed at:
    https://wikipedia-pic.herokuapp.com/
    
to update:
    activate virtual environment: ./my_venv/Scripts/activate
    git add .
    git commit -m "message"
    git push
    go to heroku dashboard, select wikipedia-pic, under 'Deploy',
        bottom of page, click 'Deploy Branch'

