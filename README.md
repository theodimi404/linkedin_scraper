# Linkedin Scraper

This project is a scraper that extracts data from the user's connections on Linkedin. It requires the username and the password of the user.
When the credentials are given, it saves a .xlsx file, that contains the following info if available of every connection that the user has.

- Profile url 
- Email
- Date that the user connected with him/her
- Birthday
- If he/she is currently working somewhere

## Instalation

You can install the required modules using the following command

```bash
pip install -r requirements.txt
```

You also need to install the WebDriver

- For Google Chrome you can find the WebDriver in: https://chromedriver.chromium.org/downloads
Copy and Paste the folder that contains the webdriver inside the PATH, e.g. you can paste it in the directory where python is installed.

## Disclaimer

I built this project, only to strength my skills on web scraping and find out more on this field. It is not recommended to use it by all means. 