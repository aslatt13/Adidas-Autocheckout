Resurrected a dead Adidas script. Shoutout Nathaniel for the help. Enjoy.

# Adidas-Autocheckout
An adidas autocheckout script using python and webdriver.

# Video Tutorial

[![Tutorial](http://img.youtube.com/vi/Xx4EvL177MM/0.jpg)](http://www.youtube.com/watch?v=Xx4EvL177MM)

This script requires python and chrome webdriver.

1. Download the script to your desired location.
	
2. Unzip the file.

3. [Download chromedriver](http://chromedriver.chromium.org/downloads) for your version of chrome and drag the exe into the script folder. (May need to add to PATH aswell).

4. cd <script folder location>

5. Install dependencies:
	
	pip install requests
		
	pip install selenium
	
6. Edit the config file with your desired credentials.
	
7. Run 'python autocheckout.py'
	
8. Login via the CLI.
	
	  username (adidas cart email)
		
	  password (adidas cart password)
		
9. The script will open chrome browser, login, and navigate to the cart. It will ask if you want to continue.
	
10. If so, it will fill in you details automatically.
	
Let it run, and happy cooking!




# To-Do List

1. Discord webhook cart integration
2. Headless mode
